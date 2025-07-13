# KPA Backend API Assignment

## Tech Stack
- FastAPI
- PostgreSQL
- SQLAlchemy
- Pydantic

## Setup Instructions
1. Rename `.env.example` to `.env` and update DB credentials.
2. Install dependencies: `pip install -r requirements.txt`
3. Run the server: `uvicorn app.main:app --reload`
4. Test Swagger UI: `http://127.0.0.1:8000/docs`

## APIs Implemented
- POST `/api/forms/bogie-checksheet`
- POST `/api/forms/wheel-specifications`
