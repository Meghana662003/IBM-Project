# Chatbot Project

## 📌 Overview
This project is a simple chatbot that uses **Flask** for the backend and a web-based frontend for user interaction. The chatbot responds to user queries based on predefined intents stored in `intents.json`.

## 🛠️ Installation & Setup
### **1️⃣ Prerequisites**
Ensure you have **Python 3.12+** installed on your system.

### **2️⃣ Install Required Dependencies**
Open a terminal or PowerShell in the project folder and run:
```sh
pip install flask flask-cors
```

## 🚀 Running the Chatbot
### **1️⃣ Start the Backend (Flask Server)**
In the project directory, run:
```sh
python app.py
```
This will start the Flask server on `http://127.0.0.1:5000/`.

### **2️⃣ Open the Frontend (Chat Interface)**
1. Open the `index.html` file in a web browser.
2. Type messages in the chatbox and receive responses from the chatbot.

## 📂 Project Structure
```
chatbot_project/
│── app.py                 # Flask backend for processing chatbot responses
│── intents.json           # Contains chatbot intents (patterns & responses)
│── index.html             # Frontend user interface for chatbot
│── static/                # Contains CSS, JavaScript (if any)
│── templates/             # (Optional) Flask HTML templates
```

## 🛠️ How It Works
1. **User enters a message** in the chatbox.
2. **Frontend (index.html) sends the message** to Flask (`/chat` endpoint).
3. **Flask processes the message** by matching it with intents in `intents.json`.
4. **Flask sends a response** back to the frontend.
5. **User sees the chatbot’s reply** in the chatbox.

## ✅ Features
- Predefined chatbot responses using `intents.json`
- Backend built with Flask
- Simple web-based frontend
- CORS enabled for frontend-backend communication

## 📌 Future Improvements
- AI-based intent recognition using NLP
- Database integration for dynamic responses
- Deployment to a cloud platform



