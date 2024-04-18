# ROCK_MINE_ACCURACY_PREDICTION
The project titled "ROCK MINE PREDICTION" aims to predict the accuracy score of hitting a submarine by a rock or a mine using different machine learning models. The problem statement involves utilizing various algorithms to determine the accuracy of classification between rocks (denoted as 'R') and mines (denoted as 'M') based on provided data.

The project follows these key steps:

Data Preparation: Loading the sonar data, which presumably contains features related to sonar readings, along with labels indicating whether the object detected is a rock or a mine.

Data Splitting: Splitting the data into training and testing sets to train models on a subset of data and evaluate their performance on unseen data.

Model Implementation: Attempting to implement three different models:

Linear Regression: Used for predicting continuous numeric values; however, it couldn't be applied due to the categorical nature of the target variable.
Random Forest Regressor: An ensemble learning method for regression tasks, also not applicable due to the categorical target variable.
Logistic Regression: A classification algorithm suitable for binary classification tasks, thus used for predicting whether the detected object is a rock or a mine.
Model Evaluation: Evaluating the Logistic Regression model's performance on both training and testing datasets using accuracy scores.

Results Summary: Creating a DataFrame to summarize the results of the implemented models, including the method used and the corresponding training and test data accuracy scores.

The Logistic Regression model achieved a training data accuracy of approximately 81.93% and a test data accuracy of around 78.57%. These results indicate that the model performs reasonably well in classifying rocks and mines based on the provided features.

Overall, the project demonstrates the application of machine learning techniques to address a classification problem related to submarine detection, providing insights into the effectiveness of different algorithms in this context.



