# Rice-Disease-Detection-app

This is a web-based application built using **Django** and **Deep Learning (CNN & VGG16)** to identify diseases in rice plants from images. The system provides real-time predictions and stores location-based disease data.

## 🚀 Features
- [cite_start]**User Authentication:** Secure register and login system.
- **Disease Prediction:** Uses a Custom CNN and VGG16 transfer learning model to classify 4 types of plant conditions.
- [cite_start]**Location Mapping:** Saves the latitude and longitude where the disease was detected[cite: 1074].
- **History Tracking:** Stores prediction results for future reference.

## 🛠️ Tech Stack
- **Backend:** Django (Python)
- **Frontend:** HTML, CSS, JavaScript
- **Deep Learning:** Keras, TensorFlow, OpenCV
- [cite_start]**Database:** SQLite (Default) / MySQL (Setup provided in DB.txt) [cite: 1, 1073]

## 📋 Database Structure
The project uses the following tables:
1. [cite_start]**Register:** Stores user profile details (username, password, contact, email, address).
2. [cite_start]**Locations:** Stores image names, predicted diseases, and GPS coordinates[cite: 1074].

