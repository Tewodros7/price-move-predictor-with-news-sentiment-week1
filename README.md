# 📈 Predicting Price Moves with News Sentiment — Week 1 Challenge
This repository contains my submission for Week 1 of the 10 Academy Artificial Intelligence Mastery (AIM) program. The project aims to predict stock price movements by analyzing financial news sentiment alongside technical indicators, using a Python-based pipeline.

# 🎯 Project Objective
The goal is to assist Nova Financial Solutions in enhancing their predictive analytics by:

📰 Performing sentiment analysis on financial news headlines.

📊 Computing technical indicators using historical stock price data.

📈 Analyzing correlations between sentiment and stock price returns.

💡 Delivering data-driven investment insights based on observed patterns.

# ✅ Tasks & Deliverables
 **🔧 Task 1: Git & Environment Setup**
Initialized GitHub repository with a modular folder structure.

Created and activated a virtual Python environment.

Tracked project dependencies in requirements.txt.

Configured GitHub Actions for Continuous Integration (CI).

Set up branching workflow (main, task-1) with regular commits and pull requests.

**📊 Initial Exploratory Data Analysis (EDA):**

Distribution of headline lengths

Publisher activity trends

News volume over time

Topic modeling & named entity recognition (NER)

**📉 Task 2: Quantitative Analysis with PyNance**
Collected historical stock price data via yfinance.

Switched to PyNance from TA-Lib due to system dependency issues.

Computed key technical indicators:

Simple & Exponential Moving Averages (SMA/EMA)

Relative Strength Index (RSI)

Moving Average Convergence Divergence (MACD)

Visualized indicator trends vs. stock price movement (outputs/ folder).

Managed progress via task-2 branch and PRs.

**🧠 Task 3: Sentiment vs. Stock Movement Correlation**
Applied nltk to assign sentiment polarity scores to news headlines.

Aggregated daily sentiment scores and aligned with corresponding stock return data.

Calculated daily stock returns based on adjusted closing prices.

Merged sentiment and stock datasets by date and ticker.

Performed Pearson correlation analysis to evaluate relationships.

Created insightful visualizations (scatter plots, heatmaps) to illustrate findings.

# 🚀 Getting Started
**1️⃣ Clone the Repository**
git clone https://github.com/Tewodros7/price-move-predictor-with-news-sentiment-week1.git  
cd price-move-predictor-with-news-sentiment-week1  

**2️⃣ Set Up the Virtual Environment**
  **💻 macOS/Linux**
bash
Copy
Edit
python3 -m venv venv  
source venv/bin/activate  
  **🪟 Windows**
bash
Copy
Edit
python -m venv venv  
venv\Scripts\activate  
**3️⃣ Install Dependencies**
bash
Copy
Edit
pip install -r requirements.txt  
# 📂 Folder Structure
markdown
Copy
Edit
├── .vscode/  
│   └── settings.json  
├── .github/  
│   └── workflows/  
│       └── ci.yml  
├── notebooks/  
│   ├── __init__.py  
│   └── EDA.ipynb  
├── src/  
│   └── __init__.py  
├── scripts/  
│   ├── __init__.py  
│   └── README.md  
├── tests/  
│   └── __init__.py  
├── requirements.txt  
├── README.md  
├── .gitignore  
