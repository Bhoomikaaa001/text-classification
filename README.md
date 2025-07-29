# text-classification
📌 Project Overview
The Text Remark Categorization project is an intelligent NLP pipeline designed to automate the classification of customer remarks in the energy sector. It focuses on accurately identifying categories such as supply-related issues, billing discrepancies, and time-sensitive complaints, while supporting multiple languages and providing actionable insights using supervised and unsupervised learning models.

This system transforms unstructured text feedback into categorized, interpretable data—helping utility companies improve service response, optimize operations, and enhance customer satisfaction.

🔄 Project Pipeline
📊 Flow Overview:
Labeled Data Preparation

Text Cleaning & Tokenization

Time-Aware Feature Extraction

Sentence Embedding via SentenceTransformer

Supervised Classification (Logistic Regression)

Unsupervised Clustering (KMeans + TF-IDF + Gemini AI)

Language Detection & Segregation

Semantic Column Merging

🧠 Functionalities
✅ Automated Categorization using a Logistic Regression classifier.

⏱️ Time-Aware Parsing for urgency detection in customer remarks.

🌐 Language Segregation (English vs. Others) using langdetect.

🧩 Remark Clustering for unsupervised discovery using cuml.KMeans.

🧠 AI-Powered Cluster Naming via Google Gemini.

🧼 Redundant Category Merging using semantic similarity and Gemini AI.

🚀 GPU Acceleration using RAPIDS (cudf, cuml) for large datasets.

💾 Model Persistence with joblib.

🧰 Tech Stack & Libraries
Language: Python

NLP & ML:

sentence-transformers (MiniLM-L6-v2)

scikit-learn (LogisticRegression, TF-IDF, train/test split)

cuml, cudf for GPU-accelerated clustering

nltk, langdetect, re for preprocessing

google.generativeai (Gemini API)

Utilities: pandas, numpy, joblib, torch, os, time
🚀 Real-World Applications
⚡ Utility Sector Feedback Categorization

🎫 Automated Customer Ticket Triage

🧠 Issue Prioritization Based on Duration

📉 Billing Dispute Trend Analysis

🔧 Proactive Maintenance Alerts

📊 KPI Reporting & Compliance

📍 Region-Specific Outage Tracking

🧪 Model Performance Metrics
Accuracy Score

Precision / Recall / F1-score (Per Category)

Cluster Cohesion (Unsupervised Groupings)

💡 Future Enhancements
Add support for non-English remark classification.

Incorporate sentiment analysis alongside categorization.

Integrate with real-time dashboards for live monitoring.

Extend cluster naming to support regional dialects.

