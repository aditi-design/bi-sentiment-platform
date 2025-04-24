# 🧠 Business Intelligence & Sentiment Analysis Platform

An end-to-end web application that combines retail sales forecasting, sentiment analysis, and interactive dashboards using Machine Learning, Power BI, and Flask.

## 🚀 Features

- 📊 Retail Sales Dashboard with Forecasting (Power BI)
- 💬 Sentiment Analysis on Amazon Reviews (BERT)
- 🌐 Web App with User Login (Flask)
- 📥 Downloadable PDF/Excel Reports
- 🔄 Real-time Data API Integration (planned)
- ⚡ Streamlit Version for Quick Demo

## 🛠️ Tech Stack

- Python, Flask/Django, HTML/CSS, Bootstrap, JS
- NLP (Scikit-learn, BERT, NLTK, Transformers)
- Power BI for BI dashboards
- Pandas, NumPy, Matplotlib, Seaborn
- PostgreSQL/MySQL (optional for scalability)

## 📦 Setup Instructions

```bash
# 1. Clone the repo
git clone https://github.com/your-username/bi-sentiment-platform.git
cd bi-sentiment-platform

# 2. Install dependencies
pip install -r requirements.txt

# 3. Run the Flask app
python app.py

    4. Access the app at:
http://localhost:5000

📁 Folder Structure
project/
├── static/             # CSS, JS, images
├── templates/          # HTML templates
├── model/              # Saved ML model
├── dashboards/         # Power BI embeds
├── app.py              # Flask backend
├── sentiment_model.py  # ML code
├── requirements.txt
└── README.md

