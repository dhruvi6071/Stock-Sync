# 📊 StockFusion — Smart Stock Data Merger & Viewer

StockFusion is a **Streamlit-based web application** that allows users to **merge, clean, and view complex stock market datasets** directly from the browser.  
It automates multiple CSV and Excel data sources into one unified, analyzable dataset — perfect for analysts, finance students, and data teams.

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/StockFusion.git
cd StockFusion
```

### 2. Create and Activate Virtual Environment
```bash
python -m venv venv
venv\Scripts\activate   # on Windows
# source venv/bin/activate  # on macOS/Linux
```

### 3. Install Required Packages
```bash
pip install -r requirements.txt
```
### 4. Requirement.txt
```bash
streamlit
pandas
openpyxl
xlsxwriter
```

### 5. Run Streamlit App
```bash
streamlit run app.py
```
### 6. Open browser at 
http://localhost:8501

--- 
## 🚀 Features

**One-Click Data Merge**  
Automatically runs your full stock data processing pipeline without any terminal commands.

**Browser-Based Interface**  
Simple and intuitive web dashboard powered by **Streamlit**, no local setup required after deployment.

**Excel & CSV Integration**  
Reads `.xlsx` and `.csv` files, merges, cleans, and outputs well-structured data.

**Live Data Preview**  
Displays sample records of the final dataset inside the browser.

**Instant Download**  
Download the cleaned, merged data file (`Cleaned_Final_Data.xlsx` or `Final_data_auto.csv`) directly.

**Safe File Handling**  
Ensures all operations happen within a defined project directory (`playground`), minimizing file errors.

---

## 🏆 Ideal For

- Equity researchers & analysts
- Financial data teams
- Market data enthusiasts
- Students learning data integration & cleaning

---




