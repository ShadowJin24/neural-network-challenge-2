# neural-network-challenge-2

The main script is named "attrition_edit.ipynb"

## Part 1: Preprocessing
* Import the data and view the first five rows.

* Determine the number of unique values in each column.

* Create y_df with the attrition and department columns.

* Create a list of at least 10 column names to use as X data. Choose any 10 columns EXCEPT the attrition and department columns.

* Create X_df using the selected columns.
  * Show the data types for X_df.

* Split the data into training and testing sets.

* Convert your X data to numeric data types. Fit any encoders to the training data and then transform both the training and testing data.

* Create a StandardScaler, fit the scaler to the training data, and then transform both the training and testing data.

* Create a OneHotEncoder for the department column, fit the encoder to the training data and use it to transform both the training and testing data.

* Create a OneHotEncoder for the attrition column, fit the encoder to the training data and use it to transform both the training and testing data.

## Part 2: Create, Compile, and Train the Model
* Find the number of columns in the X training data.

* Create the input layer. (Do NOT use a sequential model), as there will be two branched output layers.

* Create at least two shared layers.

* Create a branch to predict the department target column. Use one hidden layer and one output layer.

* Create a branch to predict the attrition target column. Use one hidden layer and one output layer.

* Create the model.

* Compile the model.

* Summarize the model.

* Train the model using the preprocessed data.

* Evaluate the model with the testing data.

* Print the accuracy for both department and attrition.

## Part 3: Summary

1. Is accuracy the best metric to use on this data? Why or why not?

2. What activation functions did you choose for your output layers, and why?

3. Can you name a few ways that this model could be improved?
