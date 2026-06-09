# 🧾 Tip Calculator & Bill Splitter

A fast, responsive web application that calculates tip amounts, grand totals, and per-person splits in real-time. I built this project to focus on live DOM manipulation, instant user feedback, and clean UI design without relying on a "Calculate" button.

**Live Demo:** `https://tip-calculator-bill.netlify.app/`

---

## ✨ Features
* **Real-Time Math:** Values update instantly as you type.
* **Inline Validation:** Gracefully handles errors (like negative numbers or zero people) with localized messages instead of annoying pop-ups.
* **Responsive Design:** Mobile-first layout that looks great on any screen size.
* **Keyboard Accessible:** Fully navigable using the `Tab` key.

---

## 🛠️ Tech Stack & Workflow

This project was built using standard web technologies, accelerated by modern AI development tools:

* **Frontend UI:** HTML5 & Bootstrap 5 *(Scaffolded and styled with the help of Claude 3.5)*
* **Scripting:** Vanilla JavaScript / jQuery *(Core logic, math, and DOM manipulation assisted by the Cursor IDE)*
* **Architecture:** Completely static, no build step required.

---

## 🚀 How to Run Locally

Because this project is entirely static, running it is incredibly simple:

1. Clone or download this repository.
2. Double-click the `index.html` file to open it in any modern browser.

*(Note: An active internet connection is needed to load the Bootstrap CSS and jQuery scripts via CDN).*

---

## 💡 What I Learned
Building this helped me refine how I handle state in a purely vanilla JavaScript environment. Managing edge cases—like what happens when a user types letters into a number field, or dividing by zero—required careful attention to detail and improved my understanding of front-end data validation.
