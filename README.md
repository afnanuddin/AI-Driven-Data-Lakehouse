# 🧠 AI-Driven Data Lakehouse for Product Review Intelligence

This project builds a **modern, AI-powered data lakehouse** that ingests and transforms large-scale e-commerce product reviews, generates NLP-based sentiment embeddings, and enables semantic search with FAISS.

## 🚀 Architecture
Raw Data → Airflow (Orchestration) → PySpark (Transform) → Delta Lake (Storage) → FAISS (Vector DB) → Streamlit (Dashboard)

## ⚙️ Tech Stack
- Orchestration: Apache Airflow
- Processing: PySpark
- Storage: Delta Lake on AWS S3
- AI/NLP: Hugging Face Transformers · TextBlob · FAISS
- Visualization: Streamlit
- Infrastructure: Docker (recommended for Airflow)

## 🧩 Key Features
- Automated **ETL pipelines** orchestrated by Airflow
- **PySpark transformations** for cleaning & aggregating raw reviews
- **Sentiment analysis + vector embeddings** via Hugging Face models
- **FAISS semantic search** for similar-product recommendations
- **Streamlit dashboard** for insights and sentiment trends

## 📁 Project Structure
```
AI-Driven-Data-Lakehouse/
 ├── dags/                   # Airflow DAGs
 ├── scripts/                # PySpark & ETL scripts
 ├── data/                   # Sample input/output data
 ├── app.py                  # Streamlit app (placeholder)
 ├── requirements.txt
 ├── architecture_diagram.png
 └── README.md
```

## 🧪 Quickstart
```bash
git clone https://github.com/<your-username>/AI-Driven-Data-Lakehouse.git
cd AI-Driven-Data-Lakehouse
pip install -r requirements.txt
streamlit run app.py
```

> ℹ️ Airflow is best run in Docker. We'll add the docker-compose setup later.

## 📜 License
MIT License © 2025 Afnan Uddin