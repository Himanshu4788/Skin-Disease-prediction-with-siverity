# Skin-Disease-prediction-with-siverity

📌 Overview
This project uses a Convolutional Neural Network (CNN) to identify skin diseases from dermoscopic images and assigns a severity level (Mild / Moderate / Severe) based on confidence scores and lesion area analysis. It is deployed as a REST API using Flask, enabling real-time inference from image uploads.

🧠 Features

Disease Classification — Detects 4 types of skin diseases from dermoscopic images
Severity Grading — Assigns Mild / Moderate / Severe based on confidence thresholds and lesion segmentation
Lesion Segmentation — Uses OpenCV to isolate and measure affected skin area
REST API — Flask-based API accepts image uploads and returns structured JSON predictions
High Precision — Evaluated on dermoscopic test datasets with strong classification performance
