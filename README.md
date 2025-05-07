🧠 **Customer Segmentation using K-Means Clustering**


🔍 **Project Overview**

This project demonstrates a practical application of unsupervised machine learning to perform customer segmentation using K-Means Clustering.
By analyzing key customer attributes, the goal is to identify distinct customer groups to help businesses optimize marketing strategies, personalize customer experience, and boost revenue.

📁 **About the Dataset**

Source: Kaggle (Mall Customer Segmentation Data)

Records: 200

Attributes: 5

Features:

CustomerID: Unique identifier for each customer

Gender: Male or Female

Age: Customer's age in years

Annual Income (k$): Income in thousands of dollars

Spending Score (1–100): Score assigned by the mall based on customer behavior and spending nature.


🧰 **Tools & Technologies**

Language: Python

Libraries: NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn

Algorithm: K-Means Clustering

IDE: Jupyter Notebook (converted to HTML)

📊 **Key Steps in the Project**


1. **Data Preprocessing**

Checked for null values and data types

Exploratory Data Analysis (EDA) using histograms

Feature selection for clustering


3. **Elbow Method & Optimal Clusters**

Used the Elbow Method to determine the optimal number of clusters (k=5)

Evaluated inertia scores to visualize the “elbow” point


3. **Model Training**

Applied KMeans from scikit-learn

Clustered customers into 5 distinct segments


4. **Visualization**
   
2D scatter plots of clusters

Used color coding for better interpretability

Plotted centroids and labeled clusters


5. **Interpretation**

Labeled clusters based on age, income, and spending score

Derived actionable insights from each segment



💡 **Key Insights**

Cluster 0: Young high spenders with average income – a valuable group for premium marketing

Cluster 1: Mid-aged customers with moderate spending – potential for loyalty programs

Cluster 2: Older low spenders – cost-conscious customers, not ideal for high-end products

Cluster 3: Young low spenders – opportunity for conversion via targeted offers

Cluster 4: High-income high spenders – ideal for luxury/premium product targeting


🎯 **Conclusion**

The segmentation model successfully identifies customer groups that a business can use to:

Tailor personalized marketing campaigns

Improve customer engagement and retention

Increase conversion rates and profitability



**This project underscores the importance of data-driven decision-making and highlights my ability to leverage unsupervised learning for real-world business solutions.**
