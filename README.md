# chem-mlops-pipeline
🧪🧠⚙️🚀  End-to-end MLOps framework for chemical engineering models.

🧪 – chemical engineering data
🧠 – intelligent ML models
⚙️ – automated pipelines and infrastructure
🚀 – deployment, scalability, and production-readiness

## 📌 Features
- ETL pipeline for experimental and simulated thermo/control data
- Model training with MLflow tracking
- FastAPI inference service
- Dockerfile for containerized deployment
- GitHub Actions for CI/CD

## 🚀 Run
### API
```bash
python -m venv .venv && . .venv/Scripts/activate
pip install -r requirements.txt
uvicorn inference.api:app --reload
