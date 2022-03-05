[toc]

## Project Overview

- In this project, we want to find out which machine learning regression model provides the most accuracy based on the given dataset.
- Based on the results, MLP NN (Multi-Layer Perceptron Neural Network) gives the best accuracy and a short training-time due to the structure of the model.
- The regression models that are used in this project include: Elastic Net, Lasso (L1), Multi-Layer Perceptron Neural Network(MLPNN), Ridge (L2), Support Vector Regression (SVR)
- [Link to this Project on Github](https://github.com/ewang58/Machine-Learning-Fibre-Classification-Regression)

## Description

- In this project, a set of training data (~80%) set and testing data set(~20%) are given. Each data contains a 2-dimension label which denotes the cotton content and the polyester content in the fabric respectively. 
- We will build and train 5 different regression models to see which models gives the best performance in terms of prediction error and efficiency.
- We will use mean absolute error (MAE) as our benchmark to compare each model.

## Python Libraries

I have Anaconda Python distribution installed on my system which comes with most of the standard Python libraries that I need for this project. Some libraries used in this project are:

- Pandas: it provides necessary tools for data manipulation, storage and analysis tasks.
- Numpy: it provides a simple numerical array structure and functions
- Seaborn: it provides the necessary plotting functions for Pandas data frames.
- Matplotlib: it is the basic plotting tools in Python for data presentation.
- Scikit-learn: it provides simple data preprocessing tools.
- Pytorch: it provides fast and flexible tools for training and testing the given datasets.



## MAE

The mean absolute error (MAE) is "a measure of errors between paired observations expressing the same phenomenon" which can be calculated as:
$$
MAE = \frac {\sum^n_{i=1}|y_i-x_i|}{n}=\frac{\sum^n_{i=1}|e_i|}{n}
$$
In python, we can write a function as such:

````python
class Metrics:
    def mae(y_pred, y_true):
        return np.mean( np.abs( np.subtract(y_pred, y_true) ) )
````



## Exploratory data analysis



## Step 3



## Interpreting the Results

- 
- a
- a
- You can access the source code [here](https://github.com/ewang58/Machine-Learning-Fibre-Classification-Regression/tree/main/Code)



[Back to Main](https://ewang58.github.io/My-Portfolio-by-Edward-Wang/)
