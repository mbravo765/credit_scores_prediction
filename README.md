# credit_scores_prediction
Objective The purpose of this model is to predict an individidual's credit score. This model could be used by banks to determine a person's probability of defaulting on a loan.

Dataset https://www.kaggle.com/datasets/sujithmandala/credit-score-classification-dataset

The features in this dataset include the following:

age
gender
income
education
marital status
number of children
home ownership *credit score
Methadology

I will use supervised learning in the form of a K-Nearest Neighbors (KNN) algorithm. I can use supervised learning because the dataset includes labeled data that has been tagged with a correct classification (in this case, credit score). The trained machine should be able to make predictions on credit score (low, high, average) based on the user's age, gender, income, education, marital status, number of children, and home ownership. This is a classification problem because I predict categorical values of credit score. The KNN algorithm will predict the lavel of its K nearest neighbors (in this model, it is 3) in the training dataset.
