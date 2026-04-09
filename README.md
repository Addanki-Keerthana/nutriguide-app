# 🥗 NutriGuide – Full Stack Diet Recommendation App (V2)

NutriGuide is a comprehensive health-tech application designed to provide personalized nutritional guidance. Version 2 introduces a modernized "Emerald" UI, enhanced dashboard analytics, and a curated library of sample and saved recipes.

---

## 🌐 Live Deployment

- **🚀 Frontend:** [https://nutriguide-app.vercel.app](https://nutriguide-app.vercel.app)
- **⚙️ Backend API:** [https://nutriguide-backend-y2az.onrender.com](https://nutriguide-backend-y2az.onrender.com)
- **📘 API Docs:** [https://nutriguide-backend-y2az.onrender.com/docs](https://nutriguide-backend-y2az.onrender.com/docs)

---

## ✨ New in V2
- **📊 Advanced Dashboard:** Real-time sync with Supabase to track total health assessments and latest BMI/Calorie metrics.
- **🍳 Recipe Engine:** Browse "Sample Recipes" and maintain a personal "Saved Recipes" kitchen.
- **🎨 Modernized UI:** Clean, high-contrast Emerald theme with improved accessibility and mobile responsiveness.
- **🛡️ Enhanced Auth:** Streamlined login/signup flow with improved session persistence.

## 🛠️ Core Features
- 🔐 **Secure Authentication:** Supabase-powered Signup, Login, and protected user sessions.
- 🧠 **Smart Reports:** AI-driven calculations for BMI, Calories, Protein, and Water intake.
- 🍽️ **Meal Planning:** Daily meal suggestions based on unique health profiles (Underweight, Healthy, Overweight, Obese).
- 💾 **Cloud Storage:** Save and manage history; View, Delete, or Analyze past reports instantly.

---

## 🏗️ Technical Architecture



- **Frontend:** Next.js (App Router), TypeScript, Tailwind CSS.
- **Backend:** FastAPI (Python), Uvicorn, Render.
- **Database/Auth:** Supabase (PostgreSQL), Supabase Auth.

---


## 🚀 Local Setup

### Frontend
- cd frontend

- npm install

- npm run dev

### Backend
- cd backend

- pip install -r requirements.txt

- uvicorn main:app --reload

---

## 📁 Project Structure

```text
nutriguide-app/
├── frontend/        # Next.js Application (Root for Vercel)
├── backend/         # FastAPI Application (Root for Render)
├── screenshots/     # UI Previews and Documentation
└── README.md        # Project Overview
