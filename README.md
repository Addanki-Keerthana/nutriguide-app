# 🥗 NutriGuide – Full Stack Diet Recommendation App

A full-stack health-tech web application that generates personalized diet plans based on user health profiles. Users can sign up, log in, generate reports, and manage their report history securely.

---

## 🌐 Live Demo

- 🚀 Frontend: https://nutriguide-frontend-omega.vercel.app  
- ⚙️ Backend API: https://nutriguide-backend-y2az.onrender.com  
- 📘 API Docs: https://nutriguide-backend-y2az.onrender.com/docs  

---

## ✨ Features

- 🔐 User Authentication (Signup/Login/Logout)
- 🛡️ Protected Routes for authenticated users
- 🧠 Personalized Diet Report Generation
- 📊 BMI, Calorie, Protein, Water & Steps Calculation
- 🍽️ One-Day Sample Meal Plan
- ❤️ Health Condition-Based Recommendations
- 💾 Save Reports to Database
- 📂 View Saved Reports History
- 🔍 Detailed Report View
- ❌ Delete Reports
- 📊 Dashboard with Latest Report Summary

---

## 🏗️ Architecture

Frontend (Next.js) → Backend API (FastAPI) → Supabase (Database + Auth)

- Next.js handles UI and user interaction  
- FastAPI processes health data and generates reports  
- Supabase manages authentication and persistent storage  

---

## 🛠️ Tech Stack

### Frontend
- Next.js
- TypeScript
- Tailwind CSS
- Vercel

### Backend
- FastAPI
- Python
- Uvicorn
- Render

### Database & Auth
- Supabase
- PostgreSQL
- Supabase Auth

---

## 📁 Project Structure

```text
diet-app/
├── frontend/        # Next.js frontend
├── backend/         # FastAPI backend
├── screenshots/     # App screenshots
└── README.md
