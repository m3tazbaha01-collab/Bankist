# Bankist
# 🏦 Bankist — Digital Banking Application

A modern, interactive banking application built with **Vanilla JavaScript**, HTML, and CSS. This project demonstrates core JavaScript concepts through a practical banking interface, including account management, financial transactions, date handling, and international currency formatting.

## 🌐 Live Demo


## 📸 Preview
<img width="950" height="422" alt="image" src="https://github.com/user-attachments/assets/15eb154e-e8f5-401d-a362-5c6fa650669d" />


## ✨ Features

- **User Authentication:** Log in using account-specific usernames and PINs.
- **Account Overview:** View account balance and transaction history.
- **Money Transfers:** Transfer money between demo accounts.
- **Loan Requests:** Request a loan based on account activity.
- **Transaction Management:** Review deposits and withdrawals.
- **Transaction Sorting:** Sort movements by amount.
- **Automatic Logout:** Session timer for improved demo-session management.
- **Date & Time Formatting:** Display transaction dates using JavaScript Date and Intl APIs.
- **International Currency Formatting:** Support different currencies and regional formats.
- **Dynamic UI:** Update account information and transactions without reloading the page.

## 👥 Demo Accounts

The application includes four demo accounts:

| Account Holder | PIN |
|---|---:|
| Motaz Eltayeb | `1111` |
| Ahmed Eltayeb | `2222` |
| Monem Ahmed | `3333` |
| Mustafa Balila | `4444` |

> **Important:** These are demonstration credentials for this educational project only. Never use real banking credentials or sensitive personal information.

## 🌍 Internationalization

The application uses JavaScript's built-in `Intl` API to format currencies and dates according to different locales.

Examples of supported currency configurations:

| Currency | Currency Code | Locale |
|---|---|---|
| US Dollar | USD | en-US |
| Euro | EUR | de-DE |
| British Pound | GBP | en-GB |
| Chinese Yuan | CNY | zh-CN |


Currency formatting is handled using `Intl.NumberFormat`, while date formatting uses `Intl.DateTimeFormat`.

**Note:** This is locale-based formatting, not a live foreign-exchange rate service.

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)
- JavaScript Date API
- Intl API
- DOM Manipulation
- Array Methods
- Event Handling
- Timers (`setTimeout` and `setInterval`)

## 📚 JavaScript Concepts Practiced

This project helped me practice and strengthen several JavaScript concepts:

- Array methods: `map()`, `filter()`, `reduce()`, `find()`, and `some()`.
- Array and object manipulation.
- DOM selection and manipulation.
- Event listeners and event delegation.
- Dates and timestamps.
- Internationalization with `Intl`.
- Timers and automatic logout.
- Number formatting and currency display.
- Working with application state and user interactions.

## 📁 Project Structure

```text
bankist/
│
├── index.html
├── style.css
├── script.js
├── img/
│   └── bankist-preview.png
└── README.md
```

*The structure above is an example. Adjust the filenames to match your actual project.*

## ⚠️ Disclaimer

This project is an educational front-end demonstration inspired by a banking application.

- It does not connect to real banks.
- It does not process real financial transactions.
- Demo account data is handled on the client side.
- It does not provide production-grade authentication or security.
- Currency formatting does not retrieve live exchange rates.

**Do not use this application for real financial activities.**

## 👨‍💻 Author

**Motaz Eltayeb**

Aspiring Front-End Developer passionate about building interactive web applications and improving JavaScript skills through practical projects.

- GitHub: [m3tazbaha01-collab](https://github.com/m3tazbaha01-collab)

---

⭐ If you find this project interesting, feel free to explore the code and share your feedback!
