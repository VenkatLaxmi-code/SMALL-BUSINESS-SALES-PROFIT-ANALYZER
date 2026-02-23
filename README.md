📊 Small Business Sales & Profit Analyzer
🚀 AI-Powered Restaurant Management System

A full-stack web application built with Flask, Machine Learning, and AI forecasting that helps restaurant and small business owners manage transactions, analyze profits, and generate intelligent business insights.

🔗 Live Demo:
https://small-business-sales-profit-analyzer-live.onrender.com

🌟 Features
👨‍💼 Owner Dashboard

📈 Real-time Sales & Profit Analytics

📊 Monthly & Yearly Profit-Loss Visualization

🤖 AI Business Forecast (Next 7 Days)

📉 AI Monthly & Yearly Predictions

📄 Downloadable & Email Management Reports

🎨 Custom Color Theme Support

🏢 Business Name Editing

👨‍🍳 Staff Dashboard

🛒 Take Orders (Inventory Auto Update)

📊 Dynamic Today's Sales Bar Chart

📦 Stock Management

⚡ Real-time Item-wise Sales Visualization

💰 Accountant Dashboard

📑 Add / Edit / Delete Transactions

📊 Income & Expense Tracking

📁 CSV Export

🔎 Search & Filter Transactions

📄 Paginated Transaction Table (10 rows per page)

🤖 AI Analysis Module

📈 AI Profit Forecast (Next 7 Days)

📊 Monthly Profit & Loss Prediction (Line Graph – Revenue, Expense, Net Profit)

📉 Yearly Profit & Loss Prediction

💡 Smart AI Business Suggestions

🔮 Predicted Revenue, Expense & Net Profit

🧠 Machine Learning Used

Linear Regression (Scikit-Learn) for:

Monthly Forecasting

Yearly Forecasting

Daily Profit Trends

🛠 Tech Stack
Backend

Python 3

Flask

Flask-Mail

PyJWT (Authentication)

OpenAI API

Scikit-learn

Frontend

HTML5

CSS3

Bootstrap 5

JavaScript

Chart.js

Database

CSV-based storage (Lightweight file-based system)

Deployment

Render (Cloud Deployment)

Gunicorn

📂 Project Structure
restaurant_management/
│
├── app.py
├── requirements.txt
├── Procfile
├── users.csv
├── sales.csv
├── inventory.csv
│
├── templates/
│   ├── base.html
│   ├── index.html
│   ├── login.html
│   ├── register.html
│   ├── owner_dashboard.html
│   ├── staff_dashboard.html
│   ├── accountant_dashboard.html
│   ├── ai_analysis.html
│   ├── all_transactions.html
│
├── static/
│   ├── css/
│   ├── js/
│
└── README.md
🔐 Environment Variables Required

Set these in Render:

OPENAI_API_KEY=your_openai_key
JWT_SECRET=your_super_secure_secret
MAIL_SERVER=smtp.gmail.com
MAIL_PORT=587
MAIL_USE_TLS=True
MAIL_USERNAME=your_email@gmail.com
MAIL_PASSWORD=your_gmail_app_password
MAIL_DEFAULT_SENDER=your_email@gmail.com

⚠ Gmail requires App Password, not normal password.

🚀 Deployment (Render)

Push code to GitHub

Create Web Service in Render

Connect GitHub repository

Build Command:

pip install -r requirements.txt

Start Command:

gunicorn app:app

Add Environment Variables

Deploy 🎉

🔒 Authentication System

Role-Based Access Control

Owner

Staff

Accountant

JWT Token Authentication

Secure Session Management

📊 Key Highlights

✔ AI Forecasting
✔ Dynamic Graphs
✔ Email Report Automation
✔ JWT Authentication
✔ Pagination & Filtering
✔ Professional UI/UX
✔ Cloud Deployment

🏆 Learning Outcomes

Full-Stack Web Development

Cloud Deployment

SMTP Email Integration

AI Integration

Machine Learning Forecasting

Role-Based Authentication

Production Debugging

📌 Future Improvements

Replace CSV with PostgreSQL

Add Background Task Queue (Celery)

Improve Forecasting Accuracy

Mobile App Version

Multi-Business Support

👨‍💻 Author

Developed as a complete AI-integrated Business Intelligence System.
