# ****Credit-risk-classification****

## Instructions
The instructions for this Challenge are divided into the following subsections:

1. Split the Data into Training and Testing Sets

2. Create a Logistic Regression Model with the Original Data

3. Write a Credit Risk Analysis Report

## Split the Data into Training and Testing Sets
Open the starter code notebook and use it to complete the following steps:

1. Read the lending_data.csv data from the Resources folder into a Pandas DataFrame.

2. Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns.

  * NOTE: A value of 0 in the “loan_status” column means that the loan is healthy. A value of 1 means that the loan has a high risk of defaulting.

3. Split the data into training and testing datasets by using train_test_split.

## Create a Logistic Regression Model with the Original Data
Use your knowledge of logistic regression to complete the following steps:

1. Fit a logistic regression model by using the training data (X_train and y_train).

2. Save the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model.

3. Evaluate the model’s performance by doing the following:

  * Generate a confusion matrix.

  * Print the classification report.

4. Answer the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?

## Write a Credit Risk Analysis Report
Write a brief report that includes a summary and analysis of the performance of the machine learning models that you used in this homework. You should write this report as the README.md file included in your GitHub repository.

Structure your report by using the report template that Starter_Code.zip includes, ensuring that it contains the following:

1. ****An overview of the analysis****: 
     The main aim of this model to train and evaluate Logistic Regression models to correctly identify credtworthiness of borrowers.

3. ****The results****:
      1. Accuracy: The accuracy of the model is 0.99, meaning that it correctly classifies 99% of the instances.
      2. Precision:
    *  For healthy loans ('0'): The model has a precision of 1.00, which means it perfectly identifies true positives with no false positives.
    *   For high-risk loans ('1'): The model has a precision of 0.85, which means it is moderately  effective in identifying high-risk loans with some false positives.
    *   In some cases 85% precision might be considered good but when compared with the 100% precision even 85% leaves scope for improvement
      3.  Recall:
     *  For healthy loans ('0'): The model has a recall of 0.99, meaning that it perfectly identifies all instances of healthy loans with no false negatives.
     *   For high-risk loans ('1'): The model has a recall of 0.91, meaning that it is moderately effective in identifying high-risk loans with some false negatives.
5. ****A summary****: Summarize the results from the machine learning model. Include your justification for recommending the model for use by the company. If you don’t recommend the model, justify your reasoning.
