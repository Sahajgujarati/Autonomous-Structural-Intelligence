# 🏗️ PS2: Autonomous Structural Intelligence

![Hackathon Build](https://img.shields.io/badge/Hackathon-Build_Live-818cf8?style=for-the-badge)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Three.js](https://img.shields.io/badge/ThreeJs-black?style=for-the-badge&logo=three.js&logoColor=white)

An advanced AI-powered pipeline that instantly converts 2D architectural floor plans into interactive 3D models and performs autonomous structural analysis. Built to bridge the gap between flat blueprints and actionable structural intelligence.

## ✨ Key Features

* **Computer Vision Parsing:** Utilizes OpenCV and Hough Line Transform to mathematically extract walls, doors, and windows from raw pixels.
* **Autonomous 3D Generation:** Dynamically extrudes 2D coordinate data into a fully interactive 3D scene using Three.js.
* **Intelligent Material Recommendation:** AI-driven analysis to recommend structural materials (Load-bearing vs. Partition) based on spatial requirements.
* **Structural Concern Detection:** Automatically identifies potential architectural flaws or structural weaknesses in the provided blueprint.

## 🛠️ Tech Stack

**Frontend:**
* React (Vite)
* Three.js (WebGL 3D Rendering)
* Glassmorphism UI / Modern CSS

**Backend:**
* Python 3.14 / FastAPI
* OpenCV (Image Processing & Geometry)
* Pytesseract (OCR for Room Labels)
* LLM Integration (Claude/OpenAI Vision & Logic)

---

## 🚀 How to Run Locally

Follow these steps to spin up the project on your local machine.

### 1. Backend Setup
Navigate to the backend directory and install the Python dependencies:
```bash
cd backend
pip install -r requirements.txt