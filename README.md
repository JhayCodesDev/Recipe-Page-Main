# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview
The goal of this challenge is to build a clean and responsive recipe page that closely matches the provided design.

In this solution, I applied:

Semantic HTML structure to ensure accessibility and improve readability.

Container and sub-container classes to organize the layout and structure content clearly.

Basic CSS styling for typography, colors, and spacing to align with the design mockup.

Responsive design with media queries to ensure the page works well on smaller screens (down to 320px).

Consistent CSS organization for easier updates and scalability.

This challenge was a valuable opportunity to practice structuring layouts with containers, applying responsive styles, and refining attention to detail when converting a design into code.

### Screenshot

![Recipe page screenshot for desktop](./Screenshot%202025-09-02%20at%2017-53-42%20Frontend%20Mentor%20Recipe%20page.png)
![Recipe page screenshot for mobile](./Screenshot%202025-09-02%20at%2017-54-06%20Frontend%20Mentor%20Recipe%20page.png)

### Links

- Solution URL: [My Frontend Mentor Solution](http://127.0.0.1:5500/index.html)
- Live Site URL: [View live site here](https://JhayCodesDev.github.io/Recipe-Page-Main/)

## My process.
1. Setup

Downloaded the starter files and extracted them into a new project folder named recipe-page-main.

Reviewed the provided documents (style-guide.md, README-template.md, README.md, and design mockups) to understand the requirements.

2. Structure

Built the HTML structure with semantic tags (header, main, section, footer) to match the design layout.

Organized the project files by creating an assets/css folder and linking the external stylesheet to the HTML file.

3. Styling

Linked the custom fonts provided in the style guide (this was my first time linking downloaded fonts directly, as I was only familiar with Google Fonts before).

Added base styles for the body, headings, and containers.

Styled each section in order:

Recipe header & image container

Preparation time block

Ingredients list

Instructions (ordered list)

Nutrition section (styled with table rows and cells)

Added attribution styling at the bottom of the page.

Responsiveness

I used a desktop-first approach, designing for larger devices first and then applying media queries to optimize the layout for smaller screens (between 320px and 767px).

Adjusted font sizes, spacing, and alignment to closely match the design mockups.

4. Finishing Up

Cleaned up the CSS by grouping selectors logically.

Tested the page at different screen sizes to ensure responsiveness.

Wrote the README and prepared the project for deployment.

### Built with

- Semantic HTML5 markup
- Flexbox for layout (body and sections) 
- CSS custom properties  
- Container-based layout (using wrappers and sub-wrappers for structure)  
- Desktop-first workflow (styled larger screens first, then optimized for smaller ones 320px–767px)  
- Responsive design techniques 


### What I learned

One of the key things I learned in this project was how to link downloadable fonts using the @font-face rule.
Instead of relying on Google Fonts, I imported the fonts locally from the project’s assets folder.

For example:

@font-face {
  font-family: 'Outfit';
  src: url(/assets/fonts/outfit/static/Outfit-Regular.ttf) format('truetype');
  font-weight: 400;
  font-style: normal;
}

@font-face {
  font-family: 'Young Serif';
  src: url(/assets/fonts/young-serif/YoungSerif-Regular.ttf) format('truetype');
  font-weight: 400;
  font-style: normal;
}

Learnt how to insert images in a README file using Markdown syntax:

![Alt text](./path-to-image.png)

This helps in visually presenting project screenshots directly in documentation.


### Continued development

For future improvement, I’d like to:

- Explore @font-face more deeply, especially working with multiple font formats for better browser support.

- Learn and practice other CSS @rules such as  @supports (progressive enhancement), and @layer (cascade management).

- Build a small font showcase project to apply these learnings and strengthen my understanding of typography in web design.


### Useful resources
- [MDN Web Docs – @font-face](https://developer.mozilla.org/en-US/docs/Web/CSS/@font-face)  
  Helped me understand how to properly use `@font-face` to load local fonts and control font weights.  

- [CSS-Tricks – Using @font-face](https://css-tricks.com/snippets/css/using-font-face/)  
  A simple guide that explains different formats and when to use them.  

- [MDN Web Docs – Responsive design with media queries](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Media_queries)  
  Useful when styling for different screen sizes.  


## Author

- Website - [@JhayCodesDev](https://github.com/JhayCodesDev)
- Frontend Mentor - [@yJhayCodesDev](https://www.frontendmentor.io/profile/JhayCodesDev)
- Twitter - [@JhayCodes](https://www.twitter.com/JhayCodes)

## Acknowledgments
Thanks to Frontend Mentor for providing such practical and challenging projects.

Grateful to resources like MDN Web Docs and CSS-Tricks, which continue to be invaluable references.
