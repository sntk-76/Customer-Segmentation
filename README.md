# Customer Segmentation Analysis

This repository contains a comprehensive analysis of customer segmentation using various clustering techniques. The goal of this project is to identify distinct customer segments based on their purchasing behavior and visualize the results.

## Table of Contents
- Introduction
- Dataset
- Data Preprocessing
- Exploratory Data Analysis
- Clustering
- Principal Component Analysis (PCA)
- Mean Shift Clustering
- Results
- Conclusion
- Dependencies
- Usage

## Introduction
Customer segmentation is a crucial task in marketing and business strategy. By identifying distinct customer segments, businesses can tailor their marketing efforts and improve customer satisfaction. In this project, we use various clustering techniques to segment customers based on their purchasing behavior.

## Dataset
The dataset used in this analysis is the "Online Retail" dataset, which contains transactional data for a UK-based online retail store. The dataset includes information such as invoice number, stock code, description, quantity, invoice date, unit price, customer ID, and country.

## Data Preprocessing
1. **Loading the Dataset**: The dataset is loaded from an Excel file using `pandas`.
2. **Cleaning the Data**: Missing values are removed, and the index is reset.
3. **Encoding Categorical Features**: Categorical features are encoded into numerical values using `LabelEncoder`.
4. **Normalizing the Data**: Features are scaled to a range of 1 to 5 using `MinMaxScaler`.

## Exploratory Data Analysis
1. **Histograms**: Histograms are created for all features to visualize their distributions.
2. **Pair Plots**: Pair plots are generated to visualize relationships between pairs of features.
3. **Correlation Heatmap**: A heatmap is created to visualize the correlation between features.

## Clustering
1. **K-Means Clustering**: K-Means clustering is performed for different values of K (2 to 11). The Elbow method is used to determine the optimal number of clusters.
2. **Evaluation Metrics**: Clustering performance is evaluated using Silhouette Score, Calinski-Harabasz Score, and Davies-Bouldin Score.
3. **Visualization**: Scatter plots are created to visualize the clusters and their centroids.

## Principal Component Analysis (PCA)
1. **Dimensionality Reduction**: PCA is performed to reduce the dimensionality of the data while retaining most of the variance.
2. **Explained Variance**: The explained variance for different numbers of principal components is evaluated.
3. **Visualization**: 2D and 3D scatter plots are created to visualize the PCA results.

## Mean Shift Clustering
1. **Sampling the Data**: A random sample of 5000 rows is taken from the normalized DataFrame.
2. **Estimating Bandwidth**: The bandwidth parameter for the Mean Shift algorithm is estimated.
3. **Clustering**: Mean Shift clustering is performed on the sampled data.
4. **Visualization**: Scatter plots are created to visualize the clusters and their centroids.

## Results
The analysis identified distinct customer segments based on their purchasing behavior. The optimal number of clusters was determined using the Elbow method and evaluation metrics. The clusters were visualized using scatter plots and PCA, providing valuable insights into the distribution of data points across different clusters.

## Conclusion
This project demonstrates the effectiveness of clustering techniques in customer segmentation. By identifying distinct customer segments, businesses can tailor their marketing efforts and improve customer satisfaction. The use of PCA and various evaluation metrics ensures that the clustering results are reliable and meaningful.


## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repository.git
   
2. Navigate to the repository directory:
   
   cd your-repository

3. Install the required dependencies:
   
pip install -r requirements.txt

4. Run the Jupyter notebook to perform the analysis and visualize the results.
Feel free to explore the code and modify it to suit your needs. If you have any questions or suggestions, please open an issue or submit a pull request.

Happy analyzing!
