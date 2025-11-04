# Excel-Budget-Tracker
A personal budget tracker powered by Excel PivotTables and charts, with an AI-assisted Python + HTML interface for quick transaction entry and automated data updates.


# Automated Budget Tracker (Excel-Based)

This project is a personal **budget tracking system** that records daily spending and automatically updates an **Excel dashboard** with **PivotTables and visual breakdowns**.  

I designed this tool to make tracking expenses simple — I only need to select a category, enter an amount, and the backend automatically logs it in Excel. The system then updates two key reports:
- A **budget breakdown by category**
- A **daily total summary**

---

## 🧩 Project Overview

This project combines:
- **Excel automation** for data storage and analysis  
- A simple **AI-assisted Python + HTML interface** for easy daily input  

While I don’t specialize in programming, I used **AI assistance** to create a minimal web interface that automatically appends entries to my Excel file — removing the need to enter transactions manually.

---

## 📊 Excel Dashboard

![Screenshot of Dashboard](https://github.com/rdtPSU/Excel-Budget-Tracker/blob/5823989d7eb3ce5eb0a31b4a53e142af97bc2198/Budget%20Tracker%20Excel.png)

Inside the workbook:
- **Raw Data**: All transactions automatically stored from the input form  
- **Pivot Table 1 – Category Breakdown**: Summarizes total spending per category  
- **Pivot Table 2 – Daily Totals**: Tracks total spending per day  
- **Charts**: Visualize trends and spending habits over time  

---

## ⚙️ How It Works

![Screenshot of Dashboard](https://github.com/rdtPSU/Excel-Budget-Tracker/blob/7ebd6cc9e8fb9e185d0e56c058eb8b6e4463d990/Budget%20Tracker%20Website.png)

1. **Front-End Input Form**  
   - Dropdown menu to select spending category  
   - Field to enter amount  
   - “Submit” button sends data to Excel file  

2. **Excel File** (`budget.xlsx`)  
   - Automatically updates with each new transaction  
   - Pivot tables refresh manually or with a macro  

3. **AI-Assisted Backend**  
   - Python (Flask) app built with AI guidance  
   - Handles the automatic writing of data into Excel  

---

## 🧠 Skills Demonstrated

- Advanced Excel reporting using **PivotTables** and **PivotCharts**
- Data organization and categorization for financial tracking
- Process automation and workflow optimization
- Collaboration and problem-solving using **AI tools**

---

## 🧰 Tools Used

| Tool | Purpose |
|------|----------|
| **Microsoft Excel** | Main data analysis and visualization |
| **Python (Flask, OpenPyXL)** | Automating data entry (AI-assisted setup) |
| **HTML** | Simple input form (AI-assisted) |
| **ChatGPT** | Used for learning and coding guidance |

---

## 🚀 How to Run It

> *If you’d like to try the automated input form:*

1. Install dependencies  
   ```bash
   pip install flask openpyxl

Run the app:
   python app.py

Open a browser to:
  http://127.0.0.1:5000/

Enter data — it will automatically be written into budget.xlsx

