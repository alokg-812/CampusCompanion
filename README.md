# 📱 CampusCompanion

## 🚀 Overview

CampusCompanion solves the recurring issue of scattered information and manual campus workflows. It centralizes all essential services—mess menu, timetable, complaints, events, and study resources—into a single digital platform accessible via mobile app (students) and web dashboard (admins).


## 🎯 Key Features

### **Core (MVP)**

* **📅 Timetable & Alerts**
  Auto-updated class schedule with reminder notifications.

* **🍽 Mess Menu & Ratings**
  Daily meal information with thumbs-up/down feedback and weekly insights for mess admin.

* **🛠 Hostel Complaint System**
  Raise, track, and resolve issues (Water, fan, WiFi, etc.) with status flow: *Raised → Assigned → Resolved*.

* **📚 Study Resources Hub**
  Upload, filter, and search notes by subject, teacher, or unit.

### **Additional (Good-to-have)**

* **🚍 Live Bus Tracking (Geo-based)**
  Track campus shuttle/bus real-time (GPS + optionally RFID).

* **🎉 Events & Clubs**
  Explore campus activities, fest updates, and register instantly.

* **📦 Lost & Found Board**
  Upload items found on campus with location & contact details.

## 🧱 System Architecture (High-Level)

```
Frontend (React / Flutter / Web)  
       ↓  
Backend API (Node.js / Django / Firebase)  
       ↓  
Database (MongoDB / PostgreSQL / Firestore)  
       ↓  
Admin Dashboard (Web)
```

Optional integrations:

* Firebase Auth
* Cloud Storage (notes/resources)
* Push Notifications

## 👥 User Roles

### **Students**

* Login & profile
* View upcoming classes
* Track attendance
* Download class notes
* Raise hostel complaints
* View mess menu
* Join events & clubs

### **Faculty / Admin**

* Upload notes
* Update timetable
* Update mess menu
* Approve complaints
* Publish notices

### **Hostel Warden**

* View all complaints
* Assign maintenance staff
* Update ticket status

## 🛠 Tech Stack Options

* React.js (Web)
* React Native (App)
* Node.js + Express
* MongoDB Atlas

## 🗂 Project Structure (Suggested)

```
CampusCompanion/
│
├── backend/          # API + business logic
├── web-dashboard/    # Admin portal
├── mobile-app/       # Student mobile app
├── docs/             # PRD, Wireframes, API schemas
└── README.md
```

## 📅 Project Timeline

**Start:** 24 Nov 2025
**End:** 28 Feb 2026

| Week | Milestone                    |
| ---- | ---------------------------- |
| 1    | PRD + Wireframes             |
| 2    | Database Schema              |
| 3    | Auth + User Roles            |
| 4    | Timetable Module             |
| 5    | Mess Menu System             |
| 6    | Hostel Complaint System      |
| 7    | Events & Clubs               |
| 8    | Study Resources              |
| 9    | Lost & Found                 |
| 10   | Bus Tracking + QR Attendance |
| 11   | Integration                  |
| 12   | Testing                      |
| 13   | UI Polish                    |
| 14   | Deployment                   |

## 🧪 Internal Evaluation Strategy

* Weekly Git commits
* Mentor summaries
* Burndown chart / Trello board
* Task-based progress tracking

## 🎥 Live Demo Plan

The demo will showcase:

* App login
* Auto-refresh timetable
* Raising a hostel complaint
* Admin approving the ticket
* Mess menu rating
* Downloading study notes

## 🤝 Team Roles

* **Frontend Developer:** App + UI
* **Backend Developer:** APIs + DB
* **Product Lead:** Documentation, testing, UX
