# Autism Predictor

Autism Spectrum Disorder affects communication and behavior. Early prediction can help in timely intervention. This is a  machine learning model designed to predict the likelihood of Autism Spectrum Disorder (ASD) based on user input features. 




![Image Link](C:\Users\shuch\Desktop\AutismPredictor\autism-7.jpg)


___

# Development Workflow




## 1. Exploratory Data Analysis


- Analyzed distribution of features like age, gender, ethnicity, etc.

- Checked for class imbalance in the target variable.

- Visualized correlations between different features.


## 2. Feature Engineering

- Normal Transformation 

 Transformed the distribution of features into normal distribution using sklearn PowerTransformer & FunctionTransformer.

- Feature Construction

Modified the existing feature

- One Hot Encoding 

Converted categorical variable into numerical format.

- Feature Extraction

Principal component analysis or PCA,  a dimensionality reduction method  is used to reduce the dimensionality of large data sets.

- Feature Scaling

Standardized or normalized numerical features which transforms features to a comman scale. Hence,improving model performance.



## 3. Model Training

Different Machine Learning algorithims are trained on data -

1. Logistic Regression

2. Decision Tree Classifier

3. RandomForest Classifier

4. AdaBoost Classifier

5. KNeighbors Classifier

6. Support Vector Machine

7. Gaussian/Bernoulli Naive Bayes

8. XGBoost


## 4. Hyperparameter Tuning

- Used GridSearchCV and RandomizedSearchCV to tune different parameters.

## 5. Evaluation

- Used different classification metrics like- Accuracy, Precision, Recall & F1-Score to evaluate the performance of ML Model.

- Visualized confusion matrix and ROC curve.

Compared results of different models and Logistic Regression & SVM performs better with an accuracy of 88.75%

