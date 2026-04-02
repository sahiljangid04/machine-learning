# 🛒 Market Basket Analysis (FP-Growth)

![Python](https://img.shields.io/badge/Python-blue)
![MLxtend](https://img.shields.io/badge/MLxtend-green)

## 📌 Overview
Performed Market Basket Analysis on retail data to find product associations using **FP-Growth**.

---

## ⚙️ Steps
- Cleaned data (removed nulls, cancelled orders)
- Created transactions using `InvoiceNo`
- Applied one-hot encoding (`TransactionEncoder`)
- Used **FP-Growth** to find frequent itemsets
- Generated association rules (support, confidence, lift)

---

## 📊 Example Rule
```
ALARM CLOCK GREEN → ALARM CLOCK RED
Confidence: 0.65 | Lift: 12.5
```

---

## 🚀 Run
```bash
pip install pandas mlxtend openpyxl
jupyter notebook script.ipynb
```

---

## 🎯 Use
- Product recommendation  
- Cross-selling  
- Retail insights