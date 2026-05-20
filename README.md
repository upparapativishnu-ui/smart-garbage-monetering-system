Smart Garbage Management System
📌 Project Overview

The Smart Garbage Management System is a web-based platform designed to help citizens report garbage issues and help municipal workers manage waste collection efficiently.

The system allows:

Citizens to report garbage with images and live location
Admin to monitor all garbage reports
Workers to track and update cleaning status
Live garbage map visualization
Smart dashboard analytics

This project is built using Flask, SQLite, HTML, Tailwind CSS, JavaScript, and Leaflet Maps.

🚀 Features
👤 User Features
Report garbage with image upload
Add live location coordinates
Submit garbage description
Real-time complaint submission
🧑‍💼 Admin Features
Secure admin login
View all garbage reports
Monitor garbage status
Live garbage map tracking
Update report status:
Pending
In Progress
Completed
👷 Worker Features
Worker OTP login
Live worker tracking
Active worker monitoring
Real-time location updates
🗺️ Map Features
OpenStreetMap integration
Live garbage markers
Interactive location tracking
🛠️ Technologies Used
| Technology   | Purpose           |
| ------------ | ----------------- |
| Flask        | Backend Framework |
| SQLite       | Database          |
| HTML/CSS     | Frontend          |
| Tailwind CSS | UI Design         |
| JavaScript   | Frontend Logic    |
| Leaflet.js   | Interactive Maps  |
| Gunicorn     | Deployment Server |
📂 Project Structure
smart-garbage-system/
│
├── app.py
├── requirements.txt
├── Procfile
├── smart_garbage.db
│
├── templates/
│   ├── index.html
│   ├── admin.html
│   ├── worker.html
│   ├── admin_login.html
│   └── worker_login.html
│
├── static/
│   └── uploads/
│
└── README.md
