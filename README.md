Build a mini full-stack app that fetches temperature data from an online sensor or open API, stores it, and displays it in a web UI.

# 🌡️ IoT Temp Watch

A full-stack mini project that fetches real-time temperature data from an online sensor API and displays it on a simple dashboard.

> ⏱ This project is designed as a 2-day technical test for technician-level developers.

---

## 📌 Project Goal

Build a small IoT-enabled web app that:
- Retrieves temperature or humidity data from a public sensor API
- Stores and exposes the data via a backend service
- Displays the data in real time or at regular intervals via a frontend interface

---

## ⚙️ Stack Suggestions

### Backend
-Spring Boot ( **JHipster**)
  or  
- Python with Flask or FastAPI

### Frontend
- React (preferred).

### Optional
- WebSocket for real-time updates
- SQLite or local JSON for persistence
- Docker/Docker Compose
- GitHub Actions CI
- <iframe width="1038" height="584" src="https://www.youtube.com/embed/yzeVMecydCE" title="Complete Guide to Open Source - How to Contribute" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

---
## 🌐 Data Source

Use one of the following free/public sensor APIs:
- [Open-Meteo API](https://open-meteo.com/en/docs)
- [ThingSpeak](https://thingspeak.com/)
- Any dummy IoT API or mock sensor server
---

## 📁 Project Structure (recommended)

iot-temp-watch/
├── backend/
│  
├── frontend/
│   └── index.html / ReactApp/
├── data/
│   └── history.json
├── .github/
│   └── workflows/ (CI if any)
├── docker-compose.yml (optional)
├── README.md
└── LICENSE


## ✅ What You’ll Be Assessed On

| Category        | Details                                                                 |
|----------------|-------------------------------------------------------------------------|
|----------------|  Figma design
| 🏗 Project Setup | Proper use of JHipster to scaffold and configure the app               |
| 🔒 Authentication | Secure login system using JWT and protected API routes                  |
| 💻 Frontend       | Functional React UI to manage employees with proper state handling     |
| 📦 API Usage      | Clean and secure usage of RESTful APIs                                 |
| 🧼 Code Quality   | Maintainable, modular, and readable code                               |
| 🔁 Git Practices  | Use of Git flow, meaningful commit messages, and clean pull requests   |

## Evaluation Criteria
<img width="660" alt="image" src="https://github.com/user-attachments/assets/5a597b9d-b301-4867-a4b7-23b3029b1561" />
