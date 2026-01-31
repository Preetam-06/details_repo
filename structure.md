# 🚨 Disaster Weather Alert System
## Team Name: Debug Dominators

A prototype-level yet scalable Disaster Weather Alert System that provides real-time disaster and weather alerts to users based on their location. The system is designed with a clean frontend–backend separation and a structured PostgreSQL database for future scalability.

---

## 📌 Problem Statement
Natural disasters such as floods, cyclones, earthquakes, and heatwaves often cause heavy losses due to delayed or missing alerts. This project focuses on delivering early warnings, location-based alerts, and clear information to users so they can take preventive action.

---

## 🎯 Objectives
- Provide real-time disaster and weather alerts  
- Send location-based notifications to users  
- Display affected regions on a map  
- Design a modular system that can scale in future phases  

---

## 🛠️ Tech Stack

### Frontend
- React Native  
- JavaScript  
- Firebase (Push Notifications)

### Backend
- Node.js  
- Express.js  

### Database
- PostgreSQL  

---

## 📁 Project Structure

### Frontend (`frontend/src`)
- `screens/` – Home, Alerts, Map, Settings screens  
- `components/` – Reusable UI components  
- `services/` – API calls, notifications, location handling  
- `constants/` – Disaster types, colors  
- `utils/` – Helper functions  
- `App.js` – Application entry point  

### Backend (`backend/src`)
- `routes/` – API endpoints  
- `controllers/` – Request handling logic  
- `services/` – Business logic  
- `models/` – Database models  
- `config/` – Database configuration  
- `middlewares/` – Authentication middleware  
- `server.js` – Server entry point  

---

## 👥 Team Roles – Debug Dominators

### Team Leader
- Overall system architecture  
- Frontend–backend integration  
- API design and scalability planning  

### Frontend Developer
- React Native UI development  
- Map and alert screen implementation  
- User interaction handling  

### Backend Developer
- REST API development  
- Weather and disaster data processing  
- Notification trigger logic  

### Database Manager
- PostgreSQL schema design  
- Data integrity and indexing  
- Query optimization  

---

## 🔌 API Endpoints

### Alerts
- `GET /api/alerts` – Fetch all alerts  
- `GET /api/alerts/:region` – Fetch alerts by region  
- `POST /api/alerts` – Create a new alert  

### Weather
- `GET /api/weather/:location` – Fetch weather data  

### Users
- `POST /api/users/register` – Register user  
- `POST /api/users/login` – User login  

---

## 🗄️ Database Design (PostgreSQL)

### Users Table
- id (Primary Key)  
- name  
- email  
- password  
- location  

### Alerts Table
- id (Primary Key)  
- disaster_type  
- region  
- severity  
- description  
- created_at  

### Regions Table
- id (Primary Key)  
- name  
- latitude  
- longitude  

---

## 🔄 Application Flow
1. Backend fetches weather and disaster data from external APIs  
2. Data is processed and stored in PostgreSQL  
3. Alerts are generated based on severity  
4. Push notifications are sent to users  
5. Alerts and affected regions are displayed in the mobile app  

---

## 📈 Future Scope & Scalability
- Region-based alert subscriptions  
- Weather API caching for performance  
- Admin dashboard for authorities  
- Cloud deployment and load balancing  

---

## ✅ Project Status
Prototype-level implementation with a scalable architecture ready for future enhancements.

---

## 🏁 Conclusion
The Disaster Weather Alert System provides a strong foundation for real-time alerting with a modular, scalable frontend–backend design and structured database management.
