# EDA
# Readme
This repository contains a Python code for performing Principal Component Analysis (PCA) on a dataset, visualizing the data separation after the transformation, and calculating the accuracy of the classification using the nearest centroid method.

##Libraries Used
numpy
pandas
matplotlib
seaborn
sklearn.decomposition.PCA
mpl_toolkits.mplot3d
scipy.spatial.distance
Dataset
The dataset used in this code is "TP1_data.csv". The file is read using pandas library and the index column is set to 0. The "classe" column is dropped as it is not needed for PCA.

##Data Visualization
Two data visualization methods are used in this code:

### Pairplot: This method is used to visualize the pairwise relationships between the features in the dataset. This is implemented using seaborn library.
Heatmap: This method is used to visualize the correlation between the features in the dataset. This is implemented using seaborn library.
Principal Component Analysis (PCA)
PCA is used to reduce the dimensionality of the dataset and visualize the separation between the classes after transformation. Two methods of visualization are used: scatter plot (with 2 and 3 principal components) and nearest centroid method.

### Scatter Plot
Two scatter plots are generated with 2 and 3 principal components respectively, to visualize the separation between the classes after transformation. This is implemented using PCA and matplotlib library.

## Nearest Centroid Method
The nearest centroid method is used to classify each object to its nearest centroid by Euclidean distance. The accuracy of the classification is calculated and printed to the console.

#Conclusion
This code provides an example of how to use PCA to reduce the dimensionality of a dataset and visualize the data separation after transformation. It also shows how to use the nearest centroid method to classify the objects.
