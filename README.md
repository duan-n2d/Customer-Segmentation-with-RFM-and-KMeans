# RFM K-means Customer Segmentation
This Jupyter notebook provides a Python implementation for customer segmentation using RFM (Recency, Frequency, Monetary) analysis combined with K-means clustering. The purpose is to group customers based on their purchasing behavior to identify valuable segments for targeted marketing strategies.

## Models
<p align="center">
  <img src="Picture1.png" title="hover text">
</p>

## Installation
The notebook utilizes various Python libraries. Ensure you have them installed, especially if you plan to run the code locally. The required libraries include:
```
Pandas
NumPy
Matplotlib
Seaborn
Plotly
DateTime
Category Encoders
Scikit-learn
Imbalanced-learn (imblearn)
SciPy
```
## File Structure
- `RFM_Kmean_for_Customer_Segmentation.ipynb`: The main Jupyter notebook containing the code.
- `AdventureWorksSales.xlsx`: Dataset containing sales, customer, product, and territory information.

## Importing Libraries and Functions
The notebook starts by importing necessary libraries and functions for data processing, visualization, and modeling. The libraries include Pandas, NumPy, Matplotlib, Seaborn, Plotly, DateTime, Category Encoders, Scikit-learn, and others.

## Pre-processing the Data
The dataset is loaded from the 'AdventureWorksSales.xlsx' file, containing sales order, territory, product, and customer information. Data pre-processing steps include handling missing values, transforming data, and performing exploratory data analysis (EDA).

## Exploratory Data Analysis (EDA)
EDA is conducted to understand the distribution of variables, detect outliers, and identify patterns in the data. Visualizations such as histograms, box plots, pair plots, and correlation matrices are utilized for analysis.

## RFM Segmentation
RFM (Recency, Frequency, Monetary) analysis is performed to segment customers based on their purchasing behavior. Customers are assigned RFM scores and segmented into groups accordingly.

## K-means Clustering
K-means clustering is applied to the RFM data to further segment customers into distinct groups based on similarities in their RFM scores. The optimal number of clusters is determined using techniques like the elbow method and silhouette analysis.

## Results and Visualization
The results of the segmentation are visualized using scatter plots, snake plots, and cluster summaries. Each cluster's characteristics and key insights are analyzed to derive actionable marketing strategies.

## Conclusion
The notebook concludes with insights derived from the customer segmentation analysis and recommendations for marketing strategies targeting different customer segments.
