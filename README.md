# 🔥 STUDY BEAST MODE

> *The study motivation website that actually makes you want to open your books.*

---

## What is this?

**Study Beast Mode** is a single-page web app designed to keep students locked in, motivated, and on track for their exams. No fluff, no boring interfaces — pure hype, countdowns, and focus tools.

Built with pure HTML + CSS + JavaScript. No frameworks, no dependencies, no excuses.

---

## Features

### 🧠 Personalized Setup
- Enter your **name or nickname** — the app greets you like a legend
- Add all your **exam names + dates** before you start
- Everything is stored in-session (private, no server)

### 🔥 Daily Motivation Memes
- 14 rotating hype cards with fire messages
- Hit **"New motivation hit"** to cycle through them
- Each card pairs with a motivational quote from legends like Confucius, Nelson Mandela, and Tim Notke

### ⏳ Exam Countdown
- Every exam shows **exact days remaining**, sorted by nearest date
- Color-coded urgency system:
  - 🟢 **Green** — chill, you've got time
  - 🟡 **Yellow** — hustle mode (≤7 days)
  - 🔴 **Red** — PANIC MODE (≤1 day or today)
  - ✓ **Gray** — already done, respect

### 🍅 Pomodoro Focus Timer
- Classic **25 min study / 5 min break** cycle
- **Long break (15 min)** after every 4 sessions
- Visual session dots so you know exactly where you are
- Start, pause, resume, and reset controls
- Alert when session ends so you never forget to take a break

---

## How to Use

1. Open the app
2. Enter your **nickname**
3. Add your **exams** (name + date for each one)
4. Hit **"LET'S GET IT 🚀"**
5. Read your motivation card, check your countdowns
6. Start the Pomodoro timer and get to work
7. Tap **"New motivation hit"** whenever you feel like slacking

---

## Tech Stack

| Layer | Tech |
|-------|------|
| Markup | HTML5 |
| Styling | CSS3 (custom variables, no framework) |
| Logic | Vanilla JavaScript |
| Fonts | Google Fonts — Syne (display) + Space Grotesk (body) |
| Timer | `setInterval` based Pomodoro engine |

---

## Design Philosophy

- **Dark, high-contrast theme** — easy on the eyes during night study sessions
- **Fire orange + gold accent** palette — energetic, urgent, motivating
- **Syne font** for headings — bold, editorial, unforgettable
- **No backend** — everything runs in the browser, nothing is tracked

---

## File Structure

```
study-beast-mode/
│
├── index.html        ← The entire app (single file)
└── README.md         ← You are here
```

---

## Customization

Want to add your own memes or quotes? Find these arrays in the `<script>` section:

```js
const memes = [
  { emoji: "😤", text: "Your message here", sub: "Sub text here" },
  // add more...
];

const quotes = [
  { text: "Your quote", author: "Author Name" },
  // add more...
];
```

---

## Tips for Maximum Effect

- 🌙 Use it at night with dark mode — the theme is built for it
- 📵 Put your phone away after starting the timer
- 🎯 Add ALL your exams so the pressure is always visible
- 🔄 Refresh the motivation card whenever you feel stuck
- ☕ Treat long breaks seriously — your brain needs it

---

## License

Free to use, share, and modify. Just don't use it as an excuse to procrastinate. 😤

---

*Built with 🔥by Ikhlass and the belief that you WILL pass your exams.*
