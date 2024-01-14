# Importing Dataset:

- Imported a dataset containing information about clothes, including columns like Clothing ID, Age, Title, Review Text, Rating, Recommended IND, etc.


# Data Cleaning:

- dropped irrelevant columns like 'Title' and 'Review Text.'
- created a new column 'Review' by combining 'Title' and 'Review Text.'
- replaced NaN values with spaces.

# Text Cleaning:

- tokenized, lowercased, and stemmed the text.
- used the NLTK library for text processing and the SpellChecker library for spell checking.
- utilized both Bag of Words (BoW) and Term Frequency-Inverse Document Frequency (TF-IDF) models.

#Model Training:

- split the dataset into training and test sets for both BoW and TF-IDF approaches.
- trained various models, including Naive Bayes, Logistic Regression, KNN, Decision Tree, Random Forest, and XGBoost.
- evaluated model performance using accuracy scores and confusion matrices.
#  Visualizing Results:

- created bar plots to visualize the accuracy of models after implementing BoW and TF-IDF methods.
- plotted confusion matrices for each model to further evaluate their performance.

#Exploratory Data Analysis:

- explored the dataset's statistical summary and visualized the distribution of features such as 'Age.'
- analyzed the distribution of categorical variables like 'Rating,' 'Recommended IND,' 'Positive Feedback Count,' 'Division Name,' 'Department Name,' and 'Class Name.'
- created visualizations such as bar plots and heatmaps to understand relationships between variables.
- summary plots to visualize the distribution of ratings and other features across different categories like 'Division Name' and 'Department Name.'
-created a correlation heatmap to examine the relationships between numerical features.

