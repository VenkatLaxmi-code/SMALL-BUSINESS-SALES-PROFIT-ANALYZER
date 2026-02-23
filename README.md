# 🚀 Small Business Sales & Profit Analyzer  
### 🤖 AI-Powered Restaurant Management System

![Python](https://img.shields.io/badge/Python-3.11+-blue?logo=python)
![Flask](https://img.shields.io/badge/Flask-Web_Framework-black?logo=flask)
![Machine Learning](https://img.shields.io/badge/Machine_Learning-Scikit--Learn-orange?logo=scikit-learn)
![OpenAI](https://img.shields.io/badge/OpenAI-API-green?logo=openai)
![Chart.js](https://img.shields.io/badge/Charts-Chart.js-red?logo=chartdotjs)
![Bootstrap](https://img.shields.io/badge/UI-Bootstrap-purple?logo=bootstrap)
![JWT](https://img.shields.io/badge/Auth-JWT-yellow?logo=jsonwebtokens)
![Deployment](https://img.shields.io/badge/Deployment-Render-46E3B7?logo=render)
![License](https://img.shields.io/badge/License-MIT-brightgreen)

---

## 🌐 Live Demo

🔗 **Live Website:**  
https://small-business-sales-profit-analyzer-live.onrender.com

---

# 📊 Overview

Small Business Sales & Profit Analyzer is a full-stack AI-powered web application designed for restaurants and small businesses to:

- 📈 Track Sales & Expenses
- 📊 Analyze Profit & Loss
- 🤖 Generate AI Business Forecasts
- 📄 Send Automated Management Reports
- 🔐 Manage Role-Based Users

This system combines **Flask backend + Machine Learning + AI Forecasting + Cloud Deployment** into one production-ready application.

---

# 🌟 Key Features

## 👑 Owner Dashboard
- Real-time Profit & Loss Analytics
- Monthly & Yearly AI Forecast
- AI Profit Forecast (Next 7 Days)
- Dynamic Graph Visualizations
- Email-based Management Reports
- Business Name Editing
- Custom Color Theme Support

---

## 👨‍🍳 Staff Dashboard
- Take Orders (Auto Inventory Update)
- Dynamic “Today’s Sales” Graph
- Item-wise Daily Sales Analysis
- Real-Time Inventory Updates

---

## 💼 Accountant Dashboard
- Add / Edit / Delete Transactions
- Income & Expense Tracking
- Paginated Transaction Table (10 rows per page)
- CSV Export
- Search & Filter Options

---

## 🤖 AI Analysis Module
- 📈 Monthly Revenue Prediction
- 📉 Monthly Expense Prediction
- 💰 Predicted Net Profit
- 📆 Yearly Profit Forecast
- 📊 3-Line Revenue/Expense/Net Graph
- 💡 Smart AI Business Suggestions

---

# 🧠 Machine Learning Implementation

Used **Linear Regression (Scikit-Learn)** to:

- Predict Monthly Profit Trends
- Predict Yearly Growth
- Forecast Next 7 Days Revenue
- Generate Advanced Business Insights

---

# 🛠 Tech Stack

### 🔹 Backend
- Python
- Flask
- Flask-Mail
- PyJWT
- OpenAI API
- Scikit-Learn

### 🔹 Frontend
- HTML5
- CSS3
- Bootstrap 5
- JavaScript
- Chart.js

### 🔹 Database
- CSV-Based Lightweight Storage

### 🔹 Deployment
- Render (Cloud Hosting)
- Gunicorn

---

# 🔐 Authentication & Security

- Role-Based Access Control
  - Owner
  - Staff
  - Accountant
- JWT Token Authentication
- Secure Environment Variables
- Gmail SMTP Integration (App Password Based)

---

# 📁 Project Structure

```
restaurant_management/
│
├── app.py
├── requirements.txt
├── users.csv
├── sales.csv
├── inventory.csv
│
├── templates/
│   ├── base.html
│   ├── owner_dashboard.html
│   ├── staff_dashboard.html
│   ├── accountant_dashboard.html
│   ├── ai_analysis.html
│
├── static/
│   ├── css/
│   ├── js/
│
└── README.md
```

---

# 🔑 Environment Variables Required

Set these in Render:

```
OPENAI_API_KEY=your_openai_api_key
JWT_SECRET=your_super_secure_secret_key
MAIL_SERVER=smtp.gmail.com
MAIL_PORT=587
MAIL_USE_TLS=True
MAIL_USERNAME=your_email@gmail.com
MAIL_PASSWORD=your_gmail_app_password
MAIL_DEFAULT_SENDER=your_email@gmail.com
```

⚠ Gmail requires App Password (not your regular password).

---

# 🚀 Deployment Steps (Render)

1. Push project to GitHub  
2. Create Web Service in Render  
3. Connect Repository  
4. Build Command:
   ```
   pip install -r requirements.txt
   ```
5. Start Command:
   ```
   gunicorn app:app
   ```
6. Add Environment Variables  
7. Deploy 🎉  

---

# 📈 Screenshots

(You can add screenshots here later)

---

# 🎯 Future Improvements

- Replace CSV with PostgreSQL
- Add Background Job Queue
- Improve Forecasting with Advanced Models
- Multi-branch Business Support
- Mobile App Version

---

# 🏆 Project Highlights

✔ Full-Stack Development  
✔ AI Integration  
✔ Machine Learning Forecasting  
✔ Cloud Deployment  
✔ SMTP Email Automation  
✔ Role-Based Security  
✔ Production Debugging  

---

# 👨‍💻 Developed By

AI-Integrated Business Intelligence System for Small Businesses.

---

# 📜 License

This project is licensed under the MIT License.
