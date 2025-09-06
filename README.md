<h2 align="center">📊 Real-Time Sales Dashboard</h2>

Welcome to my **Softsinc Internship 2025 Week 5 Practice Project**!  
This project is a simple, real-time sales analytics dashboard built with **Python**, **Flask**, **Dash**, and **Plotly**, created to practice development skills and solve real-world problems.

---

## 🚀 Project Goal

The goal is to build a web dashboard that:
- Loads sales data from a file.
- Provides a backend REST API for live analytics.
- Shows interactive charts for sales by region and product.
- Updates dynamically to help make quick business decisions.

---

## 📂 Project Structure
```bash
📁 data/
├── sales_data.txt # Sample sales data
├── schema.md # Explains data columns
📁 src/
├── data_loader.py # Loads data
├── process_data.py # Processes data (grouping, totals)
├── api.py # Flask backend
├── __init__.py # Marks src as a package
📁 dashboard/
├── app.py # Dash web app
📄 requirements.txt # Python dependencies
📄 README.md # This file
📄 LICENSE # Project license
```

## 🧩 How to Run

1️⃣ **Clone the repo**
```bash
git clone https://github.com/gazanfar-ali/sales-dashboard.git
cd sales-dashboard
```

2️⃣ Install dependencies
```bash
pip install -r requirements.txt
```
3️⃣ Run the backend API
```bash
python src/api.py
```
The API will be live at: 
```bash
http://127.0.0.1:5000
```

## 📈 API Endpoints
| Route             | Description                        |
| ----------------- | ---------------------------------- |
| /                 | Home page                          |
| /total-sales      | Returns total sales revenue        |
| /sales-by-region  | Returns revenue grouped by region  |
| /sales-by-product | Returns revenue grouped by product |

## 📦 Dependencies
Below are the libraries used in this project:
```bash
Library	Why It’s Needed	Version Example
Flask	Runs the backend REST API that serves the sales data	3.0.0
pandas	Loads, cleans, and processes the sales data files	2.2.2
dash	Builds the interactive dashboard web app	2.17.0
plotly	Provides interactive charts used by Dash	5.22.0
requests	Lets the dashboard fetch data live from the Flask API	2.31.0
```


## 📜 License
This project is licensed under the MIT License.
You are free to use, modify, and distribute it, provided proper attribution is given.
It comes with no warranty — use it at your own risk.
