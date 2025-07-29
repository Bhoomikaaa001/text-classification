# text-classification
📌 Project Overview
The Text Remark Categorization project is an intelligent NLP pipeline designed to automate the classification of customer remarks in the energy sector. It focuses on accurately identifying categories such as supply-related issues, billing discrepancies, and time-sensitive complaints, while supporting multiple languages and providing actionable insights using supervised and unsupervised learning models.

This system transforms unstructured text feedback into categorized, interpretable data—helping utility companies improve service response, optimize operations, and enhance customer satisfaction.

🔄 Project Pipeline

📊 Flow Overview:
1.Labeled Data Preparation

2.Text Cleaning & Tokenization

3.Time-Aware Feature Extraction

4.Sentence Embedding via SentenceTransformer

5.Supervised Classification (Logistic Regression)

6.Unsupervised Clustering (KMeans + TF-IDF + Gemini AI)

7.Language Detection & Segregation

8.Semantic Column Merging

🧠 Functionalities:
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

1.sentence-transformers (MiniLM-L6-v2)

2.scikit-learn (LogisticRegression, TF-IDF, train/test split)

3.cuml, cudf for GPU-accelerated clustering

4.nltk, langdetect, re for preprocessing

5.google.generativeai (Gemini API)

Utilities: pandas, numpy, joblib, torch, os, time
🚀 Real-World Applications
⚡ Utility Sector Feedback Categorization

🎫 Automated Customer Ticket Triage

🧠 Issue Prioritization Based on Duration

📉 Billing Dispute Trend Analysis

🔧 Proactive Maintenance Alerts

📊 KPI Reporting & Compliance

📍 Region-Specific Outage Tracking

💡 Future Enhancements
Add support for non-English remark classification.

Incorporate sentiment analysis alongside categorization.

Integrate with real-time dashboards for live monitoring.

Extend cluster naming to support regional dialects.

