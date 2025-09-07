# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). 

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
This is a QR Code Card Component built using HTML and CSS as part of a Frontend Mentor challenge. The project displays a card centered on the page containing:

- A QR code image
- A heading encouraging users to improve their frontend skills
- A short description paragraph
- A small footer attribution

The layout is mobile-first, with a max-width card that adapts well to all screen sizes. The design uses flexbox for centering, Google Fonts (Outfit) for typography, and a clean, modern card style with rounded corners and a shadow for depth.

### Screenshot

![](./qr-code-component-main/images/Qr-card.png)

### Links

- Solution URL: (https://github.com/utsavi-code/project01)
- Live Site URL: (https://utsavi-code.github.io/project01/)

## My process

### 1. Planning
- Started by reviewing the challenge design on Figma.
- Identified the main structure: a centered card with an image, heading, description, and footer attribution.

### 2. Building the HTML
- Wrote semantic HTML with a `<main>` container for the card.
- Used `<h1>` for the main heading and `<p>` for description text.
- Added descriptive `alt` text to the QR image for accessibility.

### 3. Styling with CSS
- Applied a **mobile-first approach** by setting base styles for small screens.
- Used **flexbox** on the `body` to center the card vertically and horizontally.
- Styled the card with `max-width`, padding, and `border-radius` for rounded corners.
- Added a **box-shadow** to make the card stand out against the light background.

### 4. Footer
- Positioned the footer 10px above the bottom using `position: fixed`.
- Styled it with smaller, muted text and hover effects on links.

### 5. Responsiveness
- Verified that the layout scales well on mobile and desktop.
- Considered adding media queries for larger screens if needed.

### Built with

- [HTML5](https://developer.mozilla.org/en-US/docs/Web/HTML) – For page structure
- [CSS3](https://developer.mozilla.org/en-US/docs/Web/CSS) – For styling and layout
- [Flexbox](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Basic_Concepts_of_Flexbox) – For centering and alignment
- [Google Fonts](https://fonts.google.com/) – For typography (Outfit)
- [GitHub Pages](https://pages.github.com/) – For deployment
- Mobile-first responsive design

### What I learned
Through building this project, I practiced and reinforced several frontend skills:

- **Semantic HTML** → using meaningful elements like `<h1>` for headings and descriptive `alt` attributes for images to improve accessibility.
- **Flexbox layout** → centering a component both vertically and horizontally within the viewport.
- **Mobile-first design** → starting with styles that work well on small screens and planning for responsive scaling.
- **Card styling** → applying `border-radius` and `box-shadow` to create a modern, clean component.
- **GitHub Pages deployment** → publishing a live version of the project directly from my repo.

### Continued development

In future iterations of this project, I plan to:

- **Add full responsiveness with media queries**
- **Refine typography and spacing** for larger screens to improve readability.  
- **Enhance accessibility** further, such as using ARIA roles or landmarks.  
- **Experiment with CSS Grid** to explore alternative layout methods.  
- **Implement hover/focus animations** on the card and links for a more interactive experience. 

### Useful resources

- [Git Fundamentals](https://www.epicweb.dev/tutorials/git-fundamentals/commands/intro-to-git-fundamentals) - This helped me for getting started with git
- [Figma tutorial](https://designlab.com/figma-101-course/introduction-to-figma) - This is an amazing article which helped me getting familiar with Figma interface.


## Author

- Website - Utsavi
- Frontend Mentor - [@utsavi-code](https://www.frontendmentor.io/profile/utsavi-code)


## Acknowledgments

- Thanks to [Frontend Mentor](https://www.frontendmentor.io?ref=challenge) for providing this challenge and design.  
- Inspired by the amazing frontend community that encourages learning by building real projects.  

