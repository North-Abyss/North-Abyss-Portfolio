
# Portfolio 🌌

A futuristic, highly interactive personal portfolio website designed for **Yuvanesh KS**, bridging the gap between **Linux System Administration** and **Data Engineering**.

Live Demo: [https://north-abyss.github.io/Portfolio/](https://north-abyss.github.io/Portfolio/)

## 📖 About The Project

This portfolio features a "Deep Space" aesthetic with dynamic visual effects to showcase a transition from Game Development to Enterprise Infrastructure. It is built to be fast, responsive, and visually engaging without relying on heavy frameworks.

**Current Persona:**
* **Role:** System Architect & Data Engineer 🐧🚀
* **Focus:** Enterprise Linux (Rocky/Arch), Virtualization (KVM), and Big Data Pipelines (Databricks).
* **Key Projects:** Enterprise Home Lab, Caelestia Shell, SDN Analysis.

## ✨ Key Features

* **Matrix Rain Background:** A mesmerizing, animated background pattern using CSS animations, inspired by the Matrix code rain.
* **Theme Toggle:** Switch between **Deep Space (Dark)** and **Clean (Light)** modes. User preference is saved via Local Storage.
* **Glassmorphism UI:** Modern, translucent card designs with neon accents using `backdrop-filter`.
* **Interactive Elements:**
    * **Hovers:** Neon glows and scale effects.
    * **Typing Effect:** Dynamic role text animation in `script.js`.
    * **Profile Cards:** Dedicated previews for GitHub and LinkedIn integration.
* **Responsive Design:** Fully optimized for desktop and mobile viewing.

## 🛠️ Tech Stack

* **HTML5:** Semantic structure.
* **CSS3:** Custom variables, Grid/Flexbox, Keyframe animations (`@keyframes smooth-pulse`).
* **JavaScript (Vanilla):** Theme logic, local storage handling, and typing effects.
* **Hosting:** GitHub Pages.

## 🚀 Usage

Simply open `index.html` in any modern web browser to view the site locally.

```bash
# Clone the repo
git clone https://github.com/North-Abyss/Portfolio.git

# Navigate to directory
cd Portfolio

# Open locally (Linux)
xdg-open index.html
```

## 🎨 Customization

### Changing Colors

Edit the `:root` variables in `style.css` to match your preferred color scheme:

```css
:root {
    --accent-cyan: #00f3ff;  /* Primary Neon */
    --accent-purple: #bc13fe; /* Secondary Neon */
    --bg-deep: #05050a;       /* Background Base */
}
```

### Adjusting Matrix Effect

The matrix animation speed and colors can be tweaked in the `.jp-matrix` classes in `style.css`.

## 💎 Credits & Acknowledgments

* **Background Animation:** "Matrix Rain" by **solowzrd** via [Uiverse.io](https://uiverse.io/).
* **Theme Toggle:** Custom animated toggle switch inspired by designs on **Uiverse.io**.
* **Icons:** [Font Awesome](https://fontawesome.com/) for social links and UI elements.
* **Fonts:** 'Orbitron' and 'Inter' via [Google Fonts](https://fonts.google.com/).

---

*Created by [Yuvanesh KS](https://github.com/North-Abyss)*
