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
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](./screenshot.png)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I have practiced how to change images, when screen size change.  
```html
 <picture class="card__img-container">
  <source media="(min-width: 1024px)" srcset="./images/image-header-desktop.jpg">
  <img class="card__img" src="./images/image-header-mobile.jpg" alt="people at the office">
 </picture>
```

New for me was also concept of mix blend mode

```css
.card__img {
    max-width: 100%;
    width: auto;
    /* mix blend mode  */
    mix-blend-mode: multiply;
    opacity: .75;
    /* odstranění malého proužku pod fotkou */
    vertical-align: middle; 
}
```


### Useful resources

- [mix-blend-mode](https://developer.mozilla.org/en-US/docs/Web/CSS/mix-blend-mode) 
- [Responsive Images & using srcset](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images#how_do_you_create_responsive_images)

## Author

- Frontend Mentor - [@davidgrossmann](https://www.frontendmentor.io/profile/davidgrossmann)

## Acknowledgments

I have checked code of [sf-adams](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images#how_do_you_create_responsive_images), when I got stuck. 
