# 🌐 Huddle Landing Page

This is a **responsive community landing page** project built with HTML, SASS, and JavaScript. The design reflects modern aesthetics with a focus on accessibility, responsiveness, and simplicity. It introduces **Huddle**, a fictional platform to build vibrant online communities.

---

## 📌 Project Overview

Huddle reimagines the way communities are built and managed online. This landing page introduces the platform and encourages users to register and connect.

🧭 Ideal for:

* Startup landing demos
* Frontend design portfolios
* Intro screens for community-based platforms

---

## ✨ Features

* 🎨 Clean and modern responsive UI
* 📱 Mobile-first design using SASS
* 🖼️ SVG-based background illustrations
* 🧩 Component-based SASS structure
* 🧠 Optimized for future extension (React, Firebase, etc.)

---

## 📁 Project Structure

```
h.landing-page/
├── images/                     # Assets like SVGs and icons
│   ├── bg-desktop.svg
│   ├── bg-mobile.svg
│   ├── illustration-mockups.svg
│   ├── logo.svg
│   └── favicon-32x32.png
├── css/
│   └── style.css               # Compiled from SASS
├── sass/
│   └── _index.scss             # Main SASS file (watch target)
├── index.html                  # Landing page markup
├── package.json                # SASS and dependencies config
├── package-lock.json
└── README.md                   # Project documentation
```

---

## 🔧 Technology Stack

* **Languages**: HTML5, SASS (CSS preprocessor), JavaScript (minimal)
* **Tools**: Node.js, NPM, Live Server / VS Code
* **Design Assets**: Custom SVGs and mockups

---

## 📋 Prerequisites

Ensure you have:

* **Node.js** and **npm** installed
* A code editor like **VS Code**

Install SASS globally (optional):

```bash
npm install -g sass
```

---

## 🛠 Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/h.landing-page.git
cd h.landing-page

# Install dependencies
npm install

# Start the SASS watcher to compile styles
npm start
```

Open `index.html` in your browser or use Live Server in VS Code.

---

## 📄 How It Works

* 📱 The page adapts across desktop and mobile with media queries
* 🖍️ Visual styling is handled using SASS for modular and reusable CSS
* 📦 Assets are preloaded as SVGs to maintain performance and clarity
* 💡 The "Register" button can be wired up for backend integration later

---

## 🚀 Future Enhancements

* 🔐 Connect "Register" to backend form/authentication
* 🌐 Add routing for multi-page support
* ⚙️ Convert to React/Vue component
* 🧪 Add accessibility enhancements (ARIA roles, keyboard nav)
