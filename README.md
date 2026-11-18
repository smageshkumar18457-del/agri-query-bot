# 🌱 AgriVoice — Agriculture Voice Advisory System

Voice-enabled RAG chatbot for agriculture advice with source citations.

## Local Setup

### Backend
```bash
cd backend && pip install -r requirements.txt
python build_index.py
uvicorn main:app --reload --port 8000
```

### Frontend
```bash
npm install && VITE_API_URL=http://localhost:8000 npm run dev
```

## Docker
```bash
docker-compose up --build
```
Frontend: http://localhost:3000 | Backend: http://localhost:8000

## Demo Queries
1. "How do I grow wheat?"
2. "Best fertilizer for maize?"
3. "How to prevent potato blight?"
4. "When should I plant rice?"
5. "Tomato irrigation best practices?"
6. "How do I test my soil fertility at home"
