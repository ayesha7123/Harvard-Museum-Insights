# 📜 Harvard Museum Insights
Explore, analyze, and visualize artifact data from the Harvard Art Museums using Python, MySQL, and Streamlit.

## 🎯 Project Overview

This app connects to the Harvard Art Museums API, retrieves data about thousands of artifacts, and stores it in a MySQL database.
Using Streamlit, it then displays the data through a simple, intuitive web interface.

Users can:
- Fetch fresh data directly from the API
- Browse artifacts by type, period, or culture
- Explore insights about Harvard’s museum collections
  
## 🧰 Tech Stack
- Python 3.12+
- Streamlit – for building the web app
- MySQL – for storing artifact data
- Pandas – for data cleaning and analysis
  
## ⚙ Setup Guide

### 1️⃣ Clone this repository
```
https://github.com/ayesha7123/Harvard-Museum-Insights.git
```
### 3️⃣ Install dependencies manually
```
pip install streamlit pandas requests mysql-connector-python
```
### 4️⃣ Configure MySQL connection
- Make sure MySQL is running and create a database named:
```
CREATE DATABASE harvard_artifacts;
```
- Then, update the connection details in your code:
```
connection = mysql.connector.connect(
    host="127.0.0.1",
    user="your username",
    password="your password",
    database="harvard_artifacts"
)
```
### 5️⃣ Run the Streamlit app
```
streamlit run app.py
```
## 🔐 API Configuration

- Go to the Harvard Art Museums API
- Create a free developer account and get your API key.
- Add it directly inside your code or in a config.toml file (for cleaner security).
