# AI-Driven-Data-Lakehouse
AI-powered data lakehouse integrating Airflow · PySpark · Delta Lake · Hugging Face · AWS · Streamlit
# 🧠 AI-Driven Data Lakehouse for Product Review Intelligence  

This project builds a **modern, AI-powered data lakehouse** that ingests and transforms large-scale e-commerce product reviews, generates NLP-based sentiment embeddings, and enables semantic search with FAISS.

---

## 🚀 Architecture
Raw Data → Airflow (Orchestration) → PySpark (Transform) → Delta Lake (Storage) → FAISS (Vector DB) → Streamlit (Dashboard)

---

## ⚙️ Tech Stack
| Layer | Tools |
|-------|-------|
| Orchestration | Apache Airflow |
| Processing | PySpark |
| Storage | Delta Lake on AWS S3 |
| AI/NLP | Hugging Face Transformers · TextBlob · FAISS |
| Visualization | Streamlit |
| Infrastructure | Docker · AWS Lambda (optional) |

---

## 🧩 Key Features
- Automated **ETL pipelines** orchestrated by Airflow  
- **PySpark transformations** for cleaning & aggregating raw reviews  
- **Sentiment analysis + vector embeddings** via Hugging Face models  
- **FAISS semantic search** for similar-product recommendations  
- **Streamlit dashboard** for real-time insights and sentiment trends  

---

## 🧰 Project Structure
AI-Driven-Data-Lakehouse/
├── dags/ # Airflow DAGs
├── scripts/ # PySpark & ETL scripts
├── data/ # Sample input/output data
├── architecture_diagram.png
├── requirements.txt
└── README.md
