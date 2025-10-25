Anomalyzed Sentinel

AI-Powered Cyber Threat Detection, User Monitoring, and Security Intelligence Dashboard

# Overview
Anomalyzed Sentinel is an integrated cybersecurity and data analytics dashboard built with Streamlit, designed to simulate and visualize AI-driven anomaly detection, phishing detection, insider threat analysis, and global cyberattack monitoring — all within a single modular interface.
It serves as both an educational tool and a demonstration platform for applied cybersecurity, data security analytics, and system intelligence.

# Key Features
 User Authentication System
Secure login, registration, and admin control with bcrypt password hashing and SQLite database.
 AI Threat Engine
Upload CSV or TXT files and run anomaly detection on numeric datasets.
 Email Protection Module
Scans email text for phishing keywords and suspicious phrases.
 Order Integrity Checker
Generates SHA-256 hashes to verify data or order authenticity.
 Network Monitor & Insider Threats
Simulates live network logs and detects suspicious activities like failed logins or port scans.
 Vulnerability Scanner
Uploads software lists and detects deprecated or outdated software entries.
 Global Cyberattack Maps
Embeds real-time live threat maps from Fortinet, Bitdefender, and MITRE ATT&CK.

# System Modules
Module	Description
AI Threat Engine	Detect anomalies from uploaded data
Email Protection	Identify phishing attempts
Order Integrity	Verify transaction or order authenticity
Network Monitor	Simulate network events and find suspicious activity
Insider Threats	Detect abnormal user behavior patterns
Vulnerability Scanner	Identify deprecated software
Global Live Attack	View real-time cyberattack threat maps
Admin Panel	Manage users and logs (future development)
# Tech Stack
Category	Technology
Frontend / Dashboard	Streamlit
Database	SQLite
Security & Auth	bcrypt, hashlib
AI & Analysis	pandas, scikit-learn
Visualization	Streamlit Components, Plotly, Matplotlib
Backend Utilities	EmailMessage, smtplib, json, re
# Installation
Step 1: Clone the Repository
git clone https://github.com/yourusername/Anomalyzed-Sentinel.git
cd Anomalyzed-Sentinel
Step 2: Install Dependencies
pip install -r requirements.txt
Step 3: Run the Application
streamlit run app.py

# Project Structure
Anomalyzed-Sentinel/
│
├── app.py                  # Main Streamlit application
├── users.db                # Auto-generated SQLite database
├── requirements.txt        # Dependencies
├── README.md               # Project documentation
└── /data                   # Optional: data uploads/logs

# Example Screenshots
Module	Preview
Dashboard	

Threat Map	



# Contributing

Contributions are welcome!
If you’d like to enhance a module or add new cybersecurity features:
Fork the repository
Create a new branch (feature/your-feature)
Commit changes and push
Submit a pull request

# License
This project is licensed under the MIT License.
You are free to use, modify, and distribute it with proper credit.

# Author

Developed by: Isaack Mutembei Sani
Role: Cybersecurity Student & Applied Statistician
LinkedIn: www.linkedin.com/in/isaack-sani-b88aa8387

GitHub:
