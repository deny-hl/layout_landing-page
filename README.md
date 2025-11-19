# MYBIKE Landing Page

MYBIKE is a responsive landing page developed within the Mate Academy Frontend program. The project reproduces the original Figma design and demonstrates semantic HTML, modular SCSS, adaptive layout techniques, reusable UI components, and modern tooling with Parcel bundler.

## Features
- Pixel-perfect layout that matches the Figma specification
- Fully responsive across mobile, tablet, and desktop breakpoints
- Modular SCSS architecture using partials and BEM
- Parcel bundler for fast dev server, HMR, and optimized production builds
- Clean, maintainable folder structure for assets, scripts, and styles
- Interactive navigation states and reusable UI components
- Responsive imagery tuned for performance
- Styled contact form with accessible inputs and validation cues

## Technologies Used
- HTML5
- SCSS (Sass)
- JavaScript (ES6)
- Parcel
- Git / GitHub Pages

## Preview
- Live Demo: [https://deny-hl.github.io/layout_landing-page/](https://deny-hl.github.io/layout_landing-page/)
- Figma Design: [https://www.figma.com/design/NZQAIydtHo5QkINyGLHNcq/BIKE-New-Version?node-id=0-1&p=f&t=TnRoAFO1anDesFf5-0](https://www.figma.com/design/NZQAIydtHo5QkINyGLHNcq/BIKE-New-Version?node-id=0-1&p=f&t=TnRoAFO1anDesFf5-0)

## Project Structure
```
src/
├── images/
│   ├── icons/
│   ├── product/
│   ├── footer-bg.png
│   ├── header-bg-mobile.png
│   ├── header-bg-mobile-2x.png
│   ├── logo-black.png
│   ├── logo-black-2x.png
│   ├── logo-white.png
│   └── logo-white-2x.png
├── scripts/
│   └── main.js
├── styles/
│   ├── blocks/
│   │   ├── button.scss
│   │   ├── contact.scss
│   │   ├── details.scss
│   │   ├── footer.scss
│   │   ├── header.scss
│   │   ├── icon.scss
│   │   ├── intro.scss
│   │   ├── main.scss
│   │   ├── menu.scss
│   │   ├── nav.scss
│   │   ├── page.scss
│   │   ├── product.scss
│   │   ├── recommended.scss
│   │   ├── section-title.scss
│   │   └── top-bar.scss
│   ├── utils/
│   │   ├── mixins.scss
│   │   └── variables.scss
│   └── main.scss
└── index.html
```

## Installation & Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/deny-hl/layout_landing-page.git
   cd layout_landing-page
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm start
   ```

Parcel will:
- start a local development server
- enable hot module replacement
- rebuild automatically when files change

4. Build for production:
   ```bash
   npm run build
   ```
   Parcel outputs an optimized `dist/` directory with:
   - minified assets
   - hashed filenames for caching
   - cleaned, production-ready HTML/CSS/JS

## Deployment (GitHub Pages)
1. Run the production build: `npm run build`
2. Push the contents of `dist/` to the GitHub Pages branch (e.g., `gh-pages`)
3. GitHub Pages will serve the build automatically

## About the Project
This landing page was created as a portfolio assignment for Mate Academy with the goals of:
- Implementing responsive UI directly from the design system
- Building a scalable SCSS structure with reusable blocks
- Writing modular, readable frontend code with ES6
- Using Parcel as a modern bundler for development and production
- Practicing deployment workflows with GitHub Pages and CI-ready scripts

Practicing production deployment on GitHub Pages

Following industry-standard frontend workflow
