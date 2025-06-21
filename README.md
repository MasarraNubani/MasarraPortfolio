# MasarraPortfolio
This project is a professional, responsive portfolio homepage that demonstrates modern web development skills, accessibility best practices, and clean, scalable CSS architecture using SCSS and the BEM methodology.

---

## What’s Included?

- **Navigation Header:**  
  - A fixed navbar at the top of the page with links (Projects, Skills, Resume, Contact) that shrinks on scroll.
  - Fully responsive for desktop and mobile screens.

- **Intro Banner:**  
  - Includes a profile or avatar image, your name, a short bio, and two prominent call-to-action buttons.
  - Layout adapts: side-by-side on large screens, stacked on mobile.

- **Latest Projects:**  
  - Displays three project cards (each with an image, title, and description) and a main action button below.
  - Interactive hover effects on the cards.

- **Footer:**  
  - Simple footer with copyright.

- **Accessibility:**  
  - Markup and styles follow accessibility best practices, including keyboard navigation and color contrast.

---

## Project Structure
starter/
├── dist/
│ └── main.css # Compiled CSS from SCSS
├── src/
│ ├── img/ # All images (profile, background, projects)
│ ├── scss/ # SCSS files (BEM-based organization)
│ │ ├── base/
│ │ ├── blocks/
│ │ ├── utils/
│ │ └── main.scss
│ └── index.html # The main homepage file
├── package.json # Project dependencies and build scripts
└── package-lock.json # Exact versions for dependencies

---

## How to Run the Project

1. **Install dependencies:**  
   In the `starter` folder, run:

2. **Build or watch SCSS:**  
- To build CSS once:
  ```
  npm run build
  ```
- To auto-compile on changes:
  ```
  npm run watch
  ```

3. **View the homepage:**  
Open `src/index.html` in your browser, or use an extension like **Live Server** in VS Code for automatic reloading.

---

> You can easily customize the content, images, and style to reflect your personal brand and skills!
<img width="949" alt="image" src="https://github.com/user-attachments/assets/00d2d25b-b0c5-4f2e-b872-352f13ba9972" />


