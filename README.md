# EV Charger Quotation Tool

A simple **Python-based quotation calculator** for EV charger equipment.

This tool allows users to input:

- Product name
- Quantity
- Unit price

The program will automatically calculate:

- Subtotal (before tax)
- Tax (5%)
- Total price (including tax)
- Quotation summary

This project is designed as a **Python beginner project with a real-world business scenario**.

---

# Features

- Input product name
- Input quantity
- Input unit price
- Automatically calculate:
  - Subtotal
  - Tax (5%)
  - Total price
- Generate quotation summary

---

# Example

### Input

```
請輸入品名：7kW AC充電樁
請輸入數量：3
請輸入單價：25000
```

### Output

```
====== 報價結果 ======

品名：7kW AC充電樁
數量：3
單價：25,000 元
未稅小計：75,000 元
稅額(5%)：3,750 元
含稅總價：78,750 元

報價摘要：
7kW AC充電樁 x 3，單價 25,000 元，
未稅 75,000 元，含稅總價 78,750 元。
```

---

# Technologies Used

- Python
- Basic arithmetic operations
- User input / output
- String formatting

---

# Project Structure

```
ev-charger-quotation-tool
│
├─ quotation_tool.py
└─ README.md
```

---

# How to Run

### 1 Clone repository

```
git clone https://github.com/yourusername/ev-charger-quotation-tool.git
```

### 2 Enter project folder

```
cd ev-charger-quotation-tool
```

### 3 Run program

```
python quotation_tool.py
```

---

# Future Improvements

Possible improvements for this project:

- Support **multiple products**
- Export quotation to **CSV / TXT**
- Add **installation cost**
- Add **material cost**
- Create **GUI interface**
- Build **web-based quotation tool**

---

# Learning Purpose

This project helps practice:

- Python fundamentals
- Input / output handling
- Basic financial calculation
- Practical business automation

---

# Author

Created as part of a **Python learning and GitHub portfolio project**.
