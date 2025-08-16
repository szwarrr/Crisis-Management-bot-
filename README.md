
# 🚨 Crisis Management Bot
An **AI-powered bot** designed to assist organizations during crises by providing **real-time decision support, automated alerts, and actionable insights**.
The bot integrates with various data sources (ERP, CCTV, GIS, IoT) to ensure fast and informed responses.

---

## 🌟 Features

* 📡 **Real-time Data Integration** – Collects inputs from ERP, CCTV feeds, GIS maps, and IoT sensors.
* 🤖 **AI-Powered Decision Making** – Uses **LangChain**, **RAG**, and **LLMs** to analyze data.
* 🔔 **Crisis Alerts & Notifications** – Sends instant alerts to relevant stakeholders.
* 🗺️ **Interactive Dashboard** – Displays crisis details and recommendations.
* 📊 **Predictive Insights** – Uses ML models for forecasting and risk assessment.
* 🔒 **Role-based Access Control** – Ensures secure access to sensitive information.

## ⚙️ Installation

```bash
# Clone repository
git clone https://github.com/your-username/crisis-management-bot.git
cd crisis-management-bot

# Create virtual environment
python -m venv venv
source venv/bin/activate   # (Linux/Mac)
venv\Scripts\activate      # (Windows)

# Install dependencies
pip install -r requirements.txt
```

---

## 🚀 Usage

```bash
# Start backend server
uvicorn main:app --reload

# Access API at
http://127.0.0.1:8000/docs
```

1. Connect your **data sources** (ERP, CCTV, GIS, IoT).
2. Configure alert rules in `config.yaml`.
3. Monitor crisis events and get real-time recommendations.
