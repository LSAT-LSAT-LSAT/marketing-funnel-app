# 🎓 Graduate Marketing Funnel Dashboard

This Streamlit app visualizes key metrics from the graduate admissions funnel, including marketing engagement, application patterns, and international breakdowns.

## 📊 Features

- Page 1: Marketing Funnel (Prospect → Enrolled)
- Page 2: Demographics & Modality
- Page 3: Domestic vs International Trends

## 🧾 Files

```
.
├── app.py                # Streamlit dashboard code
├── requirements.txt      # Dependencies
├── .gitignore            # Prevent real dataset from being pushed
├── sample_data.xlsx      # (placeholder file for schema reference)
└── README.md             # This file
```

## 🧪 Getting Started

1. Clone/download this repo
2. Install required Python packages:
```bash
pip install -r requirements.txt
```
3. Place your real data file as:
```bash
2025-2026 Grad Marketing Data.xlsx
```
4. Run locally:
```bash
streamlit run app.py
```

## 🚀 Deploy on Streamlit Cloud

1. Push this repo to GitHub
2. Go to https://streamlit.io/cloud
3. Select your repo and choose `app.py` as the entry point

## ⚠️ Privacy Note

🚫 Do **not** upload real student data to GitHub.  
This project includes a `.gitignore` to help protect sensitive files.
