# 24-Hour Code Challenge – Web Shop Frontpage

## Project Overview
This project is the implementation of a **responsive front page for a web shop**.  
It was built as part of a **24-hour code challenge** to showcase skills in **HTML and SCSS**.

- **Goal:** Build a pixel-perfect front page based on the provided Sketch/InVision wireframe.
- **Scope:** Only the homepage is implemented.
- **Technologies Used:**  
  - HTML5  
  - SCSS (Sass)  
  - Pure CSS Flexbox & Grid for layout and responsiveness  
  - JavaScript (optional, if interactions like carousels are used)  

---

## Project Structure

project-root/
│
├─ assets/                  # Images and media used in the page
│   ├─ bamboo.png
│   ├─ blank-stars.png
│   ├─ cart.png
│   ├─ centella.png
│   ├─ charcoal.png
│   ├─ check.png
│   ├─ cleanser.png
│   ├─ cleanser2.png
│   ├─ clock.png
│   ├─ d1-skincare.png
│   ├─ d1-white.png
│   ├─ d1.png
│   ├─ facebook.png
│   ├─ hyaluronic.png
│   ├─ instagram.png
│   ├─ leaf.png
│   ├─ men.png
│   ├─ moisturizer.png
│   ├─ moisturizer2.png
│   ├─ mute.png
│   ├─ niacinamide.png
│   ├─ ocean.png
│   ├─ ocean2.png
│   ├─ pic1.png
│   ├─ pic2.png
│   ├─ pic3.png
│   ├─ playbutton.png
│   ├─ products.png
│   ├─ result.png
│   ├─ rose.png
│   ├─ setproduct.png
│   ├─ sky.png
│   ├─ stars.png
│   ├─ step1.png
│   ├─ step2.png
│   ├─ step3.png
│   ├─ stick.png
│   ├─ stick2.png
│   └─ tiktok.png
│
├─ scss/                    # SCSS files for styling
│   ├─ _homepage.scss       # Main SCSS for homepage layout
│   ├─ _mixins.scss         # Optional mixins (currently empty)
│   └─ main.scss            # SCSS entry point (compiled to main.css)
│
├─ index.html               # Homepage
├─ README.md                # Project instructions
└─ ...                      # Other necessary files


## Usage

1. Clone the repository:

--bash
git clone <repository-url>


2. Open index.html in your browser to view the homepage.

3. To compile SCSS to CSS (if needed):
sass scss/main.scss css/main.css


Features

Pixel-perfect design based on the provided wireframe

Fully responsive across desktop, tablet, and mobile

Sections implemented include:

Hero section

Routine section

Features section

Testimonials

Footer

SCSS modularity:

_homepage.scss for page-specific styles

_mixins.scss for reusable mixins (currently empty)

Clean, maintainable code with semantic naming conventions



Notes

Only the homepage is implemented; other pages are placeholders.

You can replace images in assets/ to customize the page.

No CSS frameworks like Foundation were used; all layout and responsiveness were manually implemented.

All images are located in the assets/ folder and linked in HTML.

Feel free to replace images in the assets/ folder to customize the page.