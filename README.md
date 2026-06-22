# Developers-Hub-Internship-Phase-2-Task2Objective
Perform Exploratory Data Analysis (EDA) on customer data
Apply K-Means clustering to segment customers
Use PCA to visualize clusters in 2D space
Recommend marketing strategies for each customer segment Dataset

Mall Customers Dataset

Features include:

CustomerID
Gender
Age
Annual Income (k$)
Spending Score (1–100)
 Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Workflow
1. Exploratory Data Analysis (EDA)
Checked missing values and duplicates
Studied distributions of Age, Income, and Spending Score
Visualized relationships between variables
2. K-Means Clustering
Selected key features: Annual Income & Spending Score
Applied StandardScaler for normalization
Used Elbow Method to determine optimal clusters
Fitted K-Means model and assigned cluster labels
3. Dimensionality Reduction (PCA)
Reduced data to 2 components
Visualized clusters in 2D space
4. Cluster Analysis
Analyzed average characteristics of each cluster
Derived insights for business understanding
5. Marketing Strategy
Designed targeted strategies for each customer segment
High income–high spending → VIP offers
Low income–high spending → Budget-friendly deals
High income–low spending → Premium targeting
Low income–low spending → Discounts & promotions
Results
Successfully segmented customers into meaningful groups
Clear visualization of clusters using PCA
Actionable marketing insights generated for each segment
 How to Run
Download the dataset (Mall_Customers.csv)
Open Jupyter Notebook or VS Code
Run the notebook step by step
Install required libraries if needed:
pip install pandas numpy matplotlib seaborn scikit-learn
📌 Conclusion

K-Means clustering effectively groups customers based on spending behavior, allowing businesses to understand different customer types and design more effective, personalized marketing strategies.
