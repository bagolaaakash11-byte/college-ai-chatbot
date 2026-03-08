# 🎓 SIIET College AI Chatbot

A fully static AI chatbot for SIIET Engineering College — deployable directly on **GitHub Pages** with zero backend required.

> Built with pure HTML, CSS, and JavaScript. No server. No Python. No cost.

---

## 🌐 Live Demo

After deploying, your chatbot will be live at:
```
https://YOUR_USERNAME.github.io/siiet-chatbot/
```

---

## 🚀 Deploy to GitHub Pages (3 Steps)

### Step 1 — Create a GitHub Repository
1. Go to [github.com](https://github.com) → Click **New Repository**
2. Name it: `siiet-chatbot`
3. Set it to **Public**
4. Click **Create Repository**

### Step 2 — Upload Files
1. Click **uploading an existing file** in your new repo
2. Drag and drop `index.html` and `README.md`
3. Click **Commit changes**

### Step 3 — Enable GitHub Pages
1. Go to your repo → **Settings** → **Pages**
2. Under **Source**, select `main` branch → `/ (root)` folder
3. Click **Save**
4. Wait ~60 seconds → Your site is live! ✅

---

## ✨ Features

- 🤖 NLP question matching (runs entirely in browser)
- 🗣️ Voice input via Web Speech API (Chrome/Edge)
- 🔊 Text-to-speech bot responses
- 💬 Typing animation indicator
- ⚡ Quick question chips for one-click answers
- 📋 Interactive FAQ directory cards
- 🗺️ Embedded Google Maps college location
- 📱 Fully responsive on mobile

---

## 🧠 How It Works (No Python Needed!)

| Original (Flask) | GitHub Pages Version |
|---|---|
| Python Flask server | Pure HTML/JS |
| spaCy NLP similarity | JS keyword overlap scoring |
| SQLite database | JS array (same FAQ data) |
| `python app.py` | Just open `index.html` |

---

## ➕ To Add More FAQs

Open `index.html` and find the `FAQ` array:
```javascript
const FAQ = [
  { q: "Your new question here?", a: "Your answer here" },
];
```

---

## 👨‍💻 Developed By

**Aakash** — SIIET Engineering College, Cybersecurity Department
