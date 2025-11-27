🚨 AlertMate – Smart Disaster Alert & Mapping System

AlertMate is a location-aware disaster safety assistant that provides instant detection, visualization, and alerts for hazards like floods, heavy rainfall, and poor air quality.
It combines geolocation, maps, backend alerts, and an ML prediction model into one simple, user-friendly system.



📁 Project Structure (Exact)
DSATM HACK-SPARK GIT FINAL/
│
├── model backend/
│   ├── Karnataka_Disaster_Realistic_Dataset.csv
│   ├── model.pkl
│   ├── requirements.txt
│   ├── run.py
│   ├── training.py
│
├── project file/
│   ├── venv/
│   ├── about.html
│   ├── app.py
│   ├── contact.html
│   ├── home.html
│   ├── index.html
│   ├── karthii.jpg
│   ├── profile.html
│   ├── rakshii.jpg
│   ├── requirements.txt
│   ├── signin.html
│   ├── try.html
│   ├── user.html
│
└── README.md


▶️ How to Run (Frontend)
Go to the project file/ directory

Install dependencies:
pip install -r requirements.txt


Start the frontend Flask server:
python app.py


Open http://127.0.0.1:5000 in your browser

The interface will guide you through:
Start Screen → About → Login → Home Dashboard

✔ The frontend runs independently.
✔ The model backend folder contains the training code, dataset, and model.
✔ It is kept separate and is not required for demo execution.

🔍 Core Features (Short & Clear)
--->Live Map & Location Detection
--->Uses HTML5 Geolocation API
--->Automatically marks the user’s live position
--->Highlights safe points around the user
--->Built using Leaflet.js for lightweight map rendering
--->Real-Time Hazard Monitoring

Flask backend continuously provides:
--->Flood levels
--->Rainfall parameters
--->Air quality indicators
--->Frontend updates the UI every few seconds
--->🚨 Instant Emergency Alerts

When a threshold is crossed:
--->A fullscreen alert appears on the page
--->A route to the nearest safe point is drawn
--->An automated Gmail alert is sent to registered contacts

🤖 Disaster Prediction Model (Internal)

Stored in model backend/
Trained on Karnataka disaster dataset
Predicts the most likely hazard for the user’s region
Supports risk-based decision-making

🛡️ What AlertMate Provides
Real-time awareness of environmental conditions
Quick access to safety guidance
Reliable early warnings
A clean, futuristic UI for easier decision-making

📌 Note for Reviewers / Judges
The project file/ folder contains the runnable prototype
The model backend/ folder holds the ML workflow
The system is modular: frontend, server, and model are separate
Designed for practicality + hackathon demonstration