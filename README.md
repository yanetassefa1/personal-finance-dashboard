# 💰 Personal Finance Dashboard

An AI-powered personal finance dashboard for tracking income, expenses, 
and savings with interactive data visualizations. Built with React, 
Django, and Chart.js.

## 🌐 Live Demo
[View Live Demo](your-deployed-link-here)

## 🤖 AI Feature — Spending Insights
Get AI-generated insights on your spending habits — Claude analyzes your 
transactions and gives personalized tips on where to save money.

## ✨ Features

### 📊 Dashboard & Analytics
- Monthly income vs expenses overview
- Spending breakdown by category (pie chart)
- Monthly trends over time (line chart)
- Savings rate tracker

### 💳 Transaction Management
- Add, edit, and delete transactions
- Categorize spending (food, rent, transport, entertainment, etc.)
- Filter transactions by date range and category
- Export transactions to CSV

### 🤖 AI Spending Insights
- Claude API analyzes your spending patterns
- Get personalized tips on where to cut back
- Monthly spending summary generated automatically

### 📈 Data Visualization
- Interactive charts built with Chart.js
- Color-coded spending categories
- Responsive charts that work on mobile and desktop

## 🛠️ Tech Stack

**Frontend**
- React
- Chart.js
- Tailwind CSS
- React Router DOM
- Axios

**Backend**
- Python
- Django
- Django REST Framework
- PostgreSQL

**AI**
- Claude API (Anthropic)
- Prompt Engineering

## 🚀 Getting Started
```bash
# Clone the repository
git clone https://github.com/yanetassefa1/personal-finance-dashboard

# Install frontend dependencies
cd frontend
npm install
npm run dev

# Install backend dependencies
cd backend
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

## 📁 Project Structure
```
personal-finance-dashboard/
├── frontend/           # React app
│   ├── src/
│   │   ├── components/ # Charts, TransactionForm, CategoryFilter
│   │   ├── pages/      # Dashboard, Transactions, Insights
│   │   └── services/   # API calls + Claude integration
└── backend/            # Django REST API
    ├── transactions/   # Transaction models + views
    └── insights/       # Claude API integration
```

## 📚 What I Learned
- Building interactive data visualizations with Chart.js
- Integrating the Claude API for AI-powered financial insights
- Designing a full-stack app with React and Django REST Framework
- Working with date ranges and filters in a REST API
- Exporting data to CSV from a Django backend

## 🚧 Status
Currently in development — code coming soon.

## 📫 Contact
- GitHub: [yanetassefa1](https://github.com/yanetassefa1)
- LinkedIn: your-linkedin-url-here
```

---

Once committed, add these:

**Topics:**
```
react
django
python
chartjs
claude-api
ai
finance
data-visualization
full-stack
postgresql
