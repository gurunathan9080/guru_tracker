# 💰 Personal Finance Tracker & Budget Planner

A simple yet powerful **Personal Finance Tracker** built with **Streamlit**, **Pandas**, **NumPy**, and **Plotly**.  
It helps you track income, expenses, savings, and visualize your financial health with interactive charts.  
Integrated with **Google Generative AI (Gemini API)** for **smart financial insights** and suggestions.

---

## 🚀 Features
- 📊 Track **income and expenses** with categories & dates  
- 💸 Calculate **balance, total income, total expenses**  
- 📈 Interactive **charts & visualizations** (Plotly)  
- 🧠 AI-powered **financial assistant** using Google Generative AI  
- ⏰ Supports **daily, weekly, and monthly tracking**  
- 💾 Data stored locally (CSV) for persistence  

---

## 🗂️ Project Structure
personal_finance_tracker/
├── app.py # Main Streamlit app
├── requirements.txt # Dependencies
├── data/ # Folder for storing CSV files
│ └── transactions.csv
├── .gitignore # Ignore venv, pycache, secrets, etc.
├── README.md # Project documentation


## Install dependencies
pip install -r requirements.txt

Configure API Key (for AI assistant)

## Create a .streamlit/secrets.toml file:

[general]
GOOGLE_API_KEY = "your_google_gemini_api_key_here"

## Run the app
streamlit run app.py

📊 Usage

Enter income & expense transactions with categories (e.g., food, bills, salary).

View summary statistics and interactive charts.

Ask the AI Assistant for budgeting tips and financial insights.

Export your transactions as CSV for later use.

🔑 Example Transactions
Date	Category	Type	Amount	Notes
2025-09-01	Salary	Income	50000	Monthly salary
2025-09-02	Groceries	Expense	1500	Supermarket
2025-09-03	Rent	Expense	12000	Apartmen

)

🖥️ Deployment

Deploy on Streamlit Cloud

Push your code to GitHub

Go to Streamlit Cloud

Connect your GitHub repo

Add your GEMINI_API_KEY in Secrets Manager

Deploy 🚀
