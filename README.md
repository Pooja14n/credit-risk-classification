# credit-risk-classification

In this Challenge, we have to use various techniques to train and evaluate a model based on loan risk. A dataset of historical lending activity from a peer-to-peer lending services company is provided, using which we have to build a model that can identify the creditworthiness of borrowers.

# Requirements
The requirements for this Challenge are divided into the following subsections:
1. Split the Data into Training and Testing Sets
2. Create a Logistic Regression Model with the Original Data
3. Write a Credit Risk Analysis Report

# 1. Split the Data into Training and Testing Sets
1. In the starter code notebook, complete the following steps:
  a. Read the `lending_data.csv` data from the Resources folder into a Pandas DataFrame.
  b. Create the labels set (`y`) from the “loan_status” column, and then create the features (`X`) DataFrame from the remaining columns.
  c. Split the data into training and testing datasets by using `train_test_split`.

# 2. Create a Logistic Regression Model with the Original Data
1. Using logistic regression, complete the following steps:
  a. Fit a logistic regression model by using the training data (`X_train` and `y_train`).
  b. Save the predictions for the testing data labels by using the testing feature data (`X_test`) and the fitted model.
  c. Evaluate the model’s performance by doing the following:
    (i) Generate a confusion matrix.
    (ii)Print the classification report.
  d. Answer the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?

# 3. Write a Credit Risk Analysis Report
Write a brief report that includes a summary and analysis of the performance of the machine learning models that you used in this homework. This report should be written as the README.md file included in the GitHub repository.

Structure the report by using the report template that `Starter_Code.zip` includes, ensuring that it contains the following:
1. <b>An overview of the analysis:</b> Explain the purpose of this analysis.
2. <b>The results:</b> Using a bulleted list, describe the accuracy score, the precision score, and recall score of the machine learning model.
3. <b>A summary:</b> Summarize the results from the machine learning model. Include the justification for recommending the model for use by the company. If the model is not recommended, the reasoning must be justified.

