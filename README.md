# Weather-Based Dress Recommender App

A **mobile application** built using **Android Studio (Java)** that recommends outfits based on weather conditions, location, and user input. The app integrates a **machine learning model** through a Flask API to provide accurate recommendations.

## Features

- **Weather-Based Recommendations**: Get dress suggestions tailored to your location, gender, temperature, and weather conditions.
- **User-Friendly Interface**: Simple input fields for entering place, gender, temperature, and weather condition.
- **Real-Time API Integration**: Connects with a Flask API to process data and provide results.
- **Machine Learning**: Incorporates an ML model to analyze user inputs and generate optimal clothing recommendations.

## How It Works

1. **User Input**: 
   - Enter location, gender, temperature, and weather condition.
2. **Data Processing**:
   - The app sends user inputs to a Flask-based API.
3. **ML Model**:
   - The ML model analyzes the inputs and generates a suitable clothing recommendation.
4. **Output**:
   - The recommendation is displayed on the app screen.

## Tech Stack

- **Frontend**: Android Studio (Java)
- **Backend**: Flask API
- **Machine Learning**: 
  - Utilizes Random Forest for classification and regression to analyze weather data, including temperature and conditions, to predict suitable clothing recommendations with high accuracy..

## Prerequisites

- Android Studio installed on your machine.
- A running Flask server with the ML model hosted.

## Installation and Setup

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Abhirami2306/Weather_based_dress_recomm.git
   cd Weather_based_dress_recomm
2. Setup Android Studio:

Open the project in Android Studio.
Sync Gradle files.
Build the project.
Run Flask API:

3. Navigate to the backend folder:
bash
Copy code
cd backend
python app.py

4. Run the App:
Use an Android emulator or physical device to run the app.
