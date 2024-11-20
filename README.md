# Weather-Based Dress Recommender App

A feature-rich mobile application built using **Android Studio (Java)** that recommends outfits based on weather conditions, user location, and preferences. This innovative app integrates a **machine learning model** through a **Flask API** to deliver personalized and accurate clothing suggestions for varying weather scenarios.

---

## Features

- **Weather-Based Recommendations**  
  Tailored clothing suggestions based on location, gender, temperature, and weather conditions such as sunny, rainy, or cold.

- **Interactive and User-Friendly Interface**  
  Clean design with input fields for user-specific details, providing an easy and intuitive experience.

- **Real-Time API Integration**  
  Communicates seamlessly with a Flask-based backend to process user data and deliver prompt recommendations.

- **Machine Learning-Driven Predictions**  
  Employs a robust ML model trained on weather data to ensure recommendations align with user needs and local conditions.

- **Customizable Backend**  
  The Flask API can be updated or expanded to support additional weather parameters or features as required.

---

## How It Works

### 1. **User Input**  
   - The user provides details such as:  
     - Location  
     - Gender  
     - Temperature  
     - Weather conditions  

### 2. **Data Processing**  
   - These inputs are sent to a Flask-based API via **HTTP POST requests**, ensuring fast and secure communication.

### 3. **Machine Learning Model**  
   - A **Random Forest model** analyzes the data, leveraging its classification and regression capabilities to suggest suitable outfits tailored to the user's specific input.

### 4. **Recommendation Output**  
   - The app receives the result from the Flask API and displays it to the user in a clear and concise manner.

---

## Tech Stack

- **Frontend:**  
  - Android Studio (Java)  

- **Backend:**  
  - Flask API  

- **Machine Learning:**  
  - **Random Forest Algorithm** for both classification and regression to analyze weather parameters like temperature and conditions, offering reliable predictions.

---

## Prerequisites

1. **Android Studio**  
   - Installed and configured on your machine.

2. **Flask Server**  
   - A running Flask server hosting the machine learning model for processing requests.

3. **API Key (Optional)**  
   - If the Flask API is secured, ensure you have the required authentication keys.

---

## Installation and Setup

### 1. Clone the Repository  
git clone https://github.com/Abhirami2306/Weather_based_dress_recomm.git  
cd Weather_based_dress_recomm  

2. Setup Android Studio
Open the project in Android Studio.
Sync the Gradle files to ensure all dependencies are resolved.
Build the project successfully.

3. Run the Flask API
Navigate to the backend folder:
cd backend  
python app.py  

4. Run the App
Deploy the app on an Android emulator or a physical Android device.
Ensure the Android device or emulator can connect to the Flask server (use http://10.0.2.2:5000 for emulators).

*Machine Learning Details*

Random Forest

The model uses a dataset containing weather parameters like temperature, humidity, and conditions to train a decision-tree ensemble.
It performs classification to categorize weather conditions and regression to handle numerical inputs such as temperature.
This dual capability ensures precise recommendations for diverse scenarios.
Training Data

Historical weather data combined with clothing preferences to map conditions with appropriate attire.
Scalability

The ML pipeline can be updated with new features such as humidity, wind speed, or seasonal patterns to further enhance prediction accuracy.

*Future Enhancements*

Weather API Integration

Automate location and weather condition retrieval using APIs like OpenWeather or WeatherStack.
Outfit Suggestions with Images

Add image-based recommendations for better visualization.
Multi-Language Support

Expand app usability by adding support for additional languages.
Offline Mode

Cache recommendations to provide functionality even without internet access.

