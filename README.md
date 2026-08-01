🍽️ Kitchen Key: AI-Assisted Recipe Discovery and Meal Planning Platform

An AI-powered cross-platform application that helps users discover recipes based on available ingredients, generate personalized meal plans, create shopping lists, and maintain healthy eating habits through hydration tracking and smart notifications.

📖 Overview

Kitchen Key is a Final Year Project developed at COMSATS University Islamabad, Abbottabad Campus.

The application simplifies everyday meal planning by allowing users to discover recipes using ingredients they already have, generate AI-assisted recipes, organize weekly meal plans, automatically create shopping lists, and monitor hydration and nutrition in one integrated platform.

The system follows a client-server architecture consisting of a Flutter application and a Django REST Framework backend with secure JWT authentication, Google Sign-In, Firebase Cloud Messaging, and an intelligent recommendation engine.

✨ Features
👤 User Management
User Registration & Login
JWT Authentication
Google Sign-In
User Profile Management
🍳 Recipe Discovery
Search Recipes
Browse Recipe Categories
View Recipe Details
Save Favorite Recipes
Filter by Dietary Preferences
Halal/Haram Information
Nutrition Information
🤖 AI Features
AI-Assisted Recipe Generation
Ingredient-Based Recipe Suggestions
Content-Based Recipe Recommendation System
Personalized Meal Planning
📅 Meal Planning
Weekly Meal Planner
Auto Meal Plan Generation
Shopping List Generator
Grocery List Grouped by Aisles
💧 Health & Wellness
Water Intake Tracker
Daily Hydration Goals
Nutrition Dashboard
Meal Reminders
Hydration Notifications
🔔 Notifications
Firebase Push Notifications
Scheduled Meal Reminders
Hydration Reminders
🏗️ System Architecture
Flutter Application
        │
        ▼
REST API (Django REST Framework)
        │
        ├── Authentication
        ├── Recipe Services
        ├── Meal Planner
        ├── Hydration Module
        ├── Shopping List
        └── Notification Service
        │
        ▼
SQLite Database
+
Recipe JSON Dataset
🛠️ Technologies Used
Frontend
Flutter
Dart
Riverpod
go_router
Dio
Backend
Python
Django
Django REST Framework
Database
SQLite
JSON Lines (Recipe Dataset)
Authentication
JWT Authentication
Google OAuth
AI / Machine Learning
TF-IDF
Truncated SVD
Content-Based Recommendation System
Notifications
Firebase Cloud Messaging (FCM)
Celery
Redis
Version Control
Git
GitHub
📂 Project Structure
Kitchen-Key/
│
├── backend/
│   ├── recipes/
│   ├── userdata/
│   ├── core/
│   ├── requirements.txt
│   └── manage.py
│
├── frontend/
│   ├── lib/
│   ├── assets/
│   ├── android/
│   ├── ios/
│   ├── web/
│   └── pubspec.yaml
│
├── screenshots/
│
├── README.md
│
└── LICENSE
🚀 Installation
Clone Repository
git clone https://github.com/SaimKhan9/FYP.git
Backend Setup
cd backend

python -m venv venv

source venv/bin/activate
# Windows
venv\Scripts\activate

pip install -r requirements.txt

python manage.py migrate

python manage.py runserver
Frontend Setup
cd frontend

flutter pub get

flutter run
📱 Core Modules
Authentication
Home
Recipe Search
Recipe Details
AI Recipe Generator
Ingredient-Based Suggestions
Meal Planner
Shopping List
Hydration Tracker
Notifications
Favorites
User Profile
🤖 AI Recommendation Engine

Kitchen Key utilizes a content-based recommendation system using:

TF-IDF Vectorization
Truncated Singular Value Decomposition (SVD)

The recommendation engine analyzes recipe ingredients, cuisine, tags, and nutritional information to suggest recipes that best match user preferences and available ingredients.

🔒 Security Features
JWT Authentication
Google OAuth Login
HTTPS Communication
Secure Password Hashing
Protected REST APIs
