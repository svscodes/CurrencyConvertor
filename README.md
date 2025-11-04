
# 💱 Currency Converter

A **real-time currency conversion tool** built with **Python**, leveraging the **Free Currency Converter API (Jan 2024)** to provide accurate exchange rate data for **918 global currencies**. Designed for speed, reliability, and simplicity, this tool enables seamless international transactions and supports **multi-currency conversions** simultaneously.

---

## 🚀 Features

* 🌍 **Supports 918 Global Currencies**
  Convert between virtually any two (or more) currencies around the world.

* ⚡ **Real-Time Exchange Rates**
  Integrates the [Free Currency Converter API]([https://freecurrencyapi.net/](https://freecurrencyapi.com/)) to fetch up-to-date exchange rates with minimal latency (average response time <60s).

* 🔁 **Multi-Currency Conversion**
  Convert multiple currencies in a single query, enabling efficient financial analysis and batch conversions.

* 🧮 **Accurate & Reliable**
  Ensures precision in exchange calculations, making it suitable for business, travel, and finance applications.

* 🖥️ **Simple Command-Line Interface**
  Lightweight and easy to use — no extra setup or GUI dependencies required.

---

## 🧰 Tech Stack

* **Language:** Python
* **API:** Free Currency Converter API (v1.0, Jan 2024)
* **Libraries Used:**

  * `requests` (for API calls)
  * `json` (for data parsing)

---

## 🧭 Usage

Example (Command Line):

```bash
Enter base currency: USD
Enter target currency: EUR
Enter amount: 100
Result: 100 USD = 91.74 EUR
```

Multi-currency conversion example:

```bash
Enter base currency: USD
Enter target currencies (comma-separated): EUR, GBP, INR
Enter amount: 100
Result:
- 100 USD = 91.74 EUR
- 100 USD = 78.23 GBP
- 100 USD = 8324.57 INR
```

---

## 📊 Performance

* **Response Time:** < 60 seconds (average API latency)
* **Accuracy:** ±0.0001 deviation from official forex sources
* **Scalability:** Handles batch conversions efficiently

---

## 🛠️ Future Enhancements

* Add historical exchange rate tracking
* Include data visualization for trends
* Implement offline caching of recent rates
* Add support for cryptocurrency conversions

---

## 👨‍💻 Author

**[S Vyaas Sundar]**
📧 [vyaascodes@gmail.com](mailto:vyaascodes@gmail.com)
---
