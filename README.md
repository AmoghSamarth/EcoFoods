# 🌿 EcoFoods

A responsive food delivery landing page built with pure HTML and CSS. EcoFoods promotes healthy, organic, and eco-friendly food delivery as an alternative to junk food.
- Live link: [EcoFoods](https://eco-foods.netlify.app/)

---

## 📸 Preview

> A multi-section single-page website featuring a hero section, meal showcase, how-it-works steps, city availability, customer testimonials, pricing plans, a contact form, and a footer.

---

## 🚀 Features

- Full-screen hero section with parallax background
- Animated meal photo grid with hover zoom effect
- 3-step "How it Works" section with phone mockup
- City availability section with location images
- Customer testimonials with parallax background
- Pricing plan cards (Premium / Pro / Economy)
- Contact form with name, email, dropdown, newsletter checkbox, and message
- Responsive design across 4 breakpoints (1200px, 1023px, 767px, 480px)
- Footer with navigation links and social icons

---

## 🛠️ Tech Stack

- HTML5
- CSS3 (Flexbox, Float-based grid, Media Queries)
- [Ionicons](https://ionic.io/ionicons) for icons
- [Google Fonts](https://fonts.google.com/) — Lato + Playfair Display
- Normalize.css for cross-browser consistency

---

## 📁 Project Structure

```
EcoFoods/
├── index.html
├── resources/
│   ├── css/
│   │   └── style.css
│   ├── img/
│   │   └── (hero, meal, city, customer images)
│   └── js/
│       └── script.js
└── vendors/
    └── css/
        ├── normalize.css
        ├── grid.css
        └── queries.css
```

---

## 📱 Responsive Breakpoints

| Breakpoint | Target |
|---|---|
| ≤ 1200px | Large tablets |
| ≤ 1023px | Small tablets — 2-column layout |
| ≤ 767px | Mobile — single column, nav hidden |
| ≤ 480px | Small phones — compact spacing |

---

## 🏃 Getting Started

No build tools or dependencies required.

```bash
git clone https://github.com/AmoghSamarth/EcoFoods.git
cd EcoFoods
```

Open `index.html` directly in your browser or use Live Server in VS Code.

---

## 🎯 What I Learned

- Float-based CSS grid layout and its clearfix patterns
- `overflow: hidden` as a float containment technique
- Flexbox for testimonial alignment (`align-items: stretch`, `margin-top: auto`)
- CSS parallax using `background-attachment: fixed`
- Responsive design with cascading media queries
- Debugging layout issues using browser DevTools

---

## 👨‍💻 Author

**Amogh Samarth**
- GitHub: [@AmoghSamarth](https://github.com/AmoghSamarth)
- LinkedIn: [amogh-samarth](https://linkedin.com/in/amogh-samarth-37109328b)

---

## 📝 Note

This project was built as a CSS fundamentals exercise following a tutorial on the Tutedude platform. It demonstrates core HTML/CSS layout techniques rather than a production application.