# Lending-Club-deep-learning-model

### Motivation: As the total amount of lending grows exponentially by years, it also raises the risk of default on loans.Therefore, we need some rules or regulations, in order to reduce the risk of default.
### Purpose: predict whether a borrower will be default on a loan.
### Benefit (business value): Help investors understand the true cost of lending, potentially reduce their risk of loss and improve their returns.
### predict targets: 3 class for identifying default ---> safe, warning, default.

# About the data
### Data: Lending Club loan data. (!!! 5 million data points !!!)
### Methodology: Applying machine learning and deep learning techniques, to create a forecasting model. Use deep learning CNN to build model, and validate by random forest. 
### Approach: using 33 features extracted from raw data, building a predictive model, and optimizing the model through testing and evaluation. 

# Steps of approach
### Get Understanding:  meaning of each column in the dataset and correct categorization of the data.
### Data Cleaning:  Removing the data we believe that will not be helpful to build the model.
### Feature Engineering:  Separating the modified version of dataset (less number of columns with numeric terms only) into feature matrix, and target vector (loan status).
### Modeling:  Building a model with deep learning based on convolution neural networks, and use random forest technique as a validation algorithm to make better lending decisions. 

# Imbalance data (original)
### Deep Learning Accuracy: 98.27%
### Random Forest Accuracy: 98.2%

# Balance (By SMOTE)
### Deep Learning Accuracy: 98.21%
### Random Forest Accuracy: 98.42%

# Obstacles of Lending Club Demo
### Since the accuracy and confusion matrix show both deep learning and random forest model can learn pretty well in balance and imbalance situations, we need to think about if any overfitting occurs.
### After print out the feature importance report from random forest model, I didn’t see any principal feature significantly leads to the target. 
### Milestone:  I will read more paper about building model on financial data, and keep improving the model and fix the potential ‘overfitting’ problem, and give the model more sense in the real-world finance. 

# Sth to say!!! 
### Per unit change of soup intergradient, and sensitives , and what is the major contributor of the model?
### Correlation may ignore nonlinear correlation, correlation occur in continuous variables


