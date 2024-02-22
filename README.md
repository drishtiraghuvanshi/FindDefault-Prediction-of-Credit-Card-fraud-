# FindDefault-Prediction-of-Credit-Card-fraud
A credit card is one of the most used financial products to make online purchases and payments. Though the Credit cards can be a convenient way to manage your finances, they can also be risky. Credit card fraud is the unauthorized use of someone else's credit card or credit card information to make purchases or withdraw cash.
It is important that credit card companies are able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase. 
The dataset contains transactions made by credit cards in September 2013 by European cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.
We have to build a classification model to predict whether a transaction is fraudulent or not.
The accuracy of the model on the test data set should be > 75% (Subjective in nature) 

# Steps
1.Importing the Dependencies
2.Loading the data
3.Reading and understanding the data
4.Handling missing values
5.Data Preprocessing
6.Split the data into Training data & Testing Data
7.Model Evaluation

# Project Pipeline
The project pipeline can be briefly summarised in the following steps:

### Understanding Data: 
In this step, you need to load the data and understand the features present in it. This will help you choose the features that you need for your final model.
### Exploratory data analytics (EDA):
Normally, in this step, you need to perform univariate and bivariate analyses of the data, followed by feature transformations, if necessary. You can also check whether or not there is any skewness in the data and try to mitigate it, as skewed data can cause problems during the model-building phase.
### Train/Test Data Splitting:
In this step, you need to split the data set into training data and testing data in order to check the performance of your models with unseen data. You can use the stratified k-fold cross-validation method at this stage. For this, you need to choose an appropriate k value such that the minority class is correctly represented in the test folds.
### Model Building or Hyperparameter Tuning: 
This is the final step, at which you can try different models and fine-tune their hyperparameters until you get the desired level of performance out of the model on the given data set. Ensure that you start with a baseline linear model before going towards ensembles. You should check if you can get a better performance out of the model by using various sampling techniques.
### Model Evaluation: 
Evaluate the performance of the models using appropriate evaluation metrics. Note that since the data is imbalanced, it is important to identify which transactions are fraudulent transactions more accurately than identifying non-fraudulent transactions. Choose an appropriate evaluation metric that reflects this business goal.
### Business Impact: 
After the model has been built and evaluated with the appropriate metrics, you need to demonstrate its potential benefits by performing a cost-benefit analysis which can then be presented to the relevant business stakeholders.

# Conclusion
FindDefault is a powerful tool that uses advanced algorithms and machine learning techniques to analyze patterns and trends in credit card transactions. By examining various factors such as transaction amount, frequency, location, and time of day, FindDefault can accurately predict whether a transaction is likely to be fraudulent. This allows financial institutions to take immediate action to prevent unauthorized charges and protect their customers from potential financial losses.

Furthermore, FindDefault is constantly updated with new data and information, allowing it to adapt to changing fraud patterns and stay ahead of cybercriminals. By leveraging the power of technology and data analytics, FindDefault provides a proactive approach to fraud detection, helping financial institutions stay one step ahead of fraudsters.

In conclusion, FindDefault is a crucial tool in the fight against credit card fraud. By leveraging cutting-edge technology and predictive modeling, this tool helps financial institutions detect and prevent fraudulent activities, ultimately safeguarding the financial well-being of their customers. With the ever-evolving landscape of cybercrime, tools like FindDefault are essential in maintaining the security and integrity of the financial sector.

# Future Work
After the model has been deployed, the bank plans to provide a second layer of authentication for each of the transactions that the model predicts as fraudulent. If a payment gets flagged by the model, an SMS will be sent to the customer requesting them to call on a toll-free number to confirm the authenticity of the transaction.
