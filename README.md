# IrisFlowerClustering

This repository contains a machine learning project using ML.NET to perform clustering on the Iris flower dataset. The project aims to group iris flowers into different clusters based on their features—sepal length, sepal width, petal length, and petal width—without any prior knowledge of the flower types.

## Overview

Clustering is a method of unsupervised learning that helps in identifying patterns in data by grouping similar data points together. This project uses the Iris dataset, a standard dataset in the machine learning community, to demonstrate clustering with ML.NET.

## How It Works

1. **Data Loading**: The Iris dataset is loaded into ML.NET.
2. **Feature Processing**: The features (sepal length, sepal width, petal length, and petal width) are combined into a single feature vector.
3. **Model Training**: A K-Means clustering model is trained on the dataset.
4. **Model Saving**: The trained model is saved for future use.
5. **Prediction**: The model is used to predict the cluster of a new Iris data point.

## Getting Started

1. Clone this repository.
2. Add your Iris dataset in the `Data` folder.
3. Run the provided C# code to train the model and make predictions.

## License

This project is licensed under the MIT License.
