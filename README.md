# Homework-2-CPSC-392-

Johanna Speiser
Student ID: 2380023
email: jospeiser@chapman.edu
CPSC-392-02

Homework 2

References:

ChatGPT
- For the Logistic Regression:
  - What does this line do? """print("Train Prescision: ", precision_score(y_train, y_pred_train))"""
  - What does this error mean? """ValueError: could not convert string to float: 'woman'"""
  - I am already using hone-hot encoding so why is this still a problem?
- For the Gradient Boosting Tree:
  - When would I use GradientBoostingClassifier() and when GradientGoosingRegression()?
- For adding the 200 highest-risk customers:
  - Why do I get this error message when I try using n.largest()? "AttributeError: 'numpy.ndarray' object has no attribute 'nlargest'"
  - How do I use .nlargest() if I want to get the 10 rows that had the highest predicted probability?
- For the KNN
  - What does this mean? """KeyError: "None of [Index(['age', 'income', 'meanhourswatched'], dtype='object')] are in the [index]""""
  - Which data frame does this assign neighbors to? """churn_new_df = churn2_df.assign(neighbors = list(neighbors))"""
  - What does this error message mean? """ValueError: Length of values (500) does not match length of index (487)"""
  - What can I add if I want the data frame similar users to only include 487 rows? """distances, neighbors = pipe.named_steps["model"].kneighbors(pipe.named_steps["z"].transform(similar_users[predictors_new]))
  

I Discussed some of my models with a family member. 
