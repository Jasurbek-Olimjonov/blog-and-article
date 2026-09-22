# Blog List Page

A food blog list / magazine-style landing page built as a front-end practice project, focused on translating a design into a pixel-close layout using Bootstrap's utility classes and SASS.

## Live Demo
[View live site](https://jasurbek-olimjonov.github.io/food-market1-blog-list-page/)

## Overview
This project recreates a full-page food blog layout — hero section, article content, a call-to-action subscribe block, and a recipe card grid — using Bootstrap 5 as the primary framework, extended with custom SASS where Bootstrap's utilities fell short.

## Tech Stack & Approach
Built primarily with Bootstrap (flex and positioning utilities) to deepen hands-on experience with the framework. Custom SCSS handles the parts Bootstrap's utilities couldn't cleanly express — typography, sizing, and fine-grained positioning.

## What I Practiced
- Deciding when to reach for a utility class vs. writing custom SASS
- Positioning elements precisely within their containers using `flex`, `position`, and `translate-middle` utilities
- Centering and aligning overlapping elements (like images and badges) using Bootstrap's `translate-middle` class combined with `position-absolute`

## Project Structure
```
food-market1-blog-list-page/
├── assets/
│   ├── images/
│   └── svg/
├── styles/
│   ├── sections/
│   ├── utils/
│   │   ├── _mixins.scss
│   │   ├── _utilities.scss
│   │   └── _variables.scss
│   ├── style.css
│   ├── style.css.map
│   └── style.scss
├── LICENSE
├── README.md
└── index.html
```

## Getting Started
Clone the repo and open `index.html` in your browser — or, if you're editing the SASS:
```bash
git clone https://github.com/Jasurbek-Olimjonov/food-market1-blog-list-page.git
cd food-market1-blog-list-page
# compile SASS if using a live-sass-compiler or similar
```

## Author
**Jasurbek Olimjonov**
[GitHub](https://github.com/Jasurbek-Olimjonov)

## License
This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.
