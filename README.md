# DocScreen.ai — AI Identity Document Screening System

An AI-powered identity document verification and border checkpoint screening system built with **FastAPI**, **OpenCV**, and **EasyOCR**, paired with a modern web interface for real-time document inspection and validation.

🔗 **Live Application:** [https://doc-screen-ai.vercel.app/login](https://doc-screen-ai.vercel.app/login)

---

## 📌 Project Overview
Manual verification of identity documents at checkpoints and onboarding desks is time-consuming and vulnerable to human oversight. **DocScreen.ai** automates document screening by combining computer vision and optical character recognition (OCR) to extract identity fields, verify structural integrity, and flag anomalies through an interactive dashboard.

## ✨ Key Features
* **Secure User Authentication:** Role-based login portal protecting access to document screening tools and audit records.
* **Automated OCR Text Extraction:** Extracts key personal details (Name, Document Number, Date of Birth, Expiry Date) from uploaded identity documents using **EasyOCR**.
* **Computer Vision Preprocessing:** Uses **OpenCV** for image alignment, noise reduction, glare handling, and document boundary detection.
* **Database Logging & Audit Trail:** Stores verification records, confidence scores, and screening logs via structured SQL schemas.
* **Containerized & Cloud-Ready:** Includes Docker and deployment configurations (`Dockerfile`, `docker-compose.yml`, `render.yaml`, `vercel.json`) for seamless cloud hosting.

## 🛠️ Tech Stack
* **Backend:** Python, FastAPI
* **AI & Computer Vision:** OpenCV, EasyOCR
* **Frontend:** React / Modern Web UI (Deployed on Vercel)
* **Database:** SQL
* **DevOps & Deployment:** Docker, Docker Compose, Render, Vercel

## 📂 Repository Structure
```text
docScreen.ai/
├── backend/             # FastAPI server, OCR & OpenCV screening pipelines
├── frontend/            # Web dashboard and login interface
├── sql/                 # Database schemas and table definitions
├── Dockerfile           # Container configuration for backend deployment
├── docker-compose.yml   # Multi-container orchestration setup
├── requirements.txt     # Python dependencies
├── render.yaml          # Render cloud deployment configuration
└── vercel.json          # Vercel frontend routing and build settings
```

## 🚀 How to Run Locally

### 1. Clone the Repository
```bash
git clone https://github.com
cd YOUR_REPO_NAME
```

### 2. Backend Setup (FastAPI + OpenCV + EasyOCR)
```bash
cd backend
pip install -r ../requirements.txt
uvicorn main:app --reload
```

### 3. Frontend Setup
```bash
cd frontend
npm install
npm run dev
```
**Program:** B.Tech — Artificial Intelligence & Machine Learning (AIML)
