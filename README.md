# Loomé - Premium E-Commerce Interface Clone

A pixel-perfect, static front-end clone of the Loomé organic cotton luxury apparel store landing page. Built as part of a Level 3 milestone assignment during my engineering cohort at Sheryians. 

The goal of this project was to implement complex design mockups using advanced structural HTML and foundational CSS layout mechanics under strict technical constraints.

![Loomé Interface Preview](image_7ac993.jpg)

---

## 🛠️ Technical Constraints & Implementation

This project was built strictly using the core building blocks of CSS layout architecture covered up to Level 3 of the cohort. 

* **Layout Mechanics:** Implemented entirely using **CSS Flexbox** and **Explicit Positioning (`position: absolute / relative / fixed`)**. 
* **Design Control:** Built without using CSS Grid, external UI libraries, Bootstrap, or TailwindCSS. Every alignment, card overlay, and spacing token was coded from scratch using raw CSS.
* **Current Scope:** This is a non-responsive, non-functional static layout focusing 100% on pure UI precision, typographic scaling, and asset layering.

---

## 🧠 Key Learning Outcomes & Architectural Challenges

### 1. Complex Card Overlays & Layers
The primary challenge was layering elements dynamically over the main hero product image. I utilized absolute positioning context safely isolated within a relative container parent to mount the pricing tag (`$448`), the dynamic star rating badge, and the offset floating "Add to Bag" circular call-to-action button perfectly over the image boundaries.

### 2. Typographic Hierarchy & Spacing Tokens
Achieved clean typographic balance by matching the large serif header elements (`a cotton weave`) with precisely tracked sans-serif metadata sections and standard body copy block parameters. 

### 3. Asymmetric Dynamic Layouts
Managed the right-aligned layout columns (the image carousel thumbnails) and the bottom value-proposition horizontal layout blocks entirely through nested Flexbox axes to ensure exact pixel matching with the baseline design file.

---

## 💻 Tech Stack Implemented

- **HTML5:** Semantic architecture blocks (`<nav>`, `<section>`, `<main>`)
- **CSS3:** Advanced Flexbox properties, structural alignment, custom overlay positioning coordinates

---

## 🚀 To View the Project Locally

1. Clone the repository to your workstation:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/REPOS_NAME.git](https://github.com/YOUR_USERNAME/REPOS_NAME.git)
