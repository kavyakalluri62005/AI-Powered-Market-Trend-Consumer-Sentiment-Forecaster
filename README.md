# 🧠 AI-Powered Market Trend & Consumer Sentiment Forecaster

<div align="center">

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-222222?style=for-the-badge&logo=github&logoColor=white)
![Streamlit Cloud](https://img.shields.io/badge/Streamlit%20Cloud-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)

**An end-to-end AI platform that analyzes consumer sentiment, discovers trends, and delivers actionable insights in real time.**

[🌐 Live React Dashboard](https://gowthamreddy-dev.github.io/AI-Powered-Market-Trend-Consumer-Sentiment-Forecaster-/) • [🐍 Streamlit App](https://aipoweredmarkettrendandconsumersentimentforecaster.streamlit.app) • [📂 GitHub Repo](https://github.com/gowthamreddy-dev/AI-Powered-Market-Trend-Consumer-Sentiment-Forecaster-)

</div>

---

## 📌 Project Overview

Brands receive thousands of consumer reviews daily but struggle to analyze them at scale. This platform solves that by automating the entire pipeline — from raw data ingestion to a live deployed AI-powered dashboard.

**Built as a 7-week individual internship project by Gowtham Reddy.**

---

## ✨ Key Features

- 🤖 **AI Sentiment Analysis** — DistilBERT model with 97% confidence score
- 🏷️ **Topic Modeling** — BERTopic auto-discovers 8 consumer themes
- 🔍 **RAG Pipeline** — LangChain + FAISS + Groq LLaMA-3.3-70B for natural language Q&A
- 📊 **Interactive Dashboard** — 5-tab Streamlit app with Plotly visualizations
- 🚨 **Smart Alerts** — Auto-detects sentiment drops and spikes
- 📄 **Report Generation** — One-click PDF & Excel export
- 🔐 **Role-Based Login** — Admin & User authentication system
- 🌐 **React Frontend** — Beautiful dark green dashboard built in React
- ☁️ **Dual Deployment** — Streamlit Cloud + GitHub Pages

---

## 📊 Project Results

| Metric | Value |
|--------|-------|
| 📦 Total Reviews Processed | 568,454 |
| ✅ Positive Sentiment | 67.8% |
| 🤖 AI Confidence Score | 97% |
| 🏷️ Topics Discovered | 8 |
| 📅 Data Range | 2004 – 2012 |
| ☁️ Deployment | Live on Streamlit Cloud + GitHub Pages |

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| 📦 Data | Pandas, NumPy, Kaggle API |
| 🤖 AI Sentiment | HuggingFace Transformers (DistilBERT) |
| 🏷️ Topic Modeling | BERTopic, Sentence-Transformers |
| 🔍 RAG Pipeline | LangChain, FAISS, Groq LLaMA-3.3-70B |
| 📊 Dashboard | Streamlit, Plotly, WordCloud, Matplotlib |
| 📄 Reports | fpdf2 (PDF), openpyxl (Excel) |
| 🌐 Frontend | React, HTML5, CSS3 |
| ☁️ Deployment | GitHub Pages, Streamlit Cloud |
| 🔐 Auth | Streamlit Session State, Role-Based Access |

---

## 📁 Project Structure

```
📁 AI-Powered-Market-Trend-Consumer-Sentiment-Forecaster/
│
├── 🌐 index.html                    # React frontend (GitHub Pages)
├── 🐍 login.py                      # Login page (Streamlit)
├── 🐍 week6_integrated_app.py       # Main dashboard app
│
├── 📊 Week Scripts
│   ├── Week1_data_pipeline.py       # Data cleaning & processing
│   ├── Week2_sentiment_topics.py    # AI sentiment + BERTopic
│   ├── Week3_rag_pipeline.py        # RAG pipeline setup
│   ├── week4_dashboard.py           # Dashboard development
│   └── week5_alerts_reports.py      # Alerts & report generation
│
├── 📂 Data Files
│   ├── sample_reviews.csv           # 5,000-row AI sample
│   ├── sentiment_results.csv        # Sentiment analysis results
│   ├── topics_summary.csv           # BERTopic results
│   ├── rag_insights.csv             # RAG Q&A outputs
│   └── alerts_log.csv               # Detected alerts
│
├── 📄 requirements.txt              # Python dependencies
├── 🔒 .gitignore                    # Large files excluded
└── 📖 README.md                     # This file
```

---

## 🚀 Quick Start

### Option 1 — React Frontend (No Install Needed)
```bash
# Clone the repo
git clone https://github.com/gowthamreddy-dev/AI-Powered-Market-Trend-Consumer-Sentiment-Forecaster-.git
cd AI-Powered-Market-Trend-Consumer-Sentiment-Forecaster-

# Run with Python HTTP server
python -m http.server 8000

# Open in browser
# http://localhost:8000
```

### Option 2 — Streamlit Dashboard
```bash
# Install dependencies
pip install -r requirements.txt

# Run the app
streamlit run login.py
```

---

## 📦 Installation

```bash
# Clone repository
git clone https://github.com/gowthamreddy-dev/AI-Powered-Market-Trend-Consumer-Sentiment-Forecaster-.git
cd AI-Powered-Market-Trend-Consumer-Sentiment-Forecaster-

# Install all dependencies
pip install streamlit pandas numpy plotly matplotlib wordcloud
pip install transformers torch bertopic sentence-transformers
pip install langchain langchain-groq langchain-community langchain-huggingface
pip install faiss-cpu fpdf2 openpyxl
```

---

## 🔐 Login Credentials

| Role | Username | Password | Access |
|------|----------|----------|--------|
| 👑 Admin | `admin` | `admin123` | Full access — all tabs, reports, alerts |
| 👤 User | `user` | `user123` | Dashboard access |

---

## 📅 7-Week Development Journey

| Week | Milestone | Status |
|------|-----------|--------|
| Week 1 | Data Pipeline — 568K reviews cleaned & processed | ✅ Complete |
| Week 2 | AI Sentiment (97%) + BERTopic (8 topics discovered) | ✅ Complete |
| Week 3 | RAG Pipeline — LangChain + FAISS + Groq LLaMA | ✅ Complete |
| Week 4 | Interactive 5-tab Streamlit Dashboard | ✅ Complete |
| Week 5 | Alerts System + PDF & Excel Report Generation | ✅ Complete |
| Week 6 | Full Integration + Login + Role-Based Access | ✅ Complete |
| Week 7 | Deployment — Streamlit Cloud + GitHub Pages + React | ✅ Complete |

---

## 🌐 Live Deployments

| Platform | URL | Status |
|----------|-----|--------|
| 🌐 React Dashboard | [GitHub Pages](https://gowthamreddy-dev.github.io/AI-Powered-Market-Trend-Consumer-Sentiment-Forecaster-/) | ✅ Live |
| 🐍 Streamlit App | [Streamlit Cloud](https://aipoweredmarkettrendandconsumersentimentforecaster.streamlit.app) | ✅ Live |

---

## 📊 Dashboard Pages

| Page | Description |
|------|-------------|
| 📊 Overview | KPI cards, sentiment distribution, yearly trends, sample reviews table |
| 💬 Sentiment Analysis | Confidence score distribution, model details, star rating breakdown |
| 🏷️ Topic Modeling | 8 auto-discovered topics with keywords and frequency charts |
| 🤖 AI Insights | RAG-powered natural language Q&A using Groq LLaMA-3.3-70B |
| 🚨 Alerts & Reports | Live sentiment alerts, PDF & Excel one-click downloads |

---

## 🏷️ Discovered Consumer Topics

| Topic | Reviews | Top Keywords |
|-------|---------|-------------|
| 🍔 Food & Taste | 456 | taste, flavor, delicious, fresh |
| 📦 Product Quality | 423 | quality, value, recommend, best |
| 🚚 Shipping & Delivery | 251 | delivery, package, order, arrived |
| 🥗 Health & Nutrition | 247 | organic, natural, diet, healthy |
| ☕ Coffee & Beverages | 198 | coffee, tea, brew, blend |
| 🎧 Customer Service | 167 | service, support, return, refund |
| 💰 Price & Value | 142 | price, value, cheap, worth |
| 📫 Packaging | 121 | package, box, seal, container |

---

## 👨‍💻 About the Developer

| | |
|---|---|
| 👤 **Name** | Indla Venkata Gowtham Kumar Reddy |
| 🎓 **Role** | Internship Project |
| 💻 **GitHub** | [gowthamreddy-dev](https://github.com/gowthamreddy-dev) |
| 🛠️ **Built** | End-to-end | data to deployment |

---

## 📄 License

This project is for educational and internship purposes.

---

<div align="center">

**Built with ❤️ by Gowtham Reddy | Internship Project 2026**

⭐ Star this repo if you found it useful!

</div>
