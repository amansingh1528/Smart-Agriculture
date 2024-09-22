# Smart Agriculture System Using IoT and Machine Learning

## Project Overview

This project presents an **IoT and Machine Learning-based Smart Agriculture System** aimed at improving crop management through **disease prediction**, **precision irrigation**, and **fertilization**. By analyzing sensor data from low-resolution cameras and environmental sensors, the system predicts potential plant diseases and provides targeted suggestions for treatment.

## Features

- **Real-time Crop Disease Detection**: Uses image analysis with low-resolution cameras to detect early signs of plant diseases.
- **IoT Sensor Integration**: Collects data from soil moisture sensors, humidity sensors, and temperature sensors for precision agriculture.
- **Disease Prediction Model**: Utilizes a deep learning model trained on plant images for early disease detection and intervention.
- **Remedy Suggestion**: Provides treatment recommendations for detected diseases, enhancing crop management.
- **Smart Irrigation**: Automatically adjusts irrigation schedules based on soil moisture and weather predictions.
- **User-Friendly Interface**: A web-based application allows farmers to monitor crop health and environmental conditions.

## Technologies Used

- **Machine Learning**: Disease prediction model using convolutional neural networks (CNNs) for image classification.
- **IoT**: Sensor integration for environmental data collection (soil moisture, humidity, temperature).
- **Streamlit**: Web application framework for user interaction and disease prediction visualizations.
- **Python**: Backend development for model integration and sensor data analysis.
- **TensorFlow/Keras**: For building and training the deep learning model.
- **Speech Recognition**: Real-time speech-to-text conversion for voice-based interaction with the system (optional feature).

## Installation Guide

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-repo/smart-agriculture.git
   cd smart-agriculture
2. **Install Required Dependencies**
   ```bash
   pip install Tensorflow streamlit
3. **Run the Web Application**
   ```bash
   streamlit run app.py
4. **Set up IoT Sensors**
   - Connect the soil moisture, humidity, and temperature sensors to the IoT hub.
   - Ensure the sensors are calibrated and configured to send data to the application.

##How It Works
- Data Collection: IoT sensors collect real-time environmental data, while cameras capture images of crops.
- Disease Prediction: The captured images are passed through the machine learning model for disease detection.
- Actionable Insights: The system analyzes the data and provides disease predictions and remedies.
- Precision Irrigation: Based on soil moisture data, the system automatically optimizes the irrigation process.
- User Interaction: The web app provides a dashboard for farmers to monitor crop health and receive alerts.

##Usage Instructions
- Open the Streamlit Application: Access the dashboard at localhost:8501.
- Upload Plant Images: Click on the "Upload Image" button to submit crop images for disease detection.
- Monitor Sensor Data: View real-time updates of soil moisture, humidity, and temperature on the dashboard.
- View Disease Predictions: After processing, the system will display any detected diseases and suggested treatments.
