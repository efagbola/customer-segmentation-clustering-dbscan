# Customer Segmentation Using K-Means and DBSCAN

This project applies unsupervised machine learning techniques to segment mall customers based on income and spending behavior. The goal is to identify meaningful customer groups and compare centroid-based and density-based clustering methods.

## Dataset
The dataset contains customer information including age, annual income, and spending score. Customer IDs are removed and features are standardized before clustering.

## Methods
- Data exploration and preprocessing
- Feature scaling using StandardScaler
- K-Means clustering with Elbow Method and Silhouette Score
- DBSCAN clustering with k-distance graph for parameter selection
- Cluster visualization and summary statistics
- Outlier detection and analysis

## Key Findings
- K-Means produces more detailed and interpretable customer segments.
- DBSCAN identifies dense customer groups and detects outliers.
- High-spending customers exist across different income levels.
- Outliers represent unusual spending behavior and may require special business strategies.

## Tools
- Python
- pandas
- NumPy
- scikit-learn
- matplotlib
- seaborn
