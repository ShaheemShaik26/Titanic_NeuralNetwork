# Titanic_NeuralNetwork
Predicting Survivors of Titanic from Kaggle Dataset using Neural Networks

I processed the Titanic dataset by removing irrelevant columns and imputing missing values for the Age and Embarked features. The dataset was then split into input features and the target variable. Categorical variables such as Sex, Embarked, and Pclass were one-hot encoded, and all features were standardized using feature scaling. After splitting the data into training and test sets, I developed a neural network with two hidden layers using the Keras framework. The model was compiled with the Adam optimizer and binary cross-entropy loss function, then trained for 50 epochs with a batch size of 16, while using a validation split to monitor performance during training.

The model on training data:
Train Loss: 0.3648
Train Accuracy: 0.8474

Titanic Competition entry leaderboard score : 0.78468
