# Health Symptom Tracker

A professional Streamlit web application for tracking health symptoms, analyzing patterns, and generating medical reports for BYOP submission.

## 🚀 Quick Start

```bash
pip install streamlit pandas plotly
streamlit run app.py
Open Local URL: http://localhost:8501. The app automatically creates symptoms.db.

✨ Features:
1. Log symptoms with severity (1-10), duration, and triggers
2. View all entries in interactive data table
3. Analyze patterns through charts and statistics
4. Export data as CSV for doctors
5. Multi-page navigation (Log/View/Analyze/Export)

Files
app.py (main)
database.py (SQLite)
models.py (data model)
services.py (logic)
pages/1_Log_Symptom.py
pages/2_View_Data.py
pages/3_Analysis.py
pages/4_Export.py

Tech
Streamlit | Pandas | Plotly | SQLite

## 📱 Live Demo Screenshots

### 1. Homepage Dashboard
![Homepage Screenshot](https://github.com/user-attachments/assets/e3f023be-8522-4a84-930a-84c6729a7aaf)

### 2. Log New Symptom
![Log Symptom Screenshot](https://github.com/user-attachments/assets/fa645088-8a31-4b22-8d9c-0a357da8346f)

### 3. Symptom Analysis Charts
![Charts Screenshot](https://github.com/user-attachments/assets/a97a46ba-6aef-441e-960b-b0004602618d)

### 4. Export Data
![Export Screenshot](https://github.com/user-attachments/assets/cc032c15-e5fb-4204-9aaf-ae75711b9a4c)

