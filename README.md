# E-Commerce Customer Segmentation (RFM Analysis)

## Project Overview

This project focuses on analyzing e-commerce customer purchasing behaviour using **RFM Analysis (Recency, Frequency, and Monetary Value)** and **K-Means Clustering**.

The goal is to identify different customer groups, understand their spending patterns, and provide useful insights for customer retention and marketing strategies.

## Internship Details

- **Organization:** Veda Technology
- **Task:** Day 43
- **Project:** E-Commerce Customer Segmentation
- **Tools:** Python, Google Colab, Pandas, NumPy, Scikit-learn, Plotly, Matplotlib, Excel

## Objectives

- Clean and preprocess online retail transaction data.
- Calculate Recency, Frequency, and Monetary values for each customer.
- Apply K-Means clustering to identify customer groups.
- Visualize customer behaviour through interactive charts.
- Generate downloadable CSV, Excel, HTML dashboard, and PDF report files.

## Technologies Used

- Python
- Pandas and NumPy
- Scikit-learn
- Plotly
- Matplotlib
- OpenPyXL
- Google Colab
- Microsoft Excel

## Methodology

1. Load the online retail transaction dataset.
2. Remove duplicate records and invalid transactions.
3. Handle missing values and convert data types.
4. Calculate customer-level RFM metrics.
5. Scale RFM features and apply K-Means clustering.
6. Assign customer segment labels based on relative RFM profiles.
7. Build interactive visualizations and export reports.

## RFM Metrics

| Metric | Description |
|---|---|
| Recency | Number of days since the customer's latest purchase |
| Frequency | Number of distinct orders placed by the customer |
| Monetary | Total amount spent by the customer |

## Customer Segments

- **Champions:** Customers with relatively strong purchasing activity and spending.
- **Potential:** Customers who may offer opportunities for further engagement.
- **At Risk:** Customers who may need re-engagement.
- **Lost:** Customers with comparatively weak recent purchasing activity.

Segment labels are based on relative cluster profiles and should be validated before business use.

## Dashboard Features

- Customer segment analysis
- Revenue by customer segment
- Customer frequency versus spending scatter plot
- Average recency and spending analysis
- Interactive country and segment filters in Google Colab
- Downloadable project outputs

## Project Outputs

- Customer RFM segmentation CSV
- Cleaned transaction CSV
- Segment summary CSV
- Project summary CSV
- Excel analysis workbook
- Interactive Plotly HTML dashboard
- Graph images, when image export is available
- PDF project report
- ZIP package containing generated outputs

## How to Run

1. Open [Google Colab](https://colab.research.google.com/).
2. Create a new notebook.
3. Copy the project Python code into a code cell.
4. Run the cell and wait for processing to finish.
5. Use the interactive dashboard and download the generated ZIP package.

## Dataset

The project attempts to use the UCI Online Retail dataset. If the dataset cannot be downloaded, the script generates a synthetic demonstration dataset. Check the printed data source before interpreting results or submitting the project.

## Conclusion

This project demonstrates how RFM analysis and K-Means clustering can be used to explore customer purchasing behaviour. The resulting dashboard and reports help summarize customer segments, spending patterns, and potential marketing opportunities.

## Author

**R. Kaniga**  
B.Tech – Artificial Intelligence and Data Science  
Muthayammal Engineering College

## Acknowledgement

Thanks to Veda Technology for providing the opportunity to work on this data analytics project and improve practical skills in data cleaning, customer segmentation, visualization, and reporting.
