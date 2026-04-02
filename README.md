📌 Customer Segmentation using RFM & K-Means
🚀 Project Overview
Understanding customer behavior is critical for businesses to improve retention, increase revenue, and personalize marketing strategies.
In this project, I built a customer segmentation system using unsupervised learning to group customers based on their purchasing behavior.
The system transforms raw transaction data into meaningful customer insights using RFM analysis and K-Means clustering.
🧠 Problem Statement
Businesses often treat all customers the same, leading to:
Ineffective marketing strategies
Poor customer retention
Missed revenue opportunities
This project aims to identify distinct customer segments to enable data-driven decision-making.
🔍 Approach
1. Data Preprocessing
Removed irrelevant features (e.g., Customer Name, Churn)
Handled missing values in the Returns column using business logic
2. Feature Engineering (RFM)
Transaction-level data was transformed into customer-level features:
Recency (R): Days since last purchase
Frequency (F): Number of purchases
Monetary (M): Total spending
3. Handling Skewness
Identified right-skewed distributions in RFM features
Applied log transformation to normalize data
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
Applied PCA to reduce dimensions
Visualized clusters in 2D space
📊 Key Insights
A small group of customers contributes significantly to revenue
Some high-value customers show signs of inactivity
Clear behavioral differences exist across customer segments
💡 Business Impact
This segmentation can help businesses:
Personalize marketing campaigns
Improve customer retention strategies
Target high-value customers effectively
Optimize revenue generation
🛠️ Tech Stack
Python
Pandas
NumPy
Scikit-learn
Matplotlib
📽️ Project Demo
A walkthrough video demonstrating the full pipeline is included.
🚀 Future Improvements
Incorporate additional features (e.g., product category, demographics)
Compare with other clustering algorithms (e.g., DBSCAN, Hierarchical)
Deploy as an interactive segmentation tool
📂 Repository Structure

├── data/
├── notebook.ipynb
├── README.md
├── requirements.txt
🧠 Key Takeaway
This project demonstrates how unsupervised learning can transform raw transaction data into actionable business insights, enabling smarter and more effective decision-making.
