# NutriGuide – Full Stack Diet Recommendation App

NutriGuide is a full stack health and diet recommendation web application that allows users to sign up, log in, generate personalized diet reports, and save their report history securely.

## Live Demo
- Frontend: https://nutriguide-frontend-omega.vercel.app
- Backend API: https://nutriguide-backend-y2az.onrender.com

## Features
- User authentication with Supabase Auth
- Protected pages for logged-in users only
- Personalized diet report generation
- BMI, calorie target, protein goal, water intake, and daily steps calculation
- Health-aware advice based on user profile and health issue
- One-day sample meal plan generation
- Save reports to Supabase database
- View saved reports history
- View full report details
- Delete saved reports
- User dashboard with latest report summary

## Tech Stack
### Frontend
- Next.js
- TypeScript
- Tailwind CSS
- Vercel

### Backend
- FastAPI
- Python
- Render

### Database / Auth
- Supabase
- PostgreSQL
- Supabase Auth

## Project Structure
```text
nutriguide-app/
├── frontend/   # Next.js frontend
├── backend/    # FastAPI backend
└── README.md
