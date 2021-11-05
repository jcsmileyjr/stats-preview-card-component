# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to view the optimal layout depending on their device's screen size

### Screenshot

![Preview Card Component's desktop screen shot](./images/preveiw-card-desktop.png)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

1. Mixing CSS Grid and Flexbox to style a UI
2. Tweaking an image with CSS to have a purple hue layered on top it. 
3. UI design aspects such as highlighting a single key word with the purple accent color, shading the image with the same accent color, and compacting the message in short form.


Some code that I'm proud of:
```css
      .parent {
        display: grid;
        grid-template-columns: repeat(2, 1fr);
        grid-template-rows: repeat(2, 1fr);
        grid-column-gap: 0px;
        grid-row-gap: 0px;
        grid-template-areas:
          "message image"
          "information image";
        color: white;
      }
```

### Useful resources
- [CSSGrid Generator](https://cssgrid-generator.netlify.app/): auto generate CSS Grid styles
- [CSS Grid Guide](https://css-tricks.com/snippets/css/complete-guide-grid/): quick recap of CSS-grid
- [CSS background image example](https://www.freecodecamp.org/news/css-background-image-with-html-example-code/): quick recap of background image styles

## Author

- Website - [JC Smiley](https://www.jcsmileyjr.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@JCSmiley4](https://twitter.com/JCSmiley4)

