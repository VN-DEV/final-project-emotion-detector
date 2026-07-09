# Emotion Detector Application

An AI-based web application developed using the **Flask** web framework and **IBM Watson NLP (Natural Language Processing)** library. This application analyzes the emotional tone of text provided by user input and predicts scores for various emotions, including anger, disgust, fear, joy, and sadness, along with the dominant emotion.

## Features
- **Emotion Prediction:** Utilizes Watson NLP's Emotion Detection capability.
- **Output Formatting:** Returns structural data with scores for individual emotions and identifies the dominant emotional response.
- **Robust Error Handling:** Properly captures `400` status codes for blank or empty user text inputs, displaying appropriate warnings.
