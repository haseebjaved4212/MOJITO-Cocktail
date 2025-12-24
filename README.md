<div align="center">
  <br />
    <a href="https://www.youtube.com/watch?v=AW1yfBKRMKc" target="_blank">
      <img src="public/readme/hero.png" alt="Project Banner">
    </a>
  <br />

   <div>
    <img src="https://img.shields.io/badge/-React-blue?style=for-the-badge&logo=react&logoColor=white" />
    <img src="https://img.shields.io/badge/-GSAP-88CE02?style=for-the-badge&logo=greensock&logoColor=white" />
    <img src="https://img.shields.io/badge/-Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" />
  </div>

  <h2 align="center">Stunning GSAP Cocktail Website</h2>
</div>
A responsive, animation-focused demo website built with React, Tailwind CSS and GSAP. This project demonstrates advanced scroll-driven animations (ScrollTrigger), pinned sections, parallax effects, and custom timeline interactions — wrapped in a cocktail-themed landing experience.

**Table of Contents**

- **Project**: Short description and purpose.
- **Features**: What this demo shows.
- **Tech Stack**: Libraries and tools used.
- **Getting Started**: Install, run, and build steps.
- **Project Structure**: Important files and folders.
- **Customization**: How to change assets and behavior.
- **Deployment**: Quick build and host instructions.
- **Contributing & Support**: How to report issues or contribute.

**Project**

- **Purpose**: Showcase how GSAP can be integrated with React and Tailwind CSS to build immersive, scroll-driven UIs.
- **Use case**: Educational demo, portfolio piece, or starting scaffold for animation-heavy microsites.

**Features**

- **Scroll-driven animations**: Timelines triggered by scroll using `gsap` and `ScrollTrigger`.
- **Pinned sections & parallax**: Lock sections while content animates for cinematic effects.
- **Scroll-synced media**: Video or image sequences that progress with scroll position.
- **Custom animated carousel**: A component that demonstrates timeline-based slide transitions.
- **Responsive layout**: Built with Tailwind CSS for mobile-first responsiveness.

**Tech Stack**

- **React**: Component-driven UI.
- **GSAP**: Animation engine (`gsap`, `@gsap/react`).
- **Tailwind CSS**: Utility-first styling.
- **Vite**: Dev server and build tool.

**Getting Started**
Follow these steps to run the project locally on Windows (PowerShell) or other shells.

- **Clone the repository**

  - `git clone https://github.com/haseebjaved4212/MOJITO-Cocktail.git`
  - `cd MOJITO-Cocktail`

- **Install dependencies**

  - `npm install`

- **Run in development mode**

  - `npm run dev`
  - Open `http://localhost:5173` in your browser (Vite default port).

- **Build for production**
  - `npm run build`
  - Preview a production build: `npm run preview`

These scripts are defined in `package.json` (`dev`, `build`, `preview`).

**Project Structure (high level)**

- **`src/`**: React source files.
  - `main.jsx` — app entry.
  - `App.jsx` — top-level app.
  - `index.css` — global styles.
  - `components/` — UI sections (`Hero.jsx`, `Cocktails.jsx`, `Menu.jsx`, `Contact.jsx`, etc.).
- **`public/`**: Static assets (fonts, images, videos, readme images).
- **`constants/`**: Shared constants used across components.
- **`vite.config.js`**: Vite configuration.

**Customization**

- Replace images/videos in `public/images/` and `public/videos/` to change visuals.
- Edit component markup in `src/components/` to adjust layout and content.
- Modify animation timelines inside components where `gsap` is used (look for imports from `gsap` or `@gsap/react`).

**Deployment**

- Build: `npm run build`.
- Deploy the contents of the `dist/` folder to any static host (Netlify, Vercel, GitHub Pages, Surge, etc.).
- For Netlify/Vercel: point the build command to `npm run build` and the publish directory to `dist`.

**Troubleshooting**

- If animations do not play, ensure your browser supports modern web APIs and that you have no extension blocking scripts.
- If the local server does not start, confirm Node.js and npm versions (`node -v`, `npm -v`).

**Credits & Inspiration**

- This demo is inspired by community tutorials and examples that show GSAP + React patterns. If you used a specific tutorial or asset pack, keep credit in the `public/readme/` images or code comments.

**Contributing**

- Found a bug or want to add a feature? Open an issue or submit a pull request.
- Keep changes focused and include a short description of the problem you are fixing.

**Contact & Support**

- Use the repository Issues page for bugs or questions.

**License**

- This project is open source and available For modification and distribution.

---

If you'd like, I can also:


- Add a short CONTRIBUTING.md with PR guidelines.
- Create a small `DEMO.md` showing where to swap assets and tweak timelines.



<h3 align="center">Happy Coding 💖</h3>
