# Prediction-using-unsupervised-ML
From the given dataset called 'Iris.csv', predict the optimum number of clusters and represent it visually.

-> Dataset is provided above i.e 'Iris.csv'
   > The goal is to achieve classification of three types of flowers which belongs to Iris family.
   > Three types of species are Iris setosa, Iris versicolor, Iris verginica
-> Solved using K-Means Clustering
-> Following are the steps to write code:
1) Importing the libraries
   > Import the libraries numpy, pandas, matplotlib
2) Importing the dataset
   > Import the dataset provided i.e 'Iris'
3) Using elbow method to find number of optimal clusters
   > A graph is plotted using elbow method to know the number of optimal clusters.
   > The point where the graph slope changes suddenly gives the number of optimal clusters.
4) Training the K-Means Model on given dataset
   > Now, train the model on modified dataset which do not contain id column and species column.
   > Because based sepal's width and length we will classify.
5) Visualising the clusters
