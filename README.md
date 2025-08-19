# K-Means Clustering for Customer Segmentation

## Description
This project applies the K-Means clustering algorithm for customer segmentation.  
The goal is to identify distinct groups of customers based on their **annual income**, **spending score**, and **age**.  

The methodology demonstrates how unsupervised machine learning can uncover patterns in unlabelled data.  
The analysis uses a publicly available dataset of mall customers.

---

## Project Structure and Files
- **K Means Clustering Project.ipynb**: Jupyter Notebook containing the Python code for data loading, preprocessing, clustering, and visualization.  
- **Mall_Customers.csv**: The dataset used for this project.  
- **README.md**: Project overview and documentation.  

---

## Methodology
1. **Exploratory Data Analysis (EDA)**  
   - Inspect feature distributions  
   - Check for missing values  
   - Identify potential outliers  

2. **Data Preprocessing**  
   - Standardize or scale features (*Annual Income, Spending Score, Age*)  
   - Ensure equal contribution to distance calculation in K-Means  

3. **Determining Optimal Number of Clusters (K)**  
   - Apply the **Elbow Method**  
   - Select the ideal number of clusters  

4. **K-Means Clustering**  
   - Apply the K-Means algorithm with the chosen `k`  
   - Assign cluster labels to each customer  

5. **Cluster Profiling and Visualization**  
   - Use violin plots and scatter plots for analysis  
   - Assign descriptive names to clusters, e.g. *High Spenders*, *Budget Shoppers*  

---

## Key Findings and Insights
- The analysis segmented customers into **five distinct clusters**.  
- Cluster 1: High spending scores and moderate-to-high income.  
- Cluster 2: Low income but high spending behavior.  
- The cluster profiles provide actionable insights for **targeted marketing strategies**.  
