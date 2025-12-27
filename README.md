🌌 Data Imputation & Clustering Analysis on Light Pollution Data | Scikit-Learn & Python

Implemented advanced data preprocessing, imputation, and unsupervised learning techniques on the Globe at Night light pollution dataset to address missing values and uncover latent patterns in sky quality observations. This project focuses on preparing incomplete real-world data for analysis and applying clustering methods to better understand underlying structures.

Missing SQM (Sky Quality Meter) values were imputed using K-Nearest Neighbors (KNN) imputation, improving data completeness while preserving spatial and contextual relationships. The engineered dataset was then transformed into a fully numeric feature space and clustered using K-Means, enabling pattern discovery across observational, environmental, and location-based features. Cluster characteristics were analyzed and visualized using aggregated summaries and heatmaps.

This project demonstrates practical experience with data imputation, feature engineering, unsupervised machine learning, and analytical visualization using Python. 

hw3

🛠 Tools & Technologies

Python

Pandas & NumPy

Scikit-Learn (KNNImputer, K-Means, NearestNeighbors)

Jupyter Notebook

Seaborn & Matplotlib

Folium (Geospatial Visualization)

🔍 Key Analytical Tasks

Imputed missing SQM values using K-Nearest Neighbors

Compared original vs. imputed measurements through statistical summaries

Visualized original and imputed SQM readings on interactive Folium maps

Converted categorical variables into binary features for clustering

Applied K-Means clustering to identify 12 distinct observation groups

Aggregated cluster-level feature contributions using groupby operations

Visualized cluster patterns using a heatmap for interpretability

📁 Data Outputs

gan_cluster_final.csv – clustering-ready dataset

gan_cluster_final_assigned.csv – dataset with cluster labels

gan_cluster_final_agg.csv – aggregated cluster feature summaries
