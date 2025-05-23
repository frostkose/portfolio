<h1 align="center">
  🎬 Netflix Stock Data Scraper & ML Trainer 📈
</h1>

<p align="center">
  <img src="https://media.giphy.com/media/f9k1tV7HyORcngKF8v/giphy.gif" width="300" />
</p>

<p align="center">
  <a href="https://www.python.org/"><img src="https://img.shields.io/badge/Python-3.9-blue?style=for-the-badge&logo=python&logoColor=white" /></a>
  <a href="#"><img src="https://img.shields.io/badge/Selenium-Automation-brightgreen?style=for-the-badge&logo=selenium&logoColor=white" /></a>
  <a href="#"><img src="https://img.shields.io/badge/Docker-Ready-blue?style=for-the-badge&logo=docker&logoColor=white" /></a>
</p>

---

# 📚 Project Overview

This project scrapes **Netflix stock historical data** 📈 from Yahoo Finance using **Selenium WebDriver**.  
It **cleans**, **visualizes**, and **saves** the data in an Excel file (`netflix_data.xlsx`).  
Later, this dataset can be **used to train Machine Learning models** for stock price prediction 🎯.

---

# 🛠️ Tech Stack

| Technology     
|:---------------
| Python         |
| Flask          | 
| Selenium       |
| Pandas         | 
| Matplotlib     |
| Openpyxl       |
| Docker         |

---

# 🚀 Quick Start

git clone https://github.com/your-username/netflix-stock-ml.git   
cd netflix-stock-ml  


# 📊 Features
____________________________________________________________________
✅ Scrape latest Netflix historical stock data  
✅ Save data automatically to netflix_data.xlsx  
✅ Generate a Closing Price vs. Date plot  
✅ Prepare clean dataset for ML training (future project)  
✅ Fully Dockerized for easy deployment 🚀  



# ✨ Future Improvements
_____________________________________________________________________
📈 Train Machine Learning models (Random Forest, LSTM) on the stock data  
📊 Build an interactive dashboard using Plotly Dash or Streamlit  
📦 Add database storage (Postgres, MongoDB) for historical data  
🔐 Secure endpoints (authentication)  
🌎 Deploy online using Render or AWS Lightsail  

## 📈 Model Performance

### 📊 Classification Report

| **Metric**      | **Class 0** | **Class 1** | **Macro Avg** | **Weighted Avg** |
|-----------------|-------------|-------------|---------------|------------------|
| **Precision**   | 0.96         | 0.82         | 0.89          | 0.91             |
| **Recall**      | 0.87         | 0.95         | 0.91          | 0.90             |
| **F1-Score**    | 0.92         | 0.88         | 0.90          | 0.90             |
| **Support**     | 31           | 19           | 50            | 50               |

🔵 **Overall Accuracy: 90%**

✅ Your Random Forest model achieves **strong and balanced results**:
- High **Precision** (good quality of positive predictions).
- High **Recall** (low false negatives).
- **F1-scores** around 90% show good stability between Precision and Recall.

