# 📱 Android Developer Portfolio Website

A clean, modern, fully responsive single-page portfolio designed specifically for an **Android Developer** (`Prasanth-DEV-S`). Built with native HTML5, CSS3, and JavaScript, ready to deploy instantly on **GitHub Pages**.

![Android Developer Portfolio Banner](https://img.shields.io/badge/Android-Developer_Portfolio-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-Native_Android-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-Ready-222222?style=for-the-badge&logo=github&logoColor=white)

---

## 🌟 Key Features

- 📱 **Android Developer Centric**: Customized hero section, skills breakdown (Kotlin, Jetpack Compose, MVVM/MVI, Room, Retrofit, Coroutines/Flow, Media3), and project showcases.
- 🌓 **Dark / Light Theme Switcher**: Persisted user preference using `localStorage`.
- 📱 **Interactive Phone Mockup Frame**: Displays Android app UI concepts dynamically in the hero section.
- 🎯 **Filterable Projects Grid**: Easily sort projects by categories (All, Jetpack Compose, Full Apps, Libraries).
- 📲 **Fully Responsive Design**: Optimized for mobile screens, tablets, foldables, and desktops.
- ⚡ **Zero Dependencies & Fast Load**: Pure HTML, CSS, and JS with zero framework bloat.
- 📬 **Interactive Contact Form & Socials**: Direct links to GitHub, LinkedIn, and Email.

---

## 🚀 Step-by-Step GitHub Pages Deployment Guide

Follow these simple steps to deploy your portfolio to GitHub Pages:

### 1️⃣ Push Code to GitHub

Open terminal or command prompt in this directory and execute:

```bash
git add .
git commit -m "Add Android Developer portfolio site for GitHub Pages"
git branch -M main
git push -u origin main
```

---

### 2️⃣ Enable GitHub Pages in Repository Settings

1. Go to your GitHub repository: [Prasanth-DEV-S/prasanth_dev](https://github.com/Prasanth-DEV-S/prasanth_dev)
2. Click on **Settings** (top tab).
3. In the left sidebar, click on **Pages** under the *Code and automation* section.
4. Under **Build and deployment**:
   - **Source**: Select `Deploy from a branch`.
   - **Branch**: Select `main` branch and `/ (root)` directory.
5. Click **Save**.

---

### 3️⃣ View Your Live Portfolio Site! 🎉

Within 1–2 minutes, GitHub will publish your website at:

👉 **`https://prasanth-dev-s.github.io/prasanth_dev/`**

*(Note: If you rename your repository to `Prasanth-DEV-S.github.io`, your site URL will simply be `https://prasanth-dev-s.github.io/`)*

---

## 🛠️ How to Customize Your Details

- **Personal Details & Social Links**: Open [`index.html`](index.html) and update your social links, bio, and contact email.
- **Projects**: Edit project cards in [`index.html`](index.html#projects) to link directly to your Android repositories.
- **Color Palette & Styling**: Modify CSS variables in [`styles.css`](styles.css) (e.g. `--accent-android`, `--bg-primary`).

---

## 📂 Project Structure

```text
prasanth_dev/
├── index.html       # Main HTML5 structure & layout
├── styles.css       # Custom styling, dark/light theme & responsive grid
├── script.js        # Theme toggle, mobile navigation & interactive filters
├── README.md        # Documentation & GitHub Pages deployment guide
└── .gitignore       # Git ignore rules
```
