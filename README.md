# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Author](#author)



### Links

- Solution URL: [SOLUTION REPO](https://github.com/noob-coder6/Recipe-page.git)
- Live Site URL: [LIVE SITE URL](https://noob-coder6.github.io/Recipe-page/)


### Built with

- Semantic HTML5 markup
- CSS custom properties
- Responsive design
- Google Fonts (Outfit & Young Serif)
- Mobile-first workflow

### What I learned

Working on this recipe page helped me improve my understanding of:

- **CSS Custom Properties**: Used CSS variables to maintain a consistent color scheme throughout the project
```css
:root {
  --color-nutmeg: hsl(14, 45%, 36%);
  --color-dark-raspberry: hsl(332, 51%, 32%);
}
```

- **Semantic HTML**: Structured the recipe content using appropriate semantic elements like `<section>`, `<main>`, and proper heading hierarchy

- **List Styling**: Customized list markers to match the design aesthetic
```css
li::marker {
  color: var(--color-nutmeg);
  font-weight: bold;
}
```

- **Responsive Design**: Implemented mobile-first approach with media queries to ensure the recipe page looks great on all devices

### Continued development

In future projects, I want to continue focusing on:

- Advanced CSS layout techniques
- Accessibility best practices
- Performance optimization for web fonts and images
- Creating more complex responsive designs

## Author

- Frontend Mentor - [@noob-coder6](https://www.frontendmentor.io/profile/noob-coder6)