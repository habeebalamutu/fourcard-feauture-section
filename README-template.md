# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid and Flexbox
- Mobile-first workflow
- [Poppins](https://fonts.google.com/specimen/Poppins) font from Google Fonts

### What I learned

During this project, I learned how to:

- Use CSS Grid to create complex, responsive layouts that adapt to both desktop and mobile screens.
- Apply CSS custom properties (variables) for consistent color and style management.
- Utilize media queries to adjust layout and spacing for different device widths.
- Structure HTML for accessibility and maintainability.
- Integrate SVG icons and external fonts for a polished UI.

Example: Using CSS Grid for the feature cards layout

```css
.features {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-template-rows: repeat(2, 1fr);
  gap: 2rem;
}
@media (max-width: 900px) {
  .features {
    grid-template-columns: 1fr;
    grid-template-rows: none;
    gap: 1.5rem;
  }
}
```

## Acknowledgments

Thanks to [Frontend Mentor](https://www.frontendmentor.io/) for the challenge and community feedback.