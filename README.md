📌 Customer Segmentation using RFM & K-Means
🚀 Overview
Understanding customer behavior is essential for improving retention, increasing revenue, and delivering personalized experiences.
In this project, I built a customer segmentation system using unsupervised learning to group customers based on their purchasing behavior. The solution transforms raw transaction data into meaningful insights using RFM analysis and K-Means clustering.
🧠 Problem Statement
Many businesses treat all customers the same, leading to:
Ineffective marketing strategies
Poor customer retention
Missed revenue opportunities
This project aims to uncover distinct customer segments to enable data-driven decision-making.
🔍 Approach
1. Data Cleaning
Removed irrelevant features (e.g., Customer Name, Churn)
Handled missing values in the Returns column using business logic (filled with 0)
2. Feature Engineering (RFM)
Converted transaction-level data into customer-level features:
Recency (R): Days since last purchase
Frequency (F): Number of purchases
Monetary (M): Total spending
3. Handling Skewness
Identified right-skewed distributions in RFM features
Applied log transformation to reduce skewness and improve clustering performance
4. Feature Scaling
Used StandardScaler to normalize feature magnitudes
Ensured fair distance-based clustering
5. Clustering (K-Means)
Applied K-Means clustering
Used the Elbow Method to determine optimal clusters
Selected K = 4
6. Cluster Interpretation
Customers were segmented into:
🌟 High-Value Active Customers
💰 Loyal but At-Risk Customers
⚖️ Moderate Customers
⚠️ Low-Value / At-Risk Customers
7. Visualization
Applied PCA to reduce dimensionality
Visualized customer segments in 2D space
📊 Key Insights
A small group of customers contributes significantly to overall revenue
Some high-value customers show declining activity, indicating churn risk
Moderate customers present strong opportunities for growth
Low-value customers exhibit minimal engagement
💡 Business Recommendations
This segmentation enables targeted strategies:
🌟 High-Value Active Customers:
Retain through loyalty programs, rewards, and exclusive offers
💰 Loyal but At-Risk Customers:
Re-engage using personalized campaigns and incentives
⚖️ Moderate Customers:
Upsell and nurture to increase engagement and spending
⚠️ Low-Value Customers:
Target selectively or deprioritize based on business goals
🛠️ Tech Stack
Python
Pandas
NumPy
Scikit-learn
Matplotlib
📽️ Demo
A short video walkthrough of the full pipeline (data → RFM → clustering → insights) is included.
🚀 Future Improvements
Incorporate additional features (e.g., product category, demographics)
Compare with other clustering techniques (DBSCAN, Hierarchical Clustering)
Deploy as an interactive segmentation tool
📂 Project Structure
├── data/ ├── customer_segmentation.ipynb ├── README.md ├── requirements.txt 
🧠 Key Takeaway
This project demonstrates how unsupervised learning can transform raw transactional data into actionable customer insights, enabling smarter business decisions and targeted engagement strategies.
