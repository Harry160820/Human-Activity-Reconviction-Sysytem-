# Human-Activity-Reconviction-Sysytem

**Introduction**

* **What it is:** This project uses machine learning to predict human activities such as walking, sitting, or standing based on sensor data.
* **Why it matters:** HAR has applications in areas like health monitoring, fitness tracking, and improving human-computer interactions.
* **What it does:** The pipeline processes raw sensor data, extracts meaningful features, trains a classification model, and predicts activity labels for new data inputs.

**Feature**
* End-to-end pipeline: Data preprocessing, feature engineering, model training, and evaluation.
* Accurate activity classification using advanced machine learning techniques.
* Deployment-ready Python script for real-time predictions.

**Tech Stack**
* **Programming Language:** Python
* **Libraries:** TensorFlow, scikit-learn, NumPy, pandas, joblib
* **Techniques:** Data preprocessing, feature extraction, classification

**Model Overview**
* Algorithm Used: Random Forest, Logistic Regression, Neural Networks
* Input Data: Data used in this model is collected from multiple cameras and sensors.
* Output: Accurate prediction of activities such as walking, standing, jumping etc.
* Model Accuracy: Achieved an accuracy of **91.25**% on the test dataset.

**Project Workflows**
1. **Data Collection:** Sensor data from Kaggle.
2. **Data Preprocessing:** Handling missing values, normalization, feature extraction.
3. **Model Training:** Training on labeled data.
4. **Evaluation:** Testing the model with evaluation metrics.
5. **Prediction:** Deploying the model for real-time or batch predictions.
