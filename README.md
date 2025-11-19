MYBIKE Landing Page

A responsive landing page developed as part of the Mate Academy Frontend program.
The project reproduces the original Figma design and demonstrates skills in semantic HTML, modular SCSS, adaptive layout, reusable UI components, and modern tooling with Parcel bundler.

Features

Pixel-perfect layout based on the Figma specification

Fully responsive layout (mobile/tablet/desktop)

Modular SCSS architecture with partials and BEM methodology

Parcel bundler for fast development, hot reloading, and optimized production builds

Clean and maintainable folder structure

Interactive navigation and UI states

Responsive images for performance

Styled contact form and reusable components

Technologies Used

HTML5

SCSS (Sass)

JavaScript (ES6)

Parcel (bundler/microprocessor)

Git / GitHub Pages

Preview

Live Demo: https://deny-hl.github.io/layout_landing-page/


Project Structure
src/
│
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
│
├── scripts/
│   └── main.js
│
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
│   │
│   ├── utils/
│   │   ├── mixins.scss
│   │   ├── variables.scss
│   │   └── main.scss
│   │
│   └── main.scss
│
└── index.html


Installation & Setup
1. Clone the repository
  git clone https://github.com/deny-hl/layout_landing-page.git
  cd layout_landing-page
2. Install dependencies
  npm install
3. Start the development server
  npm start

Parcel will:

start a local dev server

enable hot module replacement

rebuild automatically on changes

5. Build for production
  npm run build

Parcel generates an optimized dist/ folder with:

minified assets

hashed filenames

cleaned output

Deployment (GitHub Pages)

Run the production build

Push the contents of dist/ to your deployment branch

GitHub Pages will serve the build automatically

About the Project

This landing page was created as a portfolio assignment for Mate Academy.
It focuses on:

Implementing responsive UI from design

Building scalable SCSS structure

Writing modular, readable frontend code

Using Parcel as a modern bundler

Practicing production deployment on GitHub Pages

Following industry-standard frontend workflow
