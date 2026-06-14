# 🍽️ Chetan — Restaurant Personal Assistant Chatbot

> **Internship Project** | AcmeGrade AI Internship
> An intelligent restaurant assistant powered by a custom JavaScript NLP engine

[![Live Demo](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-brightgreen?style=for-the-badge)](https://chetan1434.github.io/ChatBot-Chetan)
[![Made with](https://img.shields.io/badge/Made%20with-HTML%20%7C%20CSS%20%7C%20JS-orange?style=for-the-badge)]()
[![NLP](https://img.shields.io/badge/NLP-Rule%20Based%20Engine-blue?style=for-the-badge)]()

---

## 🌟 Features

| Feature | Description |
|---|---|
| 📋 **Menu Exploration** | Browse full menu with prices, veg/non-veg tags |
| 📅 **Table Reservation** | Book tables with date, time, party size |
| 🛵 **Order Taking** | Add items to cart, live order summary in sidebar |
| 🥗 **Dietary Filters** | Vegetarian, spicy, allergy-friendly suggestions |
| 🌟 **Smart Recommendations** | Based on mood, occasion, or preferences |
| 👨‍🍳 **Chef Special** | Daily special dish highlight |
| 💬 **NLP Understanding** | Natural conversation — no rigid commands needed |
| ⚡ **Quick Replies** | Context-aware follow-up suggestions |

---

## 🛠 Tech Stack

- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **NLP**: Custom in-browser intent detection & entity extraction (regex/keyword based)
- **Design**: Custom restaurant-themed UI with warm color palette
- **Deployment**: GitHub Pages (fully static, no backend or API key required)

---

## 🧠 How the NLP Works

Chetan's ChatBot doesn't call any external AI API — all the "understanding" happens directly in the browser via `index.html`:

- **Intent detection**: User messages are matched against patterns to classify intent (greeting, menu, booking, order, price, allergy, recommendation, etc.)
- **Entity extraction**: Menu item names, party sizes, and times are pulled directly from the user's message
- **Sentiment detection**: Positive/negative words adjust the tone of the bot's reply
- **Response generation**: Each intent maps to a dynamic response built from the live `MENU` data and current order/booking state

This keeps the project fully static and easy to run — no API keys, no backend, no setup beyond opening a file in your browser.

---

## 🚀 Setup

```bash
git clone https://github.com/Chetan1434/ChatBot-Chetan.git
cd ChatBot-Chetan
```

Open `index.html` in your browser — done! No API key or build step needed.

---

## 🌐 Live Demo

👉 **[chetan1434.github.io/ChatBot-Chetan](https://chetan1434.github.io/ChatBot-Chetan)**

---

## 👨‍💻 Author

**Chetan Bhalekar** — AI Intern @ AcmeGrade
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Chetan%20Bhalekar-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/chetan-bhalekar)
[![GitHub](https://img.shields.io/badge/GitHub-Chetan1434-181717?style=flat&logo=github&logoColor=white)](https://github.com/Chetan1434)

*Built as part of the AcmeGrade AI Internship Program 🎓*
