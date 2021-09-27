# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![Desktop view](./images/screenshot_desktop.jpg)
![Mobile view](./images/screenshot_mobile1.jpg)
![Mobile view](./images/screenshot_mobile2.jpg)
![Mobile view](./images/screenshot_mobile3.jpg)
![Mobile view](./images/screenshot_mobile4.jpg)

### Links

- Solution URL: [Github Repository](https://github.com/AndyCatlow/frontendmentor/tree/main/3-column-preview-card-component-main)
- Live Site URL: [Live site URL](https://mystifying-hawking-13cc67.netlify.app)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I used grid with auto-fit columns to make the page responsive without media queries.

```css
.card__container {
  display: grid;
  place-content: center;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  max-width: 100vw;
}
```

## Author

- Website - [Add your name here](https://www.andycatlow.dev)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/AndyCatlow)
- Twitter - [@yourusername](https://www.twitter.com/CatlowAndy)
