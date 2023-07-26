# Credit Card Customer Segmentation
This project aims to built a *clustering model* on credit card customers and evaluate the *behavior (characteristics)* of each *cluster* with ultimate goal meet *customer* needs for targeted *clusters*

# File Explanation on Github
This repository consists of several files, namely :
- **dataset_Credit_Card_Customer_Segmentation.csv** = Datasets used in the project
- **Notebook_Credit_Card_Customer_Segmentation.ipynb** = This file is the main notebook used to explore dataset, create model and analyze clusters
- **model_inference_Credit_Card_Customer_Segmentation.ipynb** = Notebook used for testing inference. Inferencing is done on a separate notebook to prove that the model can run on a notebook that is clean of variables.
- **inference_Credit_Card_Customer_Segmentation.csv** = Dataset inference used for model inference
- **pca.pkl** = PCA model have been trained on a dataset, and the serialized object allows you to load the pre-trained model later and apply the same transformation to new data without re-computing the PCA components.
- **kmeans.pkl** = K-Means model have been trained on a dataset, and the serialized object allows you to load the pre-trained model later and use it to predict the cluster assignments of new data points without having to retrain the K-Means algorithm.
- **s_MinMaxScaler.pkl** = The serialized MinMaxScaler object can be used to apply the same scaling scheme to new data without needing to retrain the encoder.

# Brief Summary of this project
The flow of this project, first EDA (Exploratory Data Analysis) to find out the basic picture of the dataset. Then cleaning and preprocessing of the dataset. Second, I performed PCA to reduce the dimensionality of the data and reduce the possibility of overfit. Third, I performed clustering using K-Means Nearest Neighbor. Result of clustering, there are 3 customer clusters with specific characteristics

# Project Conclusion
- **Cluster 0** is for credit card holders who frequently make purchases
- **Cluster 1** is for credit card holders who don't use their credit cards very frequently to make purchases
- **Cluster 2** is for credit card holders who frequently use Cash in advance payment method when making purchases
