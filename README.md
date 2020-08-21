# SVM Iris Dataset Classification

<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
* [Libraries used](#libraries-used)
* [Dataset used](#dataset-used)
* [Built on](#built-on)
* [Questions answered](#questions-answered)
* [Model Training and Testing Steps](#model-training-and-testing-steps)
* [Ackowledgements](#ackowledgements)
* [Author](#author)


## About the Project 
EDA and model building to classify the three species of flowers in the Iris flower dataset using Support Vector Machines</br></br>
The python notebook __"02-Support Vector Machine Project"__ contains an initial EDA of data from the Iris Dataset in addition to the model building process to classify the flowers species. 
We use an SVM model in order to make this classification taking 'species' as our target variable.

## Libraries used 
* Numpy
* Pandas
* Matplotlib
* Seaborn
* sklearn
* pickle

```bash
import numpy as np
import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt
%matplotlib inline
from sklearn.model_selection import train_test_split
from sklearn.svm import SVC
from sklearn.metrics import classification_report,confusion_matrix
from sklearn.model_selection import GridSearchCV
import pickle
```

## Dataset used 
* __Iris Flower Dataset__

## Built with
* Jupyter Notebook

## Questions answered 
1. How do our independent variables correlate to each other?
2. What is the distribution and correlation between sepal length and width?
3. How does the petal length and width vary with different species?

## Model Training and Testing Steps
1. Training the Base Model
2. Base Model Prediction and Evaluation
3. Parameter Tuning using Gridsearch
4. GridSearchCV Model Prediction and Evaluation

## Ackowledgements
* <a href='http://en.wikipedia.org/wiki/Iris_flower_data_set'>Iris Flower Dataset</a> - Dataset

## Author - Sharan Sukesh




