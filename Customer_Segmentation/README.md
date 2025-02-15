# Customer Segmentation Using Machine Learning

## 📌 Project Overview
This project focuses on customer segmentation using unsupervised machine learning techniques. By analyzing customer purchasing behavior and demographic data, we categorize customers into distinct groups to help businesses understand their target audiences and improve marketing strategies.

## 📂 Table of Contents
- [Dataset](#dataset)
- [Methodology](#methodology)
- [Clustering Models Used](#clustering-models-used)
- [Evaluation Metrics](#evaluation-metrics)
- [Results](#results)
- [How to Run the Notebook](#how-to-run-the-notebook)
- [Requirements](#requirements)
- [Conclusion](#conclusion)

## 📊 Dataset
The dataset consists of customer attributes such as:
- **Demographics:** Age, Gender, Income, Location
- **Spending Behavior:** Annual Spending, Purchase Frequency, Transaction Amounts
- **Customer Loyalty:** Number of years as a customer, retention rates

### Data Preprocessing
- Handling missing values
- Encoding categorical variables
- Feature scaling
- Dimensionality reduction (if necessary)

## 🔍 Methodology
1. **Exploratory Data Analysis (EDA):** Identifying patterns and relationships in the data.
2. **Feature Engineering:** Selecting key variables for clustering.
3. **Clustering Models:** Applying various unsupervised learning techniques.
4. **Model Evaluation:** Determining the optimal number of clusters and assessing segmentation quality.

## 🤖 Clustering Models Used
- **K-Means Clustering**
- **Hierarchical Clustering**

## 📈 Evaluation Metrics
- **Elbow Method & Silhouette Score (for K-Means Optimization)**
- **Dendrogram Analysis (for Hierarchical Clustering)**
- **Cluster Visualization using PCA & t-SNE**

## 🚀 Results
- Customers were successfully segmented into distinct groups based on their spending patterns and demographics.
- K-Means provided well-defined clusters, while DBSCAN helped identify outliers.
- Cluster visualization revealed insights into customer behavior and potential business strategies.

## 🛠️ How to Run the Notebook
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/classical-ml-projects.git
   cd classical-ml-projects/customer_segmentation
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Customer_Segmentation.ipynb
   ```
4. Run all cells to execute the segmentation analysis.

## ⚙️ Requirements
Ensure you have the following Python libraries installed:
```bash
pandas  
numpy  
matplotlib  
seaborn  
scikit-learn  
scipy  
```

## 📌 Conclusion
This project successfully segments customers into meaningful groups, providing valuable insights for targeted marketing and customer relationship management. Future improvements may include deep learning approaches for more dynamic segmentation.

💡 *Potential next steps: incorporating real-time customer behavior tracking for adaptive segmentation!*

