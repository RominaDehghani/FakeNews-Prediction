# FakeNews Prediction
This project uses machine learning to classify news articles as real or fake. It employs Logistic Regression for classification and utilizes TF-IDF Vectorization and stemming for text preprocessing.

Dependencies:
numpy
pandas
nltk
scikit-learn
joblib

Install dependencies with:
pip install numpy pandas scikit-learn nltk joblib

Steps:
Data Preprocessing: Clean and stem the text data, then convert it to numerical features using TF-IDF.
Model Training: Train a Logistic Regression model.
Evaluation: Calculate accuracy scores on training and test data.
Save Model: Save the trained model using joblib.
Prediction: Predict whether new news articles are real or fake.

You can find the dataset file: https://www.kaggle.com/c/fake-news/da...

How to Run:
Load the dataset (train.csv).
Run the code to train and evaluate the model.
Use the trained model to predict new news articles.
