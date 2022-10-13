# Wine Quality Classification
This project makes use of Python's Tensorflow library to classify whether a wine is of good or bad quality.

## About the Dataset
Source: https://archive.ics.uci.edu/ml/datasets/wine+Quality
The two datasets are related to red and white variants of the Portuguese "Vinho Verde" wine.

## Attribute Information
Input variables (based on physicochemical tests):
1 - fixed acidity
2 - volatile acidity
3 - citric acid
4 - residual sugar
5 - chlorides
6 - free sulfur dioxide
7 - total sulfur dioxide
8 - density
9 - pH
10 - sulphates
11 - alcohol
Output variable (based on sensory data):
12 - quality (score between 0 and 10)

## Steps in the project
1. Data pre-processing
  * Removing null values
  * Converting the target column's string values to numerical
  * Converting the 'quality' columns values to binary
  * Normalizing the following columns: fixed acidity, volatile acidity, citric acid, residual sugar, chlorides, free sulfur dioxide, total sulfur dioxide, density, pH, sulphates, alcohol
2. Building the model
3. Evaluating the model

## Correlation Matrix
According to the heatmap, most correlation can be found with alcohol, density, chlorides and volatile density
![image](https://user-images.githubusercontent.com/89472841/195724405-f0e2171d-6897-4a6d-8d6e-a93742ebbe5d.png)

## Libraries Used
* random
* matplotlib
* numpy
* pandas
* seaborn
* tensorflow 
* sklearn
