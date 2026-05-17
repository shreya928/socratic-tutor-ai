# 🎭 AI Socratic Tutor

> An AI-powered learning app that **never gives you the answer** — it only asks the right questions to guide you to discover it yourself.

![Made with Claude AI](https://img.shields.io/badge/Powered%20by-Claude%20AI-7F77DD?style=flat-square)
![HTML CSS JS](https://img.shields.io/badge/Built%20with-HTML%20%7C%20CSS%20%7C%20JS-orange?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)

---

## 🌐 Live Demo

👉 **[shreya928.github.io/socratic-tutor-ai](https://shreya928.github.io/socratic-tutor-ai)**

---

## 💡 What is Socratic Learning?

The Socratic method is a form of teaching where the teacher **never explains directly** — instead, they ask probing questions that force the student to think, reason, and arrive at the answer themselves.

Studies show this leads to **deeper understanding and longer retention** compared to passive learning.

This app applies that method using AI.

---

## ✨ Features

- 🧠 **AI-powered questioning** — Claude AI generates adaptive Socratic questions based on your answers
- 📈 **Live mastery tracking** — understanding score updates in real-time as you progress
- 🎯 **8-question deep-dive sessions** — gradually increases in depth and complexity
- 📚 **6 preset topics** — Binary Search, OOP, Machine Learning, SQL, REST APIs, Networking
- ✏️ **Custom topic input** — learn anything you want
- 🏆 **Session results** — mastery score + personalized insights at the end
- 🌙 **Dark mode support** — auto-detects system theme

---

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| HTML / CSS / JavaScript | Frontend (no frameworks) |
| Claude API (Anthropic) | AI question generation |
| GitHub Pages | Free hosting & deployment |

---

## 🚀 How to Run Locally

1. Clone the repo
```bash
git clone https://github.com/shreya928/socratic-tutor-ai.git
cd socratic-tutor-ai
```

2. Open `index.html` directly in your browser — no server needed!

3. Get a free API key from [console.anthropic.com](https://console.anthropic.com)

4. Paste your key in the input box on the app and click **Save key**

5. Pick a topic and start learning! 🎉

---

## 🔑 API Key Setup

This app uses the **Anthropic Claude API** to generate questions.

- Get a free key at [console.anthropic.com](https://console.anthropic.com)
- New accounts receive free credits (no credit card required)
- Your key is stored **only in your browser** — never sent to any external server

---

## 📸 Screenshots

> *(Add a screenshot of your app here)*
> Tip: Press `Windows + Shift + S` to take a screenshot and drag it into this file on GitHub

---

## 🧠 How It Works

```
User picks a topic
       ↓
Claude AI asks an opening question
       ↓
User types their answer
       ↓
Claude analyzes the answer and asks a deeper follow-up
       ↓
Repeat for 8 questions (getting progressively deeper)
       ↓
Final mastery score + insights shown
```

---

## 📁 Project Structure

```
socratic-tutor-ai/
│
└── index.html        # Complete app — HTML + CSS + JS in one file
```

---

## 🎯 What I Learned Building This

- Integrating the **Anthropic Claude API** with multi-turn conversation history
- Designing **adaptive AI prompts** that change behavior based on question number
- Extracting **structured JSON data** (mastery score) from AI responses
- Building a **stateful single-page app** without any frameworks
- Deploying a frontend project with **GitHub Pages**

---

## 🔮 Future Improvements

- [ ] Voice input support (Web Speech API)
- [ ] Topic difficulty levels (beginner / intermediate / advanced)
- [ ] Session history saved across visits
- [ ] Backend proxy so visitors don't need their own API key
- [ ] Leaderboard for mastery scores

---

## 📄 License

MIT License — feel free to use, modify, and share.

---

## 👩‍💻 Author

**Shreya** — [github.com/shreya928](https://github.com/shreya928)

*Built as part of my AI projects portfolio*
