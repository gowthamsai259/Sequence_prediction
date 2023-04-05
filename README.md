# Sequence_prediction
The next number will be predicted for a given sequence.
Various algorithms like Linear regression, Decision tree and Random forest regressor are used to predict the next element of the sequence.

In machine learning, we typically split our data into input features and target variables.
In the case of predicting the next number in a sequence, we use the previous numbers in the sequence as the input features (X) and the next number in the sequence as the target variable (y). The idea is to train a model to learn the relationship between the input features and the target variable, so that it can make predictions for new, unseen data.

In the code example I provided using the random forest regressor, we first define the input sequence as a list of numbers. We then create a numpy array (X_train) from the input sequence, excluding the last element, since we're using the previous numbers as the input features. We also create a numpy array (y_train) from the input sequence, excluding the first element, since we're using the next number in the sequence as the target variable.

By splitting the data into input features and target variable, we can train our model to predict the next number in the sequence based on the previous numbers in the sequence. The input features (X_train) and target variable (y_train) are used to fit the random forest regressor model. Once the model is trained, we can use it to predict the next number in the sequence by passing in the last number in the sequence as the input feature.

Among all the algorithms Linear regression has shown a good and close result.
# Application:
These kind of algorithms can be used to solve the aptitude problems.
This algorithm helps us to eliminate the options in the problem easily.
