# Backend (FastAPI)

API, dataset processing, ML pipeline, and chat handling for AI DataLab.

## Structure

- `api/` — Route handlers and request/response schemas
- `services/` — Business logic (upload, profiling, chat)
- `models/` — DB/data models and schemas
- `ml_pipeline/` — Training, evaluation, prediction
- `data_processing/` — Ingestion, profiling, feature transforms

## Setup

```bash
python -m venv .venv
source .venv/bin/activate   # or .venv\Scripts\activate on Windows
pip install -r requirements.txt
```

## Run

```bash
uvicorn api.main:app --reload
```

*(Create `api/main.py` when you implement the app.)*
