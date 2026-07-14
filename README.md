# 🚦 RoadWatch Backend

<p align="center">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white"/>
  <img src="https://img.shields.io/badge/YOLOv8-111827?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/REST_API-02569B?style=for-the-badge"/>
</p>

<p align="center">
  <b>Backend API for RoadWatch — An AI-powered Road Safety Monitoring System</b>
</p>

---

## 📖 Overview

RoadWatch Backend powers the server-side infrastructure of the **RoadWatch** platform, an intelligent road safety solution designed to detect and manage road hazards using Artificial Intelligence and Computer Vision.

The backend provides secure REST APIs for communication between the frontend, AI models, and the database, enabling seamless reporting, processing, and retrieval of road safety information.

---

## ✨ Features

- 🚧 Road hazard reporting
- 📸 Image upload and processing
- 🤖 AI/ML model integration (YOLOv8)
- 📍 GPS location support
- 🛣️ Incident management APIs
- 📊 Detection result storage
- 🔐 Secure REST API architecture
- ⚡ FastAPI-based high-performance backend
- 🌐 CORS-enabled API services
- 📦 Modular project structure

---

## 🏗️ System Architecture

```text
Mobile / Web App
        │
        ▼
    FastAPI Backend
        │
 ┌──────┼────────┐
 │      │        │
 ▼      ▼        ▼
YOLOv8 Database REST APIs
 │
 ▼
Detection Results
```

---

## 🛠️ Tech Stack

| Category | Technologies |
|-----------|--------------|
| Language | Python |
| Framework | FastAPI |
| AI / ML | YOLOv8, OpenCV |
| API | REST |
| Database | SQLite / MySQL (Configurable) |
| Authentication | JWT (Future Enhancement) |
| Documentation | Swagger UI |
| Deployment | Railway / Render / Docker |

---

## 📂 Project Structure

```text
roadwatch-backend/
│
├── app/
│   ├── api/
│   ├── models/
│   ├── services/
│   ├── database/
│   ├── schemas/
│   ├── utils/
│   └── main.py
│
├── uploads/
├── models/
├── requirements.txt
├── .env
└── README.md
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/vmkrathish/roadwatch-backend.git

cd roadwatch-backend
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Environment

#### Windows

```bash
venv\Scripts\activate
```

#### macOS / Linux

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Server

```bash
uvicorn app.main:app --reload
```

or

```bash
python main.py
```

---

## 📚 API Documentation

Once the server is running:

### Swagger UI

```
http://127.0.0.1:8000/docs
```

### ReDoc

```
http://127.0.0.1:8000/redoc
```

---

## 📡 Core API Modules

- Health Check
- Hazard Detection
- Image Upload
- Incident Reports
- Location Services
- AI Prediction
- User Management (Future)
- Authentication (Future)

---

## 🤖 AI Integration

RoadWatch integrates Computer Vision models to automatically identify road hazards from uploaded images.

Supported detections include:

- 🕳️ Potholes
- 🚧 Road Damage
- 🚨 Obstacles
- ⚠️ Hazardous Road Conditions

---

## 🔒 Security

- Input validation
- Secure file uploads
- API exception handling
- CORS protection
- Environment-based configuration

---

## 🚀 Future Improvements

- JWT Authentication
- Role-Based Access Control
- PostgreSQL/MySQL Support
- Docker Deployment
- Cloud Storage Integration
- Live Camera Streaming
- Notification Service
- Analytics Dashboard
- CI/CD Pipeline

---

## 👨‍💻 Developer

**M K Rathish**

- 💼 Computer Science Engineering Student
- 🚀 Flutter Developer
- 🤖 AI/ML Enthusiast
- 🌱 Startup Founder — Get My Service (GMS)

### Connect

- GitHub: https://github.com/vmkrathish
- LinkedIn: https://linkedin.com/in/mk-rathish

---

## 📄 License

This project is intended for educational, research, and demonstration purposes.

Feel free to fork, explore, and contribute.
