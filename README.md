# 🚀 Task 2 — Vite + Nunjucks Multi-Page Site

A modern multi-page static website built with **Vite** as the bundler and **Nunjucks** as the templating engine. Recreates the Task 1 deliverable using a proper tech stack with shared layouts, reusable partials, and a clean design system.

---

## 🛠️ Technologies Used

| Category         | Tool       | Purpose                          |
|------------------|------------|----------------------------------|
| Bundler          | Vite 5     | Dev server, HMR, production build|
| Templating Engine| Nunjucks   | Layouts, partials, variables     |
| Styling          | Vanilla CSS| Custom design system             |
| Markup           | HTML5      | Semantic page structure          |

---

## 📁 Folder Structure
task2-vite-nunjucks/
├── src/
│   ├── templates/
│   │   ├── layout.njk          ← Shared base layout
│   │   └── partials/
│   │       ├── navbar.njk      ← Navigation partial
│   │       └── footer.njk      ← Footer partial
│   ├── assets/
│   │   └── style.css           ← Global design system CSS
│   ├── index.html              ← Home page
│   ├── about.html              ← About page
│   └── contact.html            ← Contact page
├── dist/                       ← Compiled output (generated)
├── vite.config.js              ← Vite + Nunjucks configuration
├── package.json
└── README.md
