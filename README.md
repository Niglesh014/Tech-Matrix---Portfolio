# TECH MATRIX — Agile–DevOps Team Portfolio Website

A clean, modern, professional, and fully responsive portfolio website for a six-member student software development team named **TECH MATRIX**, created to replicate and elevate the design of the provided reference model images.

---

## 🎨 Visual Model Alignment (Reference Images Recreated)

1. **Header & Hero Banner (Images 3 & 4):**
   - White navigation bar with bold brand name on the left and navigation links on the right.
   - Signature **horizontal purple-blue to cyan gradient** (`linear-gradient(90deg, #5b5bf7 0%, #3080ea 42%, #00c6ff 100%)`).
   - **Gentle curved bottom edge arc** (`border-radius: 0 0 50% 50% / 0 0 35px 35px;`).
   - Centered white title, subtitle, and action buttons.

2. **Team Member Profile Cards (Image 2):**
   - Clean white cards with light-gray thin borders and subtle elevation.
   - **Blue member name** (`#1a73e8`) at the top.
   - **Member email address** directly beneath the name in small gray font.
   - Professional bio paragraph.
   - **Skills** subheader with bulleted list (`• HTML`, `• C++`, `• Java`, etc.).
   - **Certifications** subheader with bulleted list (`• Cloud Fundamentals and DevOps – L&T EduTech`, etc.).
   - **Project Role** at the bottom of each card.

3. **Contact Section (Image 1):**
   - Centered **"Contact Us"** heading.
   - Clean form inputs with light-gray borders: **Full Name**, **Email address**, **Subject**, and **Message**.
   - **Full-width blue button:** **Send Message** (`background-color: #1a73e8;`).
   - Interactive client-side validation and demonstration success notification.

4. **Agile–DevOps Portfolio Components:**
   - 3 Feature cards below the hero.
   - About Team section with Mission, Vision, and academic statement.
   - 6-step Agile–DevOps workflow with visual pipeline ribbon (`Plan → Code → Commit → Build → Test → Review → Deliver`) and interactive terminal simulator.
   - 10 Tools & Technologies cards.
   - 4 Benefits cards.
   - Minimal footer with dynamically generated copyright year.

---

## 🛠️ Technology Stack

- **HTML5:** Semantic document structure and accessibility attributes.
- **CSS3:** Custom stylesheet with theme variables, exact gradient arc, card layouts, and responsive media queries.
- **JavaScript (ES6+):** Form validation, scrollspy active link tracking, mobile navbar auto-close, dynamic year, and interactive pipeline simulation.
- **Bootstrap 5 (v5.3.3):** 12-column responsive layout grid.
- **Bootstrap Icons (v1.11.3):** Recognizable iconography.

---

## 📂 File Structure

```
Tech Matrix/
├── index.html          # Main single-page portfolio application
├── README.md           # Project documentation and guide
├── css/
│   └── style.css       # Custom stylesheet matching the reference model
└── js/
    └── script.js       # Client-side validation, interactive pipeline simulator, scrollspy
```

---

## 🚀 How to Open and View

### Option 1: Direct File Opening
Double-click `index.html` or open it directly in any browser:
```
file:///E:/anitgravity/Tech%20Matrix/index.html
```

### Option 2: Live Server or Local HTTP Server
Run from the project folder:
```bash
python -m http.server 9090
```
Then navigate to `http://localhost:9090` in your browser.
