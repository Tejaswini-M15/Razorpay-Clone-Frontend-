# 🚀 Razorpay Clone (Frontend)
![Tailwind CSS](https://img.shields.io/badge/Styled_with-TailwindCSS-38BDF8?style=for-the-badge&logo=tailwindcss)
![Built with Vite](https://img.shields.io/badge/Bundled_with-Vite-646CFF?style=for-the-badge&logo=vite)

A high-fidelity, responsive frontend clone of the official Razorpay homepage. Built using **HTML5**, **Tailwind CSS**, and custom utilities, this project focuses on layout accuracy, responsiveness, clean design principles, and interaction effects.
---

## 📸 Live Preview
> ✨ A full-featured UI replica inspired by Razorpay’s homepage. Includes all major sections: Navbar, Hero, Features, Banking Suite, CTA, Footer, and more — with responsive breakpoints.
---


## 🎥 Project Demo

### 🖥️ Desktop View 
#### 👉 [Watch Desktop Demo](https://drive.google.com/file/d/19_bgfR7snA1Z4eg0BAygPCAEhJ6i95Zh/view?usp=sharing)
---
### 📱 Responsive View (Tablet & Mobile)
Covers media queries, layout changes, and responsiveness for smaller devices.
#### 👉 [Watch Mobile/Tablet Demo](https://drive.google.com/file/d/YOUR_MOBILE_VIDEO_LINK/view?usp=sharing)
---

## 🛠 Tech Stack

- ⚙️ **HTML5** — semantic layout structure  
- 🎨 **Tailwind CSS** — utility-first responsive styling  
- 📦 **Feather Icons** — for consistent, lightweight icons  
- 🔀 **Flexbox & Grid** — advanced layout control  
- 🖼 SVG + PNG assets (manually imported for realism)
---

## 📐 Features Implemented

- ✅ Responsive **navbar** with hover effects
- ✅ **Hero section** with CTA and background SVG
- ✅ **Feature section** with animated icons and cards
- ✅ **RazorpayX banking suite** with interactive layout
- ✅ **Floating illustrations**, layered gradients & z-index control
- ✅ Scroll-based section reveals and CTA section
- ✅ **Professional footer** with full link structure
- ✅ Custom typography using **Google Fonts (Mulish)**
---

## 🧰 How to Run Locally

### ⚙️ Development Setup (Tailwind CSS + Vite)

This project uses **Tailwind CSS** with **Vite** for fast local development. Follow these steps to set it up:
```bash
# 1. Initialize project and install dependencies
npm init -y
npm install -D tailwindcss postcss autoprefixer vite

# 2. Generate config files
npx tailwindcss init -p

# 3. Add start script to package.json
# Inside "scripts" block:
"start": "vite"

# 4. Configure Tailwind to scan your files
# In tailwind.config.js
content: ["./index.html", "./**/*.js"]

# 5. Create your style file (style.css)
# Add the following to style.css:
@tailwind base;
@tailwind components;
@tailwind utilities;

# 6. Link the CSS in your HTML
# Inside <head> of index.html
<link rel="stylesheet" href="/style.css" />

# 7. Start development server
npm run start
```

### Folder Structure 🗂️
```
razorpay-clone/
├── images/                 # All SVG, PNG, icons, illustrations
├── node_modules/           # Installed dependencies
├── .hintrc                 # Linter config (optional)
├── index.html              # Main HTML file
├── package.json            # Project metadata and scripts
├── package-lock.json       # Dependency lock file
├── postcss.config.js       # PostCSS config (used by Tailwind)
├── tailwind.config.js      # Tailwind CSS config
├── style.css               # Tailwind + custom styles
└── README.md               # Project documentation
```
---

## 🧠 What I Learned

- Creating pixel-perfect layouts with Tailwind CSS
- Organizing responsive content across breakpoints
- Working with `z-index`, positioning, and SVG illustrations
- Understanding the visual structure of a real-world product landing page
---

## 🔮 Future Improvements

- [ ] Mobile menu with animated toggle  
- [ ] Scroll animations (e.g., with AOS or Framer Motion)  
- [ ] Live hosting via Netlify or Vercel  
- [ ] Convert to React (component-based) for scalability
---

## 👩‍💻 About Me

**Tejaswini Mohapatra** — CSE Undergrad | Frontend Enthusiast 💙

- 🐙 GitHub: [@Tejaswini-M15](https://github.com/Tejaswini-M15)
- 💼 LinkedIn: [Tejaswini Mohapatra](https://www.linkedin.com/in/tejaswinim15)

> If you found this project interesting, feel free to ⭐ star the repo and connect with me!
---
