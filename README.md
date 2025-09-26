# 🧹 Customer Data Cleaning & Preparation Project

An end-to-end project demonstrating how to clean messy data, handle missing values, remove duplicates, and merge multiple datasets using **Pandas** in Python.  
The ultimate goal is to transform raw, scattered customer and transaction data into a **clean, unified dataset** ready for analytics, BI dashboards, and machine learning models.  

---

## ✨ Key Features

- **Duplicate Data Management**: Detect and remove duplicate customer records.  
- **Missing Value Handling (NaNs)**: Fill missing values using **mean** (numeric) and **mode** (categorical).  
- **Intelligent Data Merging**: Combine customer and transaction datasets using `customer_id`.  
- **Clean & Usable Output**: Export the final dataset as `finalldata.csv`.  

---

## 🛠️ Tech Stack & Tools

- **Programming Language**: Python 3.x  
- **Libraries**: Pandas  
- **Environment**: Jupyter Notebook  

---

## 📂 Project Structure

```bash
.
├── Data/
│   ├── customerinfo.csv       # Raw customer data (input)
│   ├── transaction.csv        # Raw transaction data (input)
│   └── finalldata.csv         # Cleaned dataset (output)
│
└── exerciseDataCleaning.ipynb  # Main notebook with all cleaning & merging steps
