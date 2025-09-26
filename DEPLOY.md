# Deployment Guide - Elevate Professional Cleaners

## 📋 Exact Deployment Information

### Backend (Render)
- **Folder Path**: ./backend
- **Start Command**: uvicorn server:app --host 0.0.0.0 --port $PORT
- **Build Command**: pip install -r requirements.txt

### Frontend (Vercel)  
- **Folder Path**: ./frontend
- **Build Command**: yarn build
- **Output Directory**: build
