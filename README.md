# UCI_heart_dataset_analysis
Analysis of the UCI heart dataset using Machine Learning and statistical techniques. 
Dataset url http://archive.ics.uci.edu/ml/datasets/statlog+(heart)

File :

Silhouette_clustering.ipynb: 
  1. Preprocess data from the files 
     - Drop any nan and missing values
  2. Do clustering according to kmeans and Gaussian Mixture Models. 
  3. Calculate the Silhouette scores for the clustering for each method and compare for n componets.  
  
 
Silhouette.py:
 Code for Silhouette scores from sklearn machine learning.
 
Imputation_comparison_heart : focuses on the comparison of different imputation methods and the explains the rational of doing so. Result also included in file.

Visualize+imports : functionality for plotting.

Kmeans : K means clustering of samples based on different sets of features and iteratively checking the best k. 

heart_impute : first trial of imputation process
