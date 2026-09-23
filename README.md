# Natours
A responsive tour agency landing page built with **HTML5**, **CSS3**, and **Sass (SCSS)**, created as a hands-on project while completing the **"Advanced CSS and Sass: Flexbox, Grid, Animations and More!"** course by Jonas Schmedtmann on Udemy.
The project focuses on advanced CSS techniques — Sass architecture, CSS animations, 3D transforms, responsive design, and modern layout methods (Flexbox & CSS Grid).

---

## Live Demo
🔗 (https://natours-1el7ll85h-nayrasoliman02-7939s-projects.vercel.app/)

---

## Features

- **Responsive Design**
  - Fully responsive layout across mobile, tablet, and desktop breakpoints using media queries.
  - Custom root font-size scaling (rem-based sizing) for consistent responsiveness.
- **Sass Architecture**
  - Organized SCSS files using the **7-1 pattern** (abstracts, base, components, layout, pages).
  - Use of Sass variables, mixins, nesting, and partials for maintainable styles.
- **Animations & Interactions**
  - CSS `@keyframes` entrance animations (heading slide-in, button fade/slide-up).
  - Pure CSS circular navigation menu using the **checkbox hack** (no JavaScript).
  - 3D flip animation on tour pricing cards (`transform: rotateY()` with `perspective`).
  - Hover micro-interactions: image composition effects, feature box lift, button shadows.
  - `:target`-based popup/modal for the booking confirmation.
- **Modern Layout**
  - CSS Grid used for section and card layouts.
  - `clip-path` used for diagonal section edges and image cuts.
- **Sections**
  - Hero header, About, Features, Popular Tours (pricing cards), Testimonials (with background video), Booking form, Footer, and Booking popup.

---

## Tech Stack
- **Markup**: HTML5
- **Styling**: CSS3, Sass (SCSS)
- **Icons**: Font Awesome
- **Fonts**: Google Fonts (Lato)
- **Deployment**: Vercel

---

## Installation

### 1. Clone the repository
```bash
git clone https://github.com/Nayra-04/Natours.git
cd Natours
```

### 2. Install Sass (if not already installed)
```bash
npm install -g sass
```

### 3. Compile SCSS to CSS
```bash
sass sass/main.scss css/style.css --watch
```

### 4. Open the project
Open `index.html` directly in your browser, or serve it with a live server extension for automatic reload.

---

## Project Structure
```
Natours/
├── img/                # Images, icons, and background video
├── sass/               # Sass source files (7-1 architecture)
│   ├── abstracts/      # Variables, mixins, functions
│   ├── base/           # Base/reset styles, typography, animations
│   ├── components/     # Reusable UI components (buttons, cards, forms...)
│   ├── layout/         # Layout-level styles (header, footer, navigation, grid)
│   └── main.scss       # Main Sass entry file
├── css/
│   └── style.css       # Compiled CSS output
└── index.html
```

---

## Project Goal
This project was built to practice and apply advanced CSS and Sass concepts learned in Jonas Schmedtmann's course — including Sass architecture, CSS animations, 3D transforms, and fully responsive, mobile-first design — by rebuilding the Natours landing page from scratch.
