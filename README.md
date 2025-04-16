# Fraud detection in credit card transactions with Isolation Forest/Power BI
Development of a fraud detection system for credit card transactions by applying the unsupervised machine learning algorithm Isolation Forest, ideal for detecting anomalies through the analysis of variables such as geographic distances and transaction times are analyzed to identify suspicious clusters, particularly clusters 1 and 4. This project used Power BI to present the findings and visualizations that allow us to identify potentially fraudulent transactions in a credit card dataset.

## Repository content
- **fraude_credicard.pbix:** Interactive Dashboard of Power BI.
- **fraud-detection-in-credit-card-transactions.ipynb:** Notebook with exploratory analysis, model development, and complementary visualizations (downloaded from Kaggle and adapted for this project).
- **README.md:** This document explains the project, findings, and how to replicate it.

## Origin of the data
The data used in this project was extracted from the Kaggle platform.   The dataset [Credit Card Fraud Detection](https://www.kaggle.com/datasets/iabhishekofficial/creditcard-fraud-detection) was used. It contains two credit card datasets: cc_info.csv and transactions.csv. I would like to thank the Kaggle community and the dataset creator for sharing this data.

## Project Description
The main objective is to identify patterns and anomalies in credit card transactions, focusing on:
- **Suspicious Clusters:** Clusters 1 and 4 stand out for their high proportion of anomalous transactions.
- **Key Variables:** The distance to the cardholder's city, transaction amounts, and temporal patterns are analyzed.
- **Main Findings:**
- Cluster 1 shows a difference of 1,777.52 km in the median distance to the city between normal and anomalous transactions.
- Cluster 3 shows the highest proportion of anomalous transactions (39.90%).
- Fraudulent activity is most common between midnight and 5:00 AM on weekends.

## Visualizations and Analysis
The Power BI dashboard includes:
- **KPIs and cards** that summarize total transactions and fraud rates.
- **Maps and scatter charts** to visualize the relationship between geographic distance and transaction amounts.
- **Bar charts** that show the distribution of anomalies by day of the week and hour.

The attached notebook details the analysis process, from data cleansing and transformation to the implementation of the Isolation Forest model and exploratory analysis, complementing the visualization in Power BI.

## How to Replicate the Project
1. **Download the Dataset:**
Download the original dataset from [Kaggle](https://www.kaggle.com/). You can find the link in the dataset project description.

2. **Open the Dashboard:**
Open the `fraude_credicard.pbix` file in Power BI Desktop to view and explore the interactive dashboard.

3. **Run the Notebook:**
Open the `fraud-detection-in-credit-card-transactions.ipynb` notebook in Jupyter Notebook, Jupyter Lab, or VS Code.
- Make sure you have the necessary libraries installed (pandas, numpy, scikit-learn, matplotlib, seaborn, etc.).
- Trace the cells in the notebook to replicate the analysis.

4. **Adapt and Customize:**
You can modify the analysis and visualizations to suit your needs or delve deeper into specific aspects of the model.

## Requirements
- [Power BI Desktop](https://powerbi.microsoft.com/) (free version)
-Python 3.x
- Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn, among others.
- Jupyter Notebook or Jupyter Lab

## Contributions
If you'd like to contribute or suggest improvements, please open an issue or submit a pull request.

## Author
Jennifer Silva
jenniferlsu20@gmail.com
www.linkedin.com/in/jennifer-silva-3aa1462a


