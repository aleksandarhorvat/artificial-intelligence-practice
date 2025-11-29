# Exercise 5

This exercise addresses binary classification on the Titanic dataset. The notebooks use knowledge acquired in previous exercises to preprocess the data and create the data splits required to train and evaluate models. The same algorithms used earlier are trained and evaluated and their performance compared. For more reliable results, k-fold cross-validation is applied. After selecting an algorithm, hyperparameter tuning is performed to obtain the best possible results, measured with standard classification metrics (accuracy, precision, recall, F1 score). Finally, the trained model is used to make predictions on the test set for submission to the Kaggle competition.

The dataset is available on Kaggle as part of the competition [Titanic - Machine Learning from Disaster](https://www.kaggle.com/c/titanic/overview). Generated predictions for the test set can be submitted there to see a score on the public leaderboard. Try improving the results from the exercises and submit them to the competition if desired.

## Files
- `titanic/` - folder for the Titanic task (exercise)
    - `titanic_solution.ipynb` - notebook with the solution for this exercise (not fully completed)
    - `titanic_dataset/` - folder with the dataset for this exercise
- `iris/` - folder for the Iris task (an additional, simpler task to try if unsure how to start)
    - `iris_solution.ipynb` - notebook with the solution for the Iris task
    - `iris_dataset/` - folder with the dataset for the Iris task