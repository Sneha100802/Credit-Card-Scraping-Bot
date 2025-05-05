# 🧾 Credit Card Scraping Bot

This bot extracts **credit card details** from either:

- 📄 A **PDF brochure** (e.g., from a bank or financial site)
- 🌐 A **website URL** listing credit cards

It returns a **structured dataset** with:
- Card Name
- Joining Fee
- Annual Fee
- Reward Structure
- Offers
- And more (if available)

---

## ✅ Setup Instructions

### 1. Environment Requirements

You can run this bot locally using **Jupyter Notebook** or on **Google Colab**. No paid APIs or complex tools needed.

---

### 2. Install Dependencies

In a Jupyter/Colab cell, run this once:

```python
!pip install pdfplumber beautifulsoup4 requests pandas openpyxl
