"Disease Prediction System using Machine Learning"
This repository contains a disease prediction system developed using machine learning techniques. The system aims to predict the likelihood of a person having a particular disease based on input symptoms and predicts disease with a accuracy of 95%.

Introduction
The Disease Prediction System is a machine learning-based application that assists in predicting the probability of a person having a specific disease. The system utilizes a trained model to make predictions based on input data provided by the user. It can be used by healthcare professionals, researchers, or individuals interested in gaining insights about potential diseases based on their symptoms.

Installation
To run the Disease Prediction System locally, follow these steps:

Step 1: Clone this repository to your local machine:

Step 2: Install the required dependencies using pip:

Step 3: Run the application:
root.mainloop()

Usage
Once the application is running, a pop up window opens. The main interface allows you to enter the required information, such as name and sysmptoms the patient feeling. After providing the necessary details, click on the "Predict" button to generate the disease prediction.

Dataset
The dataset used for training and testing the machine learning model is found in the directory namely training.csv and testing.csv. It contains anonymized patient records with attributes symptoms and the diagnosed diseases.

Model Training
The machine learning model was trained using the dataset mentioned above. The preprocessing steps, feature engineering, and model selection can be found '.ipynb' notebook. We used a supervised learning approach and various classification algorithms to train the model.

Results
The performance of the trained model is evaluated using different metrics such as accuracy, precision, recall, and F1-score.
