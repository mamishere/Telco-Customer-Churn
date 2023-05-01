# Customer Churn Complete Analysis and Prediction

![Kaggle](https://img.shields.io/badge/Dataset-Kaggle-blue.svg) 
![Python](https://img.shields.io/badge/Python-3.9-blue)
![Notebook](https://img.shields.io/badge/Notebook-Jupyter-orange)

Customer churn is a crucial problem for businesses, as it impacts revenue and growth.
Customer churn refers to the phenomenon of customers leaving a company, and it is an important metric for businesses to measure customer satisfaction and loyalty.
Predicting customer churn accurately can help businesses take proactive measures to retain customers and improve their satisfaction.

In this notebook, we will explore customer churn data and perform a detailed analysis of the variables that are most correlated with customer churn.
We will then build predictive models to identify customers who are at risk of churning.
We will use several machine learning algorithms, including logistic regression, decision trees, random forests, and gradient boosting, and evaluate their performance using various metrics such as accuracy, precision, recall, and F1 score.

Our analysis will help businesses to gain a better understanding of their customers and to develop targeted strategies for customer retention.
By identifying the variables that are most predictive of customer churn, businesses can take proactive measures to address these issues and improve customer satisfaction. Additionally, our predictive models can help businesses to prioritize their resources and take appropriate actions to retain customers who are at the highest risk of churning.

## Steps

1. [First Organization](#step1)
2. [Second Step: Data Preprocessing](#step2)
3. [Third and Final Step: Modeling](#step3)
4. [Conclusion and Further Analysis Ideas](#step4)
   [Dataset](#dataset)

<a name="step1"></a>
## 1. First Organization

In the first steps we'll get to know about our dataset and its fields.
We'll check some statistics and plot them to get familiar with the project and its characteristics.
### Features

**Fields**
- Demographic information about customers | **Gender, Seniorcitizen, Partnere, Dependents**
- Main services that each customer has signed up for | **Phoneservice, Multiplelines, Internetservice**
- Internet-based services which customers have signed up for | **Onlinesecurity, Onlinebackup, Deviceprotection, Techsupport, and Streamingtv and streamingmovies**
- Customers' accounts information | **Tenure, Monthlycharges, Totalcharges**
- Customers' financial information | **Contract, Paymentmethod, Paperlessbilling**
- Customers who left within the last month | **Churn**
### Packages

- **warnings**
- **Numpy**
- **Pandas**
- **Visualization Libraries (Matplotlib, Seaborn, Missingno)**
- **Statsmodels**
- **SciPy**
- **Sklean**
- **Other Modeling Modules**

<a name="step2"></a>

## 2. Second Step: Data Preprocessing

Here we'll equip our dataset to be ready foe modeling.

<a name="step3"></a>

## 3. Third and Final Step: Modeling

In the last part we'll check some famous relevant regression models and choose the best model for this dataset.
Tuning in this step can help to improve each model to get their best ability.

<a name="step4"></a>

## 4. Conclusion and Further Analysis Ideas

From the results of our experiments, we can observe that the Random Forest and Gradient Boosting Classifier models outperformed the other models in terms of test recall and accuracy.
These models have achieved values of around 76% in both recall and accuracy metrics, respectively.
There are a lot of analysis outputs above in all steps of this analysis.
Some of them, like correlation analysis, can be used in modeling.
Exploring the most important features that contribute to the Random Forest and Gradient Boosting Classifier models' performance can help to determine whether these features are relevant or could be modified to improve the models' performance.
Performing hyperparameter tuning for each model to improve their performance have been done, but it can be more than what there is in this project.
Dealing with outliers can also help improving models' performance which here has been ignored.

<a name="dataset"></a>

## Dataset

The data we have used in this project was downloaded from <a href = "https://www.kaggle.com/datasets/blastchar/telco-customer-churn" style="text-decoration:none;" target="_blank"> Kaggle</a>. 
There are more useful information about this dataset in the notebook.
You can also access the notebook uploaded on kaggle website through <a href = "https://www.kaggle.com/code/mamishere/customer-churn-complete-analysis-and-prediction/notebook" style="text-decoration:none;" target="_blank"> this link</a>. 