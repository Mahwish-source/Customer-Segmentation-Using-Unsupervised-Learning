Customer Segmentation Using Unsupervised Learning (K-Means)
📌 Project Overview

Customer behavior varies significantly based on income and spending habits. Treating all customers identically leads to ineffective marketing strategies. This project applies unsupervised machine learning (K-Means clustering) to segment customers into meaningful groups and proposes data-driven marketing strategies for each segment.

🎯 Objective

Segment customers based on Annual Income and Spending Score

Identify natural customer groups using K-Means Clustering

Visualize clusters using PCA and t-SNE

Recommend targeted marketing strategies for each customer segment

📂 Dataset Description

Dataset Name: Mall Customers Dataset

Source: Public online dataset (GitHub – raw CSV)

Total Records: 200

Features:
Feature	Description
CustomerID	Unique customer identifier
Gender	Male / Female
Age	Customer age
Annual Income (k$)	Annual income in thousand dollars
Spending Score (1–100)	Customer spending behavior score
🛠️ Technologies & Libraries Used

Python

Pandas – Data manipulation

NumPy – Numerical computations

Matplotlib & Seaborn – Data visualization

Scikit-learn – Machine learning models

🔄 Project Workflow
1️⃣ Data Loading

Dataset loaded directly from an online CSV URL using Pandas

2️⃣ Data Cleaning & Preprocessing

Checked for missing values (none found)

Selected relevant numerical features

Applied StandardScaler for normalization

3️⃣ Exploratory Data Analysis (EDA)

Analyzed distributions of age, income, and spending score

Visualized relationships using histograms and scatter plots

4️⃣ Model Building

Applied K-Means Clustering

Used the Elbow Method to determine the optimal number of clusters

Selected 5 clusters for segmentation

5️⃣ Dimensionality Reduction

Used PCA for 2D cluster visualization

Used t-SNE for enhanced cluster separation

6️⃣ Cluster Analysis

Analyzed average income, age, and spending score per cluster

Interpreted customer behavior patterns

📊 Visualizations Included

Age, income, and spending score distributions

Income vs spending scatter plots

Cluster visualizations with centroids

PCA and t-SNE cluster projections

📈 Marketing Strategy Recommendations
Customer Segment	Characteristics	Strategy
Low income – Low spending	Price-sensitive	Discounts, loyalty programs
Medium income – High spending	Active buyers	Upselling & premium offers
High income – High spending	VIP customers	Personalized deals & exclusives
High income – Low spending	Potential growth	Incentives & targeted campaigns
Medium income – Medium spending	Balanced	Bundled offers & promotions
✅ Key Insights

Spending behavior does not always correlate with income

Customer segmentation enables personalized marketing

K-Means is effective for uncovering hidden patterns in customer data

Visualizations greatly improve interpretability of clusters

📌 Conclusion

This project demonstrates how unsupervised learning can be used to identify customer segments and transform raw data into actionable business insights. The approach helps organizations move from generic marketing to data-driven decision making
