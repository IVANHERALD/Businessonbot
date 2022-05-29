# Businessonbot
Task given by Business on bot company

Flow of the code:
=>Imported libraries such as pandas to deal with data frames/datasets, re for regular expression, nltk is a natural language tool kit and from that, we have imported module – stopwords which are nothing but ‘dictionary’.
=>And have checked for the top 5 values in the dataset using head()
=>Further, I have performed some data visualizations using matplotlib and seaborn libraries which are really the best visualization libraries in Python. 
=>Converted text into the matrix of tokens, we have to import the following library and perform code
=>LabelEncoder is used here for transforming categorical values into numerical values.
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
