# AI DataLab — System Architecture

*(To be expanded.)*

## High-level flow

```
Frontend (React / Next.js)
        ↓
Backend API (FastAPI)
        ↓
AI Layer (LLM API)
        ↓
ML Pipeline
        ↓
Data Storage
        ↓
Cloud Infrastructure (AWS)
```

## Components

- **Frontend**: Dataset upload, dashboards, chat UI, visualizations (Plotly, Recharts, TailwindCSS).
- **Backend**: FastAPI — API, dataset processing, ML orchestration, chat handling, query generation.
- **ML**: scikit-learn, pandas, numpy, xgboost — training, evaluation, feature importance.
- **Data pipeline**: Ingestion → profiling → feature processing → training → evaluation → prediction API.
- **Cloud**: EC2 (compute), S3 (datasets & artifacts), PostgreSQL (metadata), CloudWatch (monitoring).

See main [README](../README.md) for full feature and stack details.
