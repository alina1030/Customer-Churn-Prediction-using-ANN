# Customer-Churn-Prediction-using-ANN

**AIM** 

To build a customer churn prediction model using Artificial Neural Network or ANN. Also to understand precision,recall and accuracy of this model by using confusion matrix and classification report

**DATASET**

Telco Customer Churn dataset containing the following

- Customers who left within the last month – the column is called Churn

- Services that each customer has signed up for – phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies

- Customer account information – how long they’ve been a customer, contract, payment method, paperless billing, monthly charges, and total charges


- Demographic info about customers – gender, age range, and if they have partners and dependents

**METHODOLOGY**

1. Load the dataset into a dataframe
2. Pre-process the data
   - Drop columns that may not add value for churn prediction
   - Identify missing values & drop them if required
   - Convert any text/string to numerical data
3. Standardize the dataset values between 0 to 1 using MinMax scaler function
4. Split the dataset as train and test set
5. Build an ANN model containing three layers(input, hidden and output layer)
6. Compile and fit the ANN model
7. Evaluate and predict the model
8. Analyze the performance of the model
   - Classification report(precision, recall, f1-score,accuracy)
   - Confusion matrix 

