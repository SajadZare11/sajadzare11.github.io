# Sajad Zare - Personal Biography & Portfolio

Official website source code for [sajadzare11.github.io](https://sajadzare11.github.io).

A responsive biography and portfolio website celebrating a dual career: **Backend & Cloud Engineer** (Python, Go, Docker, APIs) and **English Educator** (IELTS/TOEFL Exam Preparation, General English, High School Curriculum).

---

## 🌟 Highlights & Features

- **Dual-Focus Identity**: Highlights both Software Engineering and English Teaching with clear, balanced sections.
- **Pure Modern Tech Stack**: Built with zero build tools or complex dependencies (Vanilla HTML5, modern CSS with custom properties, and modular ES6 JavaScript).
- **Dark & Light Mode**: Built-in theme switcher with automatic system preference detection (`prefers-color-scheme`) and `localStorage` persistence.
- **Full Responsive Design**: Optimized across mobile phones, tablets, and desktop displays.
- **Interactive Features**:
  - Scroll-spy navigation with auto-highlighting
  - Mobile hamburger navigation drawer
  - Interactive contact form with client validation and mailto routing
  - Modular skill badges and project feature cards
- **SEO & Social Sharing**: Preconfigured Open Graph meta tags, structured semantic HTML, and accessibility features.

---

## 📂 Project Structure

```text
Biagraphy/
├── .nojekyll           # Tells GitHub Pages to bypass Jekyll processing
├── index.html          # Main homepage and biography structure
├── css/
│   └── style.css       # Design tokens, variables, responsive layout, dark/light theme
├── js/
│   └── main.js         # Theme toggle, mobile menu, scroll-spy, contact handler
└── README.md           # Documentation & deployment guide
```

---

## 🚀 How to Deploy to GitHub Pages

1. **Initialize Git Repository** (if not already done):
   ```bash
   git init
   git add .
   git commit -m "Initial biography website release"
   ```

2. **Connect to your GitHub Pages Repository**:
   Make sure you have created the repository named `sajadzare11.github.io` under your GitHub account `sajadzare11`:
   ```bash
   git branch -M main
   git remote add origin https://github.com/sajadzare11/sajadzare11.github.io.git
   git push -u origin main
   ```

3. **Verify GitHub Pages Settings**:
   - Go to your repository on GitHub: `https://github.com/sajadzare11/sajadzare11.github.io/settings/pages`
   - Under **Build and deployment** > **Source**, ensure it is set to **Deploy from a branch** with branch **`main`** and folder **`/ (root)`**.
   - Your site will be live at `https://sajadzare11.github.io` within a few minutes!

---

## 🛠️ Customization Guide

- **Profile Picture**: Place an image in an `assets/` folder (e.g. `assets/profile.jpg`) and replace the SVG avatar inside `.avatar-wrapper` in `index.html`.
- **Contact Details**: Update your email, LinkedIn URL, or Telegram handle in the Hero and Contact sections of `index.html`.
- **Contact Form Backend**: By default, the form opens the visitor's mail client with your prefilled email (`sajadzare11@gmail.com`). If you prefer an automated service like [Formspree](https://formspree.io), simply set `<form action="https://formspree.io/f/YOUR_ID" method="POST">` in `index.html`.
