# Mazen Abdelatty — Personal Portfolio

A premium, responsive personal portfolio website built with **vanilla HTML, CSS, and JavaScript**, featuring a sleek **gold + black** design theme.

## 🌟 Features

- **Responsive Design** — Works seamlessly across desktop, tablet, and mobile
- **Dark/Light Theme Toggle** — Persistent theme preference using localStorage
- **Smooth Animations** — Scroll-triggered fade-ins, typing effect, gold particle hero
- **Working Contact Form** — Client-side validation linked to FormSubmit API to send real emails directly to your inbox without a backend
- **Time-of-Day Greeting** — Dynamic greeting that changes based on the current time

## 📁 Project Structure

```
202277380-Mazen_Abdelatty-assignment-1/
├── index.html              # Main HTML page
├── css/
│   └── styles.css          # All styles (responsive, themes)
├── js/
│   └── script.js           # All interactivity
├── assets/
│   └── images/             # Profile photo & project images
├── docs/
│   ├── ai-usage-report.md  # AI tools documentation
│   └── technical-documentation.md
└── README.md               # This file
```

## 🚀 Setup Instructions

1. **Clone** (or download) this repository
2. Open the project using a local HTTP server such as **Live Server** in VS Code (or `npx serve`). This is required so the Contact Form's AJAX requests are not blocked by browser CORS security policies.
3. Test the contact form (the very first submission requires you to click an activation link sent to your email by FormSubmit).

## 🤖 AI Usage Summary

AI tools (Claude / Antigravity) were used to assist with:

- **Code generation** — HTML structure, CSS styling, JavaScript interactivity
- **Design decisions** — Color palette selection, layout architecture, animation effects
- **Image generation** — Placeholder project images
- **Documentation** — README and AI usage report drafting

Full details in [`docs/ai-usage-report.md`](docs/ai-usage-report.md).

## 🛠 Technologies

- HTML5, CSS3, JavaScript (ES6+)
- Google Fonts (Outfit, Inter)
- Font Awesome 6.5
- CSS Grid & Flexbox
- IntersectionObserver API

## 📄 License

© 2025 Mazen Abdelatty. All rights reserved.
