
# Frontend Mentor - Blog Preview Card Solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS).  
Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: (https://github.com/tech-goddezz/Blog-Preview-Card.git)
- Live Site URL: (https://blog-preview-card-pi-lovat.vercel.app/)

## My process

### Built with

- Semantic **HTML5 markup**
- **CSS3** (custom properties, flexbox)
- **Box shadows** for card styling
- **Hover states** for interactive elements
- **Responsive centering** with flexbox

### What I learned

This project helped me practice:

- Building a **card component** with semantic HTML and modern CSS.
- Using **flexbox** to align an avatar and name side by side:
  css
  .author-container {
    display: flex;
    align-items: center;
    gap: 12px;
  }


* Creating hover states to make the UI feel more interactive:

  ```css
  h1:hover {
    color: hsl(47, 88%, 63%);
    cursor: pointer;
  }
  ```
* Applying clean and subtle **box shadows** for a modern UI look:

  ```css
  .main-container {
    box-shadow: 8px 8px black;
    border: 1px solid black;
  }
  ```


### Continued development

In future projects, I want to focus on:

* Making components more **responsive** across different screen sizes.
* Using **CSS Grid** for more complex layouts.
* Refining animation skills (subtle micro-interactions vs playful effects).
* Exploring how to integrate **JavaScript** for more dynamic interactivity.

### Useful resources

* [MDN Web Docs - box-shadow](https://developer.mozilla.org/en-US/docs/Web/CSS/box-shadow) - Helped me fix my shadow syntax and create a cleaner effect.
* [CSS Tricks - Flexbox Guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - Great reference for aligning elements like the avatar and name.
* [Frontend Mentor Community](https://www.frontendmentor.io/community) - Inspiration and seeing how others approached the same challenge.

## Author

* Frontend Mentor - [@tech-goddezz](https://www.frontendmentor.io/profile/tech-goddezz)
* Twitter - [@tech\_goddezz](https://x.com/tech_goddezz)
* GitHub - [@tech-goddezz](https://github.com/tech-goddezz)
* LinkedIn - [Elizabeth Omigie](https://www.linkedin.com/in/elizabethomigie)

