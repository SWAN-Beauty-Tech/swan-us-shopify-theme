# 🛍️ Shopify Smooth Scroll + GSAP Animation Setup (with Lenis)

This project enhances a **Shopify theme** by adding **smooth scrolling** (via Lenis) and **scroll-triggered animations** (via GSAP + ScrollTrigger).  
Each Shopify section includes its own animation logic and minimal CSS, while **common styling** lives in a global `custom.css` file.

---

## ✨ Features

- 🌊 Smooth and natural scroll behavior powered by **Lenis**
- 🎞️ Section-based GSAP + ScrollTrigger animations
- 🧱 Modular structure — each section manages its own CSS + JS
- ⚙️ Global shared styles via `assets/custom.css`
- 📱 Fully responsive and Online Store 2.0 compatible

---

## 🧩 Project Structure

📁 Shopify Theme
│
├── 📂 assets
│ ├── custom.css ← global shared CSS
│ └── (Lenis + GSAP loaded via CDN in theme.liquid)
