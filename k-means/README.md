# K-Means Clustering
A simple K-Means Clustering project to group iris flowers based on their sepal and petal measurements

## Dataset used
This project uses the Iris dataset that contains 150 samples of iris flowers, with measurements such as sepal length, sepal width, petal length, and petal width

The species label (Iris-setosa, Iris-versicolor, Iris-virginica) is not used for training because K-Means is an unsupervised algorithm. It is only used afterwards to check how well the clusters match the real species

## What I Did
- Exploratory data analysis (correlation heatmap and pairplot)
- Data preprocessing (dropping the Id column and feature scaling with StandardScaler)
- K-Means Clustering
- Finding the best number of clusters (Elbow Method and Silhouette Score)
