<div align="Center">
<img width="320" alt="Image" src="https://github.com/user-attachments/assets/a216c3f2-c9b8-4272-a243-46ff2f0dbe11" />

# Quartet: Simpsons-Inspired Team Portfolio
  <img src="https://img.shields.io/badge/Theme-Simpsons%20Cartoon-FFD93D?style=for-the-badge&labelColor=2C2C2C" alt="Simpsons Theme" />
  <img src="https://img.shields.io/badge/Team-4%20Creative%20Members-FF9A00?style=for-the-badge&labelColor=4F200D" alt="4 Members" />
  <img src="https://img.shields.io/badge/Stack-HTML5%20%2F%20CSS3%20%2F%20JS-4F200D?style=for-the-badge&labelColor=FFD93D" alt="Stack" />

<br>

<p> 
<em>Welcome to <strong>Quartet</strong>.</em>

<sub>An interactive, high-fidelity team web portfolio designed to showcase a four-person creative collective. The visual identity, layout, and color palette of this project are deeply inspired by the iconic <strong>Simpsons cartoon aesthetic</strong>, translating a playful classic style into a sleek, premium, and modern digital portfolio.
Whether you are looking to hire a full team or seeking design inspiration, Quartet represents the fusion of cartoon nostalgia and cutting-edge web design.
</sub>
</p>

</div>

## 🐝 The Simpsons Inspiration & Design Concept

This project demonstrates how a highly recognizable cartoon aesthetic can be adapted into a professional, modern user interface. Instead of resorting to loud or childish designs, Quartet elevates the theme using premium UI patterns:

### 1. Color Palette (Simpsons Colors)
The custom style variables map directly to Springfield's most famous color signatures:
* **Simpson Yellow (`#FFD93D`)**: Prominently featured as the primary accent, drawing immediate focus to brand elements and key interactions.
* **Simpson Orange (`#FF9A00`)**: Used for background glows, gradients, and secondary highlights.
* **Deep Brown (`#4F200D`)**: Taken from the outline of character models, hair, and shadow details, serving as the main typography base, buttons, and border accents.
* **Off-white (`#F3F4F4`)**: Acts as a neutral background canvas, ensuring the brighter palette remains balanced and highly readable.
* **Charcoal (`#2C2C2C`)**: Used for crisp outlines and primary headings.

### 2. Cartoon Print Texture
The UI implements a subtle overlay system using an SVG noise filter:
* A `feTurbulence` fractal noise SVG is applied as a fixed body overlay at low opacity (`.022`).
* This mimics vintage comic book prints and old CRT television screens, adding physical depth to the digital environment.

### 3. Springfield Atmosphere
The page background features radial gradients reminiscent of the pastel, sunny skies of Springfield, creating a natural backdrop for the team cards.

## 👥 Meet the Quartet

The portfolio is structured around four unique creative personas, each represented by a dedicated card slide in the gallery track:

| Portrait | Name | Role | Primary Skills & Tools |
| :--- | :--- | :--- | :--- |
| `aldino.png` | **Aldino** | Creative Developer & Designer | Figma, React, Motion Design |
| `bagus.png` | **Bagus** | Product Engineer & Strategist | TypeScript, Node.js, System Design |
| `hawwin.png` | **Hawwin** | Motion Designer & Illustrator | After Effects, Illustrator, Lottie |
| `yardan.png` | **Yardan** | Backend Architect & DevOps | Laravel, Docker, PostgreSQL |

## 💛 Key Features

* **Dynamic Carousel Stage**: A smooth, transform-based card slider with custom hardware-accelerated transitions.
* **Multi-modal Navigation**:
  * On-screen Arrow Buttons (Previous/Next)
  * Clickable Dot Indicators corresponding to each member
  * Keyboard support (Left/Right arrow keys)
  * Mobile swipe gestures (touch start/end track listener)
* **Design Tokens & System**: Standardized spacing, border-radii, color tokens, and shadow presets coded natively in CSS variables for easy maintenance.
* **Call to Action & Connectors**: Each member's card features dedicated resume download links and social triggers (GitHub, LinkedIn, Instagram, Email).

## 📂 Repository Structure

The codebase is designed to be lightweight, fast, and entirely self-contained:
* [index.html](file:///D:/Dev/Projects/Team-WebPortfolio/index.html) — Contains the semantic HTML markup, embedded CSS stylesheet (with extensive Simpson-themed design tokens), and JavaScript logic for the slider transitions and interactive event handlers.
* `assets/` — Stores member portraits (`aldino.png`, `bagus.png`, `hawwin.png`, `yardan.png`) and vector icons.

## ⭐ Getting Started

Since the project uses vanilla HTML, CSS, and JavaScript with no external build dependencies, running the application is straightforward:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/RockHead07/Team-WebPortfolio.git
   ```
2. **Open index.html**:
   * Double-click [index.html](file:///D:/Dev/Projects/Team-WebPortfolio/index.html) to open it directly in your web browser.
   * Or run a simple local web server (e.g., using VS Code Live Server or python's `http.server` module):
     ```bash
     python -m http.server 8000
     ```
     Then navigate to `http://localhost:8000`. 