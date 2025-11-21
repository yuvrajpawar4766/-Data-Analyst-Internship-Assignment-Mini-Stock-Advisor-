# 📈 Rule-Based Mini Stock Advisor  
A simple rule-based (NO machine learning) stock advisor that generates **BUY / SELL / HOLD** signals based on daily percentage change logic. Python is used for data processing & rule evaluation, and R is used for generating plots.

---
## 🧠 Project Overview

### **1️⃣ Compute Daily Percentage Change**


### **2️⃣ BUY Rules**
A **BUY** signal is generated if ANY ONE is true:
- Today’s % change > **+2%** AND yesterday had positive change  
- Today AND yesterday both had a positive change

### **3️⃣ SELL Rules**
A **SELL** signal is generated if ANY ONE is true:
- Today’s % change < **–2%**  
- Today AND yesterday both had negative change

### **4️⃣ HOLD Rule**
A HOLD signal is assigned when:
- % change is between **–2% and +2%**, AND  
- No BUY/SELL rule is triggered

---


---

## 🐍 Python Script (stock_advisor.py)

The Python script:
- Creates or loads a 10-day dataset  
- Computes daily percentage change  
- Applies the rule-based system  
- Outputs BUY / SELL / HOLD for each day  

Run using:


