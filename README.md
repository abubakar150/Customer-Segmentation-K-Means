# Customer-Segmentation-K-Means
Project Overview
This project applies unsupervised machine learning (clustering) to segment mall customers based on their demographic and purchasing behavior. By grouping similar customers together, businesses can identify valuable customer segments, design targeted marketing strategies, and improve decision-making.

Dataset

The dataset used is the Mall Customers Dataset, which contains the following features:

CustomerID – Unique identifier

Gender – Male/Female

Age – Age of customer

Annual Income (k$) – Annual income in thousands of dollars

Spending Score (1–100) – Score assigned based on spending behavior

Methodology

Data Preprocessing

Checked for missing values & duplicates.

Selected features: Age, Annual Income (k$), Spending Score (1–100).

Standardized features using StandardScaler.

Exploratory Data Analysis (EDA)

Visualized customer distributions (gender, age, income, spending).

Boxplots & pairplots to analyze patterns.

Clustering

Applied KMeans clustering.

Used the Elbow Method to determine optimal clusters (k=5).

Visualization

2D Scatterplots (Annual Income vs Spending Score).

3D Plots (Age, Income, Spending Score).

Cluster centroids highlighted.

Cluster Profiling

Described the behavior of each customer group.



Results & Insights

The model identified five distinct customer segments:

High Income – High Spending → Premium customers (most valuable).

High Income – Low Spending → Potential but less engaged.

Low Income – High Spending → Budget-conscious but loyal.

Low Income – Low Spending → Minimal contributors.

Average Income – Average Spending → Middle-class customers.

These insights help businesses in:

Targeted marketing campaigns.

Customer retention strategies.

Resource allocation for business growth.


Tech Stack

Python

Pandas, NumPy – Data handling

Matplotlib, Seaborn – Visualization

Scikit-learn – Machine Learning (KMeans, StandardScaler)

Future Improvements

Experiment with other clustering algorithms (DBSCAN, Hierarchical).

Use more features (purchase history, online activity).

Deploy as a web dashboard for interactive segmentation.

Sample Visualizations

(Insert scatterplots / elbow curve images here when you upload to GitHub)

 How to Run

Clone the repo:

git clone https://github.com/your-username/customer-segmentation.git
cd customer-segmentation


Install dependencies:

pip install -r requirements.txt


Run the script:

python mall_customer.py
