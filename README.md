Product Explorer App

A Flutter-based mobile application that allows users to browse products from an external REST API, authenticate using Firebase, and save favorite items to the cloud using Firestore.

Features
User Authentication with Firebase
Sign Up
Login
Logout
Product Browsing
Fetches product data from Fake Store API
Displays clothing products in a dynamic ListView
Responsive and user-friendly interface
Favorites Management
Save favorite products to Firebase Firestore
View saved favorites on a dedicated screen
Persistent user-specific data storage
Technologies Used
Flutter (Dart)
Firebase Authentication
Cloud Firestore
REST API Integration
HTTP Package
API Used
Fake Store API: https://fakestoreapi.com/products
Project Structure
lib/
├── screens/
├── widgets/
├── services/
├── models/
└── main.dart
Installation
Clone the repository
git clone <repository-url>
Install dependencies
flutter pub get
Configure Firebase
Create a Firebase project
Enable Authentication
Enable Cloud Firestore
Add google-services.json to the Android project
Run the application
flutter run
Learning Outcomes
Firebase Authentication integration
Firestore database operations
REST API consumption in Flutter
State management and asynchronous programming
Mobile UI development with Flutter
Screenshots

Add screenshots here:

Login Screen
Product List Screen
Favorites Screen
