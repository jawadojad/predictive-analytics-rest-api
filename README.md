# Predictive Analytics REST API 📈 (In Progress)

FastAPI-based REST API for predictive analytics and anomaly detection. Deployed on Cloud Run (free tier), with OpenAPI documentation and Postman collection.

## Status
🟡 In Progress – core endpoints (`/health`, `/predict`) implemented. Cloud Run CI deploy workflow included.

## Tech Stack
- Python (FastAPI, Uvicorn, NumPy, Pydantic)
- Google Cloud Run (free tier)
- GitHub Actions (CI/CD)
- OpenAPI + Postman collection

## Endpoints
- `GET /health` → service liveness
- `POST /predict` → returns forecast & anomaly flags
- `GET /openapi.json` → OpenAPI docs

## Roadmap
- [ ] Implement rolling z-score anomaly detection (done ✅ basic)
- [ ] Deploy to Cloud Run via GitHub Actions
- [ ] Add simple time-series predictive model
- [ ] Add monitoring hooks (Stackdriver/Prometheus)

## License
MITAPCAHE