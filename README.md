# Credit_Card_Fraud_Detection

Libraries Used :

1. Numpy 
2. Pandas 
3. Train_test_split
4. LogisticRegression
5. Accuracy_score

1. Loading the dataset to a Pandas DataFrame
2. First 5 rows of the dataset
3. Dataset informations Using 'Info'
4. Checking the number of missing values in each column Using 'isnull()'
5. Distribution of legit transactions & fraudulent transactions Using 'value_counts()'

# This Dataset is highly unblanced

0 --> Normal Transaction

1 --> fraudulent transaction

# separating the data for analysis based on legit and fraud and used 'shape' for rows and columns

# statistical measures of the data using 'describe

# compare the values for both transactions using 'Groupby'

# Under-Sampling

1.  Build a sample dataset containing similar distribution of normal transactions and Fraudulent Transactions
2.  Number of Fraudulent Transactions --> 492
3.  We can Concatenating two DataFrames

# Splitting the data into Features & Targets

X = Indepedent
Y = Dependent

# Split the data into Training data & Testing Data

1. X_train, X_test, Y_train, Y_test 

# Model Training

1.  Logistic Regression

Then Training the Logistic Regression Model with Training Data using fit(X_train, Y_train)

# Model Evaluation
## Accuracy Score

1. Finding accuracy on training data

2. Finding accuracy on test data
