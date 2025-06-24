#**AIR QUALITY PREDICTOR USING SENSOR DATA**
air quality perdition using sensor values
 Air Quality Prediction Using Machine Learning and Flask
 
**Overview:**
This project is a machine learning-based system designed to predict air quality using real-time sensor data. It takes in environmental parameters like temperature, humidity, and weight, and classifies the air quality into categories like Good, Moderate, or Poor using multiple ML algorithms. A simple and interactive Flask web application allows users to input data and view predictions instantly.

**Objective:**
To build a cost-effective, accessible, and scalable air quality monitoring system that helps individuals and communities take proactive measures against pollution, without relying on expensive equipment.
Machine Learning Algorithms Used:
K-Nearest Neighbors (KNN)
Decision Tree
Random Forest
Naïve Bayes
Support Vector Machine (SVM)
Each algorithm is trained and evaluated using cross-validation and performance metrics like accuracy and confusion matrix. The best-performing model is saved and integrated with Flask.


**Dataset Description:**
The model is trained on a CSV file that includes the following fields:
Column Name	Description
prod_id	Unique product or data entry ID
temperature	Temperature (°C)
humidity	Humidity (%)
weight	Sensor-measured weight or load
air_quality	Output label (Good, Moderate, Poor)


**Clone the repository:**
git clone https://github.com/yourusername/air-quality-predictor.git
cd air-quality-predictor

Install dependencies:

pip install -r requirements.txt

python app.py

http://127.0.0.1:5000/
