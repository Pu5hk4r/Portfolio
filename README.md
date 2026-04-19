# Personal Portfolio

A modern, responsive personal portfolio website showcasing my projects, skills, and resume. The web app is designed with a sleek, dark-themed UI and features a fully interactive 3D physics simulation built with Three.js.

![](https://github.com/Pu5hk4r/Portfolio/blob/main/pushkar1.png)
![](https://github.com/Pu5hk4r/Portfolio/blob/main/particle.mp4)

🔗 **[Live Demo](https://portfolio-alpha-one-d21sm830b1.vercel.app/)**

## ✨ Features

- **Dynamic Hero Section**: Interactive background and bold typography that establishes a strong first impression.
- **Project Showcase**: A detailed grid highlighting core projects (e.g., CODEREVIEW-AI-AGENT, RealTime Taxi Pipeline, Smart Bank Loan System) complete with architecture diagrams, relevant tech stack tags, and links.
- **Interactive "Lab" / Particle Collider**: A fun physics simulation built using **Three.js**. Visitors can tweak speed and power to create particle collisions with accompanying sound effects and plasma bursts.
- **Modern UI/UX**: Built with a sleek dark-themed palette, smooth scrolling, scroll-reveal animations, responsive navigation, and glassmorphism styling.
- **Working Contact Form**: Integrated with Formspree for immediate, serverless message handling that delivers straight to the designated email inbox.

## 🛠️ Technology Stack

- **HTML5**: Semantic structure.
- **CSS3 / Variables**: Custom responsive design, flexbox/grid layouts, animations, and transitions without relying on external heavy frameworks.
- **JavaScript (ES6+)**: Functional logic for mobile menus, intersection observers (scroll reveals), contact API requests, etc.
- **Three.js (WebGL)**: Interactive 3D graphics rendering in the browser for the "Particle Collider" game.

## 🚀 Setup & Local Development

This is a static site. No heavy build tools or bundlers are required.

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Pu5hk4r/Portfolio.git
   cd Portfolio
   ```

2. **Run locally:**
   You can run it using any simple local web server. For example, with Python installed:
   ```bash
   python -m http.server 8000
   ```
   Alternatively, you can simply open `index.html` in your favorite web browser.

3. **Contact Form Setup**:
   The contact form uses Formspree. Remember to ensure that your own Formspree ID is set in the `<form action="...">` tag inside the HTML file to receive messages correctly.

## 👤 Author

**Pushkar**
- AI Engineer & Full Stack Python Developer
- **GitHub**: [@Pu5hk4r](https://github.com/Pu5hk4r)
- **LinkedIn**: [in/pushkar25](https://linkedin.com/in/pushkar25)
- **Email**: pushstack25@gmail.com

---
*Built from scratch using vanilla web technologies and Three.js.*
