# Smart Logistics MVP

**AI-Driven Smart Logistics & Supply-Chain Optimization Platform (Prototype)**

This is a **student-friendly prototype** of a logistics optimization system.  
It simulates IoT shipment updates, ingests them into a backend, predicts ETAs, and provides a dashboard + AI chatbot for queries.

## 🔹 Features
- IoT data simulator (Python script) generating shipment updates
- FastAPI backend for ingestion, storage, and analytics
- PostgreSQL for structured shipment data
- Simple ETA predictor (distance/speed)
- Qdrant + LLM chatbot (LangChain) for natural language queries
- Dashboard (table + charts) for monitoring
- Docker Compose for easy setup

## 🔹 Tech Stack
- **Backend:** FastAPI (Python 3.10+)
- **Database:** PostgreSQL
- **Vector DB:** Qdrant
- **AI/ML:** LangChain, OpenAI API (or Gemini)
- **Frontend:** React (or simple HTML/JS + Chart.js)
- **Deployment:** Docker, Docker Compose

##  Getting Started
1. Clone repo:
   git clone https://github.com/goswamivaishnavi/smart-logistics-mvp.git
   cd smart-logistics-mvp
2.   Run locally (API only):
   pip install -r requirements.txt
   uvicorn api.main:app --reload
3. Start full stack (with Docker Compose, coming soon):
     docker-compose up --build

