# Career Mentor: AI-Powered Career Guidance App

![Career Mentor Logo](https://i.imgur.com/your-logo-image-url.png) 
This repository contains the source code for the **Career Mentor** mobile application, a prototype developed for the **Google Gen AI Exchange Hackathon**.

## 📖 About the Project

Career Mentor is an intelligent, mobile-first application designed to revolutionize career guidance. It addresses the common challenge faced by students and professionals: navigating a complex job market with generic, one-size-fits-all advice.

The app's key innovation is its use of **Google's Generative AI**. Instead of providing static, pre-written roadmaps, the app analyzes a user's unique profile—their desired job and existing skills—to generate a dynamic, step-by-step career path in real-time, ensuring the guidance is always relevant, tailored, and up-to-date.

---

## ✨ Key Features

* **🤖 AI-Personalized Roadmaps:** Generates unique learning paths with specific skills, tools, and projects for any career goal.
* **💬 Interactive AI Mentor:** A chat feature allowing users to ask contextual questions and receive immediate, human-like advice.
* **📊 Progress Tracking:** A visual dashboard to monitor the completion of skills and tasks, keeping users motivated.
* **🔒 Secure User Profiles:** Manages user data, authentication, and progress securely using Google Firebase.

---

## 🛠️ Tech Stack

This project is a full-stack application built with a modern technology stack.

* **Frontend:** React Native, Expo
* **Backend:** Node.js, Express.js
* **Data Scripting:** Python
* **Database & Auth:** Firebase (Firestore, Authentication)
* **Generative AI:** Google Gemini API

---

## 🚀 Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

* [Node.js](https://nodejs.org/) installed
* [Python](https://www.python.org/downloads/) installed
* An active Firebase project
* Expo Go app on your mobile device

### Installation & Setup

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/Career-Mentor-App.git](https://github.com/your-username/Career-Mentor-App.git)
    cd Career-Mentor-App
    ```

2.  **Setup the Backend:**
    ```bash
    # Navigate to the backend folder
    cd backend

    # (Optional) If you add npm dependencies to the backend in the future
    # npm install

    # Start the server
    node server.js
    ```
    *The backend server will be running on `http://localhost:3000`.*

3.  **Setup the Frontend (Mobile App):**
    ```bash
    # Navigate to the app folder from the root directory
    cd My-App

    # Install dependencies
    npm install

    # Create a .env file in the /My-App folder and add your Firebase keys
    # See .env.example for the required format (e.g., EXPO_PUBLIC_FIREBASE_API_KEY="...")

    # IMPORTANT: Update the API_BASE_URL constant in the screen files
    # (e.g., DashboardScreen.jsx) to your computer's local IP address.

    # Start the Expo development server
    npx expo start
    ```
4.  Scan the QR code from the terminal using the Expo Go app on your phone.
