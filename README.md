# customer-segmentation-portfolio
Customer Segmentation project using RFM analysis and K-Means clustering for e-commerce data.

# Overview
This project demonstrates **customer segmentation for an e-commerce company** using RFM analysis and K-Means clustering.  
The goal is to segment customers to optimize marketing campaigns, increase engagement, and improve revenue.

# Dataset
- Public e-commerce dataset (Online Retail)
- Key columns: InvoiceNo, CustomerID, Quantity, InvoiceDate, UnitPrice

# Approach
1. **Data Cleaning:** Removed missing CustomerID and canceled orders, converted InvoiceDate to datetime.  
2. **RFM Analysis:** Calculated Recency, Frequency, and Monetary metrics for each customer.  
3. **Clustering:** Standardized RFM metrics and applied K-Means clustering (k=4).  
4. **Insights:** Assigned descriptive labels to clusters and interpreted business implications.  
5. **Visualization:** Bar charts and pairplots to show customer segments.

# Customer Segments
| Segment | Description |
|---------|-------------|
| Super-Active High-Value | Frequent and high-spending customers. Target with VIP programs. |
| High-Spend Frequent | Frequent buyers with large total spend. Reward loyalty. |
| Moderate | Occasional buyers with moderate spend. Encourage engagement. |
| Inactive | Haven’t purchased in a long time. Win-back campaigns recommended. |

# Visualizations
- Average RFM metrics by segment (bar chart)
- Pairplot of RFM features colored by segment

# Skills Highlighted
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Data Cleaning & Preprocessing
- RFM Analysis
- K-Means Clustering
- Data Visualization & Storytelling
- Business Insight Interpretation

## View Project
- **Notebook:** `customer_segmentation.ipynb`  
- **HTML Render:** `customer_segmentation.html`
