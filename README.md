# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
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

- View the optimal layout depending on their device's screen size


### Links

- Solution URL: (https://www.frontendmentor.io/solutions/responsive-stats-preview-card-UEpWQo4v0)
- Live Site URL: (https://ax-cd.github.io/stats-preview-card-challenge/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

With this project I learned:
- The importance to try on different browsers (the changes I made with Flexbox didn't appear in Edge but worked just fine in Firefox)
- Adding borders is really useful to visualize where are the elements on the page and how they move with flexbox

I had trouble with making the image purple. I tried filter, -webkit-filter, and hue-rotate, but the color wasn't changing. Finally I tried combining background-color and opacity, and it worked just fine! I added a filter brightness() for more precision.

```html
        <div class="image-header">
            <img src="images/image-header-desktop.jpg" alt="Image header">
        </div>
```
```css
.image-header {
    width: 540px;
    height: 400px;
    border-radius: 0 6px 6px 0;
    background-color: hsl(278, 96%, 55%);
}

.image-header img {
    width: 540px;
    height: 400px;
    border-radius: 0 6px 6px 0;
    opacity: 70%;
    filter: brightness(0.60);
}
```

### Continued development

- Working with flexbox
- Making responsive designs with @media queries

### Useful resources

- [How to Change the Color of PNG Image](https://www.w3docs.com/snippets/css/how-to-change-the-color-of-png-image-using-css.html) - This tutorial taught me how to use the filter property and the differents values it has.
- [CSS filter Property](https://www.w3schools.com/cssref/css3_pr_filter.asp) - This article was useful as it summarize how each value must be written (ex: blur in pixels, brightness in percentage, hue-rotate in degrees, etc.).


## Author

- Website - [Ax-cd](https://axcoding.blogspot.com/)
- Frontend Mentor - [@Ax-cd](https://www.frontendmentor.io/profile/Ax-cd)
- Instagram - [@ax.coding](https://www.instagram.com/ax.coding/)
