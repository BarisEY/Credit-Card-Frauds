# Fraudulent Transaction Detection using Random Forest Classifier and Genetic Algorithm
This Jupyter notebook demonstrates how to use machine learning techniques to detect fraudulent transactions using a random forest classifier and a genetic algorithm for feature selection.

The dataset used in this notebook is obtained from XXX, which contains a large number of credit card transactions, with 30 unknown features and 3 known features. The dataset is highly imbalanced, with only a small percentage of transactions being fraudulent.

We will use a genetic algorithm to select the most important features for the classification model. Then, we will train a random forest classifier on the selected features and evaluate its performance using the accuracy metric. The reason as to why the random forest classifier is being used is because of [this](https://journalofbigdata.springeropen.com/articles/10.1186/s40537-022-00573-8) study. In order to get the best possible outcome, the genetic algorithm will compare the accuracy score of many different combination and in the end, keep the solution with the highest score.

This notebook is suitable for data scientists and machine learning practitioners who want to learn how to use a random forest classifier with a genetic algorithm to detect fraudulent transactions in real-world datasets. The implementation details and code snippets are provided, along with the necessary explanations and visualizations.

Let's dive in!
