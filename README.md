# SMS Spam Detector

## Description

This project demonstrates a simple SMS spam classification model using machine learning. It utilizes a pipeline with TF-IDF vectorization and a Linear Support Vector Classifier (SVC) to categorize text messages as either "spam" or "not spam" (ham).

## How it works

1. **Data:** The model is trained on the SMSSpamCollection dataset, which contains labeled SMS messages.
2. **Pipeline:** A pipeline is created using `TfidfVectorizer` to convert text messages into numerical features and `LinearSVC` to classify the messages.
3. **Prediction:** The `sms_prediction` function takes a new text message as input and predicts its classification using the trained model.
4. **Gradio Interface:** A user-friendly interface is built using `gradio` to allow users to input text messages and view the predictions.


## Requirements

- pandas
- scikit-learn
- gradio

