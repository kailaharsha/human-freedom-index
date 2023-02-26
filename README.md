# Predicting Human Freedom Index

The <a href="https://www.cato.org/human-freedom-index/2021 ">Human Freedom Index</a> measures economic freedoms such as the freedom to trade or to use sound money, and it captures the degree to which people are free to enjoy the major freedoms often referred to as civil liberties—freedom of speech, religion, association, and assembly— in the countries in the survey. In addition, it includes indicators on rule of law, crime and violence, freedom of movement, and legal discrimination against same-sex relationships. We also include nine variables pertaining to women-specific freedoms that are found in various categories of the index.

<u>Citation</u>
Ian Vásquez, Fred McMahon, Ryan Murphy, and Guillermina Sutter Schneider, The Human Freedom Index 2021: A Global Measurement of Personal, Civil, and Economic Freedom (Washington: Cato Institute and the Fraser Institute, 2021).

## Dataset
The dataset is a aggregated version of the one that exists on the <a href="https://www.cato.org/human-freedom-index/2021 ">Human Freedom Index</a> website. The dataset is **wide** with a shape of **2000*125** with **`hf_quartile`** being the target variable. 

## Objective 
The objective of this project is to predict the Human Freedom index. This is a Supervised learning task where we have a target variable associated with the data. Precisely, this is a multi-class classification task where the target variable has 4 classes. The target variable is **`hf_quartile`**, which refers to a measure of the Human Freedom Index. The classes are as follows : 
* 1 -> Highest Freedom
* 2 -> High Freedom
* 3 -> Moderate Freedom
* 4 -> Little Freedom

The objective is also to identify the factors that contribute the most to the Human Freedom index.


## Repository structure
This project is divided into 3 parts (contains a Jupyter notebooks for each part). 
* **PART-1** : Exploratory data analysis & building a simple scikit-learn pipeline.
* **PART-2** : Using GridSearchCV to perform hyperparameter optimization for Logistic Regression & Decision Tree models.
* **PART-3** : Deep Learning approach to the problem using Keras.

## Requirements
- Jupyter Notebook / Google colab
- Pandas
- scikit-learn
- keras
- warnings
- tqdm
- matplotlib
