# Task-Manager
# Cyberpunk Task Manager (Full-Stack)
A high-performance Task Management system built with **FastAPI**, **SQLite**, and **React**.

## Features
- **FastAPI Backend:** High-speed asynchronous Python API.
- **Modern UI:** Black and Purple "Cyberpunk" aesthetic.
- **SQL Persistence:** Tasks are saved in a SQLite database.
- **Custom User Greeting:** Personalized name-entry modal.

## Setup Instructions

### Backend
1. `cd backend`
2. `python -m venv venv`
3. `source venv/bin/activate` (Windows: `venv\Scripts\activate`)
4. `pip install -r requirements.txt` (Note: Run `pip freeze > requirements.txt` before uploading)
5. `uvicorn main:app --reload`

### Frontend
1. `cd frontend`
2. `npm install`
3. `npm run dev`
