# Week 2: CSS Mastery

## Author
- **Name:** Catherine Nduku
- **GitHub:** [Ndush-gif](https://github.com/Ndush-gif)
- **Date:** October 28, 2026

## Project Description
This week I took my Week 1 HTML portfolio and styled it into a responsive website that works on phones, tablets and desktops. It has a home page, an About page, a Projects page and a Contact page, all sharing the same navigation, colors and typography. I also built three practice pages (box model, flexbox and grid) and five daily challenges (buttons, a card, a hero section, a styled form and a footer).

## Technologies Used
- HTML5
- CSS3 (custom properties, Flexbox, Grid, media queries)
- Google Fonts (Poppins and Open Sans)
- Coolors (to build the color palette)
- Chrome DevTools (box model inspector and device toolbar)
- Git and GitHub
- VS Code
- GitHub Pages

## Features
- A reset, a typography system and a color scheme built with CSS variables in `:root`
- A mobile-first navigation bar: a CSS-only hamburger menu on phones and a horizontal Flexbox menu from 768px up
- A home page hero that is one column on mobile and text with a side image on desktop
- A Projects page with a CSS Grid of cards: 1 column on mobile, 2 on tablet and 3 on desktop
- A Contact page with a full-width form on mobile and a form with a sidebar on desktop
- Hover states, smooth transitions and visible focus outlines for keyboard users
- Practice pages: `box-model-practice.html`, `flexbox-practice.html` and `grid-practice.html`
- Five daily challenges in the `daily-challenges` folder: `button-styles-day-1.html`, `card-component-day-2.html`, `hero-section-day-3.html`, `form-styling-day-4.html` and `footer-design-day-5.html`

## How to Run
1. Clone this repository
2. Open `index.html` in your browser, or use the Live Server extension in VS Code

## Lessons Learned
- `box-sizing: border-box` makes `width` include the padding and border, so layouts are predictable. Without it, a 300px box with 20px padding becomes 340px wide.
- Flexbox lays items out in one direction, and Grid controls rows and columns together, so I use Flexbox for the navbar and card rows and Grid for galleries and page layouts.
- Mobile-first means writing the phone layout as the base and adding `min-width` media queries as the screen gets bigger.
- CSS variables keep the fonts and colors in one place, so changing one value updates the whole site.
- A rule with a class selector beats a plain tag selector, which is how my button classes override the general `button` styles.
- Focus styles matter for accessibility, because keyboard users rely on them to see where they are.
- `:invalid` with `:not(:placeholder-shown)` lets a form show errors only after someone has typed.

## Challenges Faced
- My 300px box measured 340px wide. I found the cause with the DevTools box model diagram and fixed it with `box-sizing: border-box`.
- My body text stayed in Times New Roman because of a missing comma in `font-family`, and a `margin-bottom` without a unit was ignored. CSS skips a whole line when it has a mistake, so I learned to check for missing punctuation and units.
- The images on my Projects page were broken because I had not copied the `images` folder into my Week 2 folder.
- I pasted the contact page code into `index.html` by mistake, so my home page showed the contact form. I fixed it by replacing the file with the correct home page code.
- My new navigation styles did nothing at first because they had not been saved to `style.css`, and DevTools showed me the rules were missing.


## Live Demo
[View Live Demo](https://ndush-gif.github.io/iyf-s12-week-02-Ndush-gif/)
