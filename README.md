# Player rating prediction  - Football




# Project Description

This project is based upon the player dataset released by Sevilla FC and FC Bengaluru as part of the initiative to promote Data-Driven Player Performance Assesment (Hosted on Analytics Vidhya). The provided dataset contains matchwise player perfomance (as rating), player attributes as well as team attributes compiled by 21 scouts over the course of 10 different competitions. The approach to solve the problem was as follows:

1. Divide the dataset provided into train & test sets.
2. Understand the various features available in the dataset.
3. Treat missing values (dropping through threshold methods & filling through imputation)
4. Encode categorical variables.
5. Modeling the data (Xtreme Boosting Regressor) & Initial Evaluation of Performance through Cross Validation.
6. Tuning the hyperparameters to improvve model performance.
7. Checking Model performance on test dataset.


# Results

The metric used to measure model performance is R2 Score ( Coefficient of Determination). The initial model constructed on the training set resulted in a r2 score of ~ 0.25 which improved to ~ 0.35 after tuning of Hyperparameters. The model performance increased on the test dataset (unseen) data with a score of ~ 0.38. According to the current results observed, the model's ability to explain the variance in the dataset is quite moderate (~ 40 %). Since the dataset had close to 800 features, no additional features were created. Additionally feature selection methods were also not employed owing to the size of the dataset. These are two possible avenues to explore in order to improve current model performance.
