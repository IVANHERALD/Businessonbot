# Businessonbot
Task given by Business on bot company

Flow of the code:
=> First the required packages are imported in the notebook.
=>Then the provided data set is split into two categories:
              ->Train dataset
              -> Test dataset
 =>The sentiment is split into two categories such as positive and negative.
 => Then the data cleaning is done re.sub statements.
 => Then it is displayed using charts and graphs.
 =>Finally the accuracy is predecited .
=>Created a model which classifies the tweets into one of the given target labels.
=>LabelEncoder is used here for transforming categorical values into numerical values.
=>By using vectorization, we have performed normalization of test data and stored it into x_test & y_test.
=>We have also predicted actual and predicted values.
=>Performed the accuracy of our model in the form of an AUC curve plotted using the matplotlib library.
=>Got a score of AUC – 0.64 for the classifier (Naive Byes).
