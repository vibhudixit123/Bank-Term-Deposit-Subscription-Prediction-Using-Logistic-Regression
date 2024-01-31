
# Bank Term Deposit Subscription Prediction
This repository contains the code and documentation for a machine learning project focused on predicting customer term deposit subscriptions using logistic regression. The dataset used for this project is bank_data.csv. The goal is to predict whether a client will subscribe to a term deposit, enabling targeted marketing for enhanced campaign effectiveness in banking.


## Screenshots

![Screenshot 2024-01-31 224320](https://github.com/vibhudixit123/LOGISTIC_REGRESSION/assets/104568465/59563248-1f5a-4984-87ee-6d0a418fe214)
![Screenshot 2024-01-31 224304](https://github.com/vibhudixit123/LOGISTIC_REGRESSION/assets/104568465/a4346b32-eb41-4070-8dc1-263cd57e2a81)
![Screenshot 2024-01-31 224347](https://github.com/vibhudixit123/LOGISTIC_REGRESSION/assets/104568465/4b097ddd-9b26-4906-820f-f2fe719cb31b)
![Screenshot 2024-01-31 224401](https://github.com/vibhudixit123/LOGISTIC_REGRESSION/assets/104568465/69c28321-b2ba-452f-b86e-00c1bb91bfa9)



## Data:
The bank_data.csv dataset includes various features related to clients, such as age, income, and other relevant attributes. The target variable, denoted as "y," indicates whether a client subscribes to a term deposit (1) or not (0).
## Machine Learning Model:
The project utilizes logistic regression, a classification algorithm, to predict customer term deposit subscriptions:

Logistic Regression:

Logistic regression is employed to model the probability of a client subscribing to a term deposit based on features such as age, income, and others.
The logistic function is used to map predicted values to probabilities, making it suitable for binary classification.
## Data Preprocessing:
Various preprocessing techniques are applied to the dataset to prepare it for model training:

Handling Categorical Variables:

Categorical variables are encoded using techniques such as one-hot encoding to convert them into numerical format.

Scaling Numerical Features:

Numerical features are scaled to bring them to a similar scale, preventing certain features from dominating the model.

Splitting the Dataset:

The dataset is split into training and testing sets to evaluate the model's performance on unseen data.
## Target Audience:
This project is relevant for marketing teams in banking institutions. The machine learning model developed here assists in predicting which clients are more likely to subscribe to a term deposit, enabling targeted marketing strategies for campaign effectiveness.
## Training and Evaluation:
The logistic regression model is trained on a portion of the dataset and evaluated on another to ensure robust performance. Performance metrics such as accuracy, precision, recall, and F1 score are calculated.
## License

[MIT](https://choosealicense.com/licenses/mit/)

