# Customer Segmentation using RFM Analysis and K-Means Clustering

In today's competitive retail landscape, understanding customer preferences is essential for scaling up business strategies. If you're managing a store, you might face the challenge of tailoring unique strategies for each customer. Instead of evaluating each customer individually, leveraging data analysis techniques like RFM analysis and K-Means clustering can help segment customers effectively. In this project, we apply these techniques to gain actionable insights into customer behavior.

## 📋 Table of Contents

1. [Project Overview](#project-overview)
2. [Flow of the Project](#flow-of-the-project)
3. [Dataset Overview](#dataset-overview)
4. [Integrating with Amazon S3 and Databricks](#integrating-with-amazon-s3-and-databricks)
5. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
6. [Understanding RFM Analysis](#understanding-rfm-analysis)
7. [Customer Segmentation with K-Means Clustering](#customer-segmentation-with-k-means-clustering)
8. [Overall Analysis and Insights](#overall-analysis-and-insights)
9. [Conclusion](#conclusion)
10. [Contact](#contact)

## 🌟 Project Overview

As the head of a retail store, understanding customer preferences to develop tailored strategies is critical. Instead of assessing each customer individually, this project utilizes RFM (Recency, Frequency, Monetary) analysis and K-Means clustering to segment customers based on their purchasing behavior. By clustering customers into distinct groups, we can devise targeted strategies for each segment, enhancing overall business effectiveness.

## 🎗️ Flow of the Project

1. **Data Collection and Preparation:** Gather and clean data for analysis.
2. **Exploratory Data Analysis (EDA):** Analyze data to identify patterns and insights.
3. **RFM Analysis:** Compute Recency, Frequency, and Monetary scores to evaluate customer behavior.
4. **K-Means Clustering:** Segment customers based on their RFM scores.
5. **Analysis and Interpretation:** Draw conclusions from the results to refine business strategies.
6. **Implementation:** Apply insights to improve marketing and operational strategies.

## Dataset Overview

We began with a dataset containing 500,000 rows of customer transaction data. To tackle this as a big data problem, we augmented and bootstrapped the data, increasing it to 10 million rows. This allowed us to apply advanced clustering techniques effectively.

## Integration with Amazon S3 and Databricks ☁️

- **S3 Bucket:** We stored and managed our large datasets using Amazon S3, ensuring scalable storage and easy accessibility.
- **Databricks:** Utilized Databricks for distributed computing and advanced data processing. This platform enabled efficient handling of our augmented dataset and facilitated complex analytics tasks.

## Exploratory Data Analysis (EDA) 🔍

### Steps Taken:
1. **Data Cleaning:** Addressed missing values, corrected data types, and removed duplicates to ensure data integrity.
2. **Data Transformation:** Normalized data features and created new variables to enrich the dataset.
3. **Visualization:** Generated visualizations to uncover patterns, trends, and anomalies in customer behavior.

### EDA Findings:
- **Customer Purchase Patterns:** Identified frequent purchase patterns and seasonal trends.
- **Anomalies:** Detected outliers and anomalies affecting customer insights.
- **Data Distribution:** Analyzed the distribution of various metrics to better understand customer segments.

## RFM Analysis 📈

### What is RFM?
RFM (Recency, Frequency, Monetary) analysis helps in categorizing customers based on their purchase history:
- **Recency:** How recently a customer made a purchase.
- **Frequency:** How often a customer makes a purchase.
- **Monetary:** How much money a customer spends.

### Steps to Calculate RFM:
1. **Recency Calculation:** Compute the number of days since the last purchase for each customer.
2. **Frequency Calculation:** Determine the total number of purchases for each customer.
3. **Monetary Calculation:** Calculate the total expenditure for each customer.

### Using RFM for Prediction:
By analyzing RFM scores, we can predict customer loyalty and identify which customers are likely to be high-value. This insight allows us to tailor marketing efforts and retention strategies.

## K-Means Clustering 🤖

### What is K-Means Clustering?
K-Means is a clustering algorithm that partitions data into `k` distinct clusters based on feature similarity.

### Steps Taken:
1. **Choosing K:** Utilized methods like the Elbow Method to determine the optimal number of clusters.
2. **Clustering:** Applied K-Means to segment customers based on their RFM scores.
3. **Analyzing Clusters:** Interpreted cluster characteristics to define customer loyalty and behavior patterns.

### Defining Customer Loyalty:
Clusters help us categorize customers into various loyalty tiers, allowing for targeted marketing strategies.

## Overall Analysis 🧠

### Key Findings:
- **Customer Segmentation:** Identified distinct customer segments with specific behaviors and spending patterns.
- **Strategic Insights:** Provided actionable insights for targeted marketing and personalized customer engagement.

### Solution to Problem Statement:
By clustering customers and analyzing their purchasing behaviors, we devised tailored strategies for different customer segments, enhancing business growth and customer satisfaction.

## 🔍 Conclusion

Customer segmentation is a powerful technique that allows businesses to gain a deeper understanding of their customers and create tailored marketing strategies that cater to each customer group's specific needs. By using big data technologies such as Spark and Amazon EMR, businesses can analyze large volumes of data from various sources and identify their most valuable customers using RFM analysis. Power BI provides a powerful data visualization tool that helps businesses gain insights into customer behavior and preferences and make data-driven decisions.

## 📧 Contact

For any questions or inquiries, don't hesitate to reach out to me on LinkedIn and Github.

- **LinkedIn:** [Shruti Bharat](https://www.linkedin.com/in/shrutibharat)
- **GitHub:** [shrutibharat01](https://github.com/shrutibharat01)
