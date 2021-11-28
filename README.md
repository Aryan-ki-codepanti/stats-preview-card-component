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

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](./readme-assets/screenshot.png)

### Links

- Solution URL: [Index.html file](./index.html)
- Live Site URL: [Stats Preview Component](https://aryan-ki-codepanti.github.io/stats-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

I learnt quite interesting things while making this project
One of them being adding a overlay to the images with 2 div system 


```html
<div class="hero-img">
    <div class="color-overlay"></div>
    <img src="images/image-header-desktop.jpg" alt="">
</div>
```

```css
.hero-img{
    position: relative;
}


.color-overlay{
    background-color: var(--Opacity-violet);
    position: absolute;
    inset: 0;
}
.app__right img{
    width: 100%;
    object-fit: cover;
    border-radius: 0 var(--Corner-radius) var(--Corner-radius) 0;
}
```

![](./readme-assets/overlay.png)

### Continued development

For future i would like to focus on improving my CSS skills like mobile responsiveness. 

### Useful resources

- [MDN dev docs](https://developer.mozilla.org/) - This helped me for tricks and tips and short lookups for CSS and Javascript.
- [Kevin Powell youtube channel](https://www.youtube.com/kepowob) - This helped me  understanding concepts of flexbox and grids in CSS.

## Author

- Frontend Mentor - [@Aryan-ki-codepanti](https://www.frontendmentor.io/profile/Aryan-ki-codepanti)
- Twitter - [@AryanSe73817078](https://www.twitter.com/AryanSe73817078)
- Youtube - [Channel: Coding Tiger](https://www.youtube.com/channel/UCkz7TnVuNBGEQOTa77lmZfA)