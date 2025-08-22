# <img width="55" height="25" alt="image" src="https://github.com/user-attachments/assets/db216f07-167b-4d75-9d29-1165a7d43dbf" /> **Customer Churn Prediction Using ANN**

This project demonstrates how to build and train an Artificial Neural Network (ANN) to predict customer churn. Customer churn is a critical metric for businesses, and predicting it allows companies to proactively retain customers.

### Overview 
The main objective of this project is to create a deep learning model that can analyze a customer's information (such as their demographics, account details, and services they use) and predict whether they are likely to leave the company. The notebook walks through the entire process, from data preprocessing to model evaluation.

GitHub Repo: [https://github.com/Niharika-Rawat/DL-Customer-Churn/]

Dataset Source: [https://www.kaggle.com/datasets/blastchar/telco-customer-churn?resource=download]

The dataset used in this project is a CSV file containing information on various customers. The features include: 'customerID', 'gender', SeniorCitizen', 'Partner', 'Dependents',
       'tenure', 'PhoneService', 'MultipleLines', 'InternetService',
       'OnlineSecurity', 'OnlineBackup', 'DeviceProtection', 'TechSupport',
       'StreamingTV', 'StreamingMovies', 'Contract', 'PaperlessBilling',
       'PaymentMethod', 'MonthlyCharges', 'TotalCharges', 'Churn'.
       
The raw dataset is cleaned and prepared for the model. This includes handling categorical variables, scaling numerical features, and splitting the data into training and testing sets.The ANN is designed using Keras. The model consists of dense layer with ReLU activation functions and an output layer with a sigmoid activation function for binary classification. For model evaluation, I have made use of classification report and confusion matrix.

### Tech Stack 

* Pandas
* Numpy
* Matplotlib
* Seaborn
* Scikit-Learn / Sklearn
* Tensorflow
* Keras
