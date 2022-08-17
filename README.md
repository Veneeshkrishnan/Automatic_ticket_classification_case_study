# Automatic Ticket Classification
For a financial company, customer complaints carry a lot of importance, as they are often an indicator of the shortcomings in their products and servies. If these complaints are resolved efficiently in time, they can bring down the customer dissatisfaction to a minimum and retain them with stronger loyalty. This also gives them an idea of how to continuously improve their services to attract more customers.

## Table of Contents
* Problem Statement
* Structure of Case study
* Technologies-used
* Acknowledgements

## Problem Statement
* These customer complaints are unstructured text data. So, traditionally companies need to allocate the task of evaluating and assigning each ticket to the relevant department to multiple support employees. This becomes tedious as the company grows and has a large customer base.
* So the company wants to automate its customer tickets system. As a financial company, the firm has many products & services such as:
   1. Credit card/prepaid card
   2. Bank account services
   3. Theft/dispute reporting
   4. Mortgages/Loans
   5. Others
* we need to build a model that is able to classify customer complaints based on the products/servies. By doing so, we can segregate these tickets into their relevant categories and, therefore, help in the quick resolution of the issue.
* With the help of non-negative matrix factorization (NMF), an approach under topic modelling, you will detect patterns and recurring words present in each ticket. This can be then used to understand the important features for each cluster of categories.
* With the help of topic modelling, we will be able to map each ticket onto its respective department/category. we can then use this data to train any supervised model such as LOgistic Regression, Decision tree or random forest. Using this trained model, we can classify any new customer complaint support ticket into its relevant department.

## Structure of Case study:
* Introduction
* Problem Statement
* Pipeline that needs to be performed
* Data Loading and Preparation
* Text Preprocessing
* Exploratory Data Analysis
* Feature Extraction
* Topic Modelling
* Model Building and Evaluation
    1) Logistic Regression
    2) Decision Tree
    3) Random Forest
    4) Gaussian Naive Bayes
* Model Inference

## Technologies Used
- Python version 3.9.13
- numpy library version 1.20.1
- pandas library version 1.2.4
- matplotlib library version 3.3.4
- seaborn library version 0.11.1
- plotly library version 5.10.0
- wordcloud library version 1.8.2.2
- textblob library version 0.17.1
- nltk library version 3.7
- spacy library version 3.4
- scikit-learn library version 0.24.1
- git version 2.33.0.windows.1


## References
1. https://jovian.ai/the-sikdar/automatic-ticket-classification-assignment
2. https://github.com/derekgreene/topic-model-tutorial/blob/master/2%20-%20NMF%20Topic%20Models.ipynb
3. https://predictivehacks.com/topic-modelling-with-nmf-in-python/


## Contact
Created by [https://github.com/Veneeshkrishnan] - feel free to contact me!
1. Veneesh -  veneeshkrish96@gmail.com
