# Story Generator

A full-stack web application that generates interactive stories using AI.

## Tech Stack

**Frontend**
- React
- Vite

**Backend**
- Python
- FastAPI
- SQLite
- OpenAI API

## Project Structure
story-generator/
├── backend/
└── frontend/


## Backend Setup

cd backend
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate

pip install -r requirements.txt

Create backend/.env

OPENAI_API_KEY=your_api_key_here

uvicorn main:app --reload

##Frontend Setup
cd frontend
npm install
npm run dev


