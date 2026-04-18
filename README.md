# 📊 Stock Average Calculator

A simple, interactive web tool to calculate and manage stock average prices in real time.

---

## 🚀 Features

- Live calculation (no buttons needed)
- Two-way updates:
  - Change target average → updates buy price
  - Change buy price → updates target average
- Supports:
  - Existing shares
  - Existing average price
  - New quantity planning
- Instant results in browser

---

## 🧮 How it works

The tool uses the standard weighted average formula:

\[
New Average = \frac{(Q1 × P1) + (Q2 × P2)}{Q1 + Q2}
\]

Where:
- Q1 = existing shares
- P1 = existing average price
- Q2 = new shares
- P2 = new buy price

It can also rearrange the formula to calculate missing values dynamically.

---

## 📁 Files
