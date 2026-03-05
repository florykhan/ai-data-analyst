# AI DataLab — API Reference

*(To be expanded with request/response schemas and examples.)*

## Dataset

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST   | `/datasets/upload`       | Upload dataset (CSV, JSON, Excel). |
| GET    | `/datasets/{id}/summary` | Profiling statistics for a dataset. |

## Models

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST   | `/models/train`   | Train ML model (regression, classification, clustering). |
| POST   | `/models/predict` | Get predictions for input data. |

## Chat

| Method | Endpoint   | Description |
|--------|------------|-------------|
| POST   | `/chat/query` | Natural language query (SQL/code generation, visualizations). |

See main [README](../README.md) for feature details.
