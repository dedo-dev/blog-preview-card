# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

![](./assets/images/blog-preview-card.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://dz-blog-preview-card.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- BEM
- Logical Properties
- Custom Properties
- Variable Fonts

### What I learned
In this Challenge I learn how to work with **Variable Fonts**, I make a muscle memory with **Semantic HTML** to build a card, with **Logical Properties** and **Custom Properties**.

```html
  <article class="card">
<<<<<<< HEAD
    <img height="200" class="card__img" src="/assets/images/illustration-article.svg" alt="Colorfull code elements illustration">
=======
    <img
      height="200"
      class="card__img"
      src="/assets/images/illustration-article.svg"
      alt="Colured in yellow, black and white illustration of HTML element's"
    >
>>>>>>> 29227a7d7661a23f1198017d045793912ff11dfd
    <div class="card__content">
      <span class="tag">Learning</span>
      <time class="publishdate" datetime="2024-06-03" title="Published Dec 21, 2023">
        Published 21 Dec 2023
      </time>
      <h1><a href="#" class="title">HTML & CSS foundations</a></h1>
      <p class="description">
        These languages are the backbone of every website, defining structure, content, and presentation.
      </p>
    </div>
    <div class="author-info">
      <img width="32" height="32" src="/assets/images/image-avatar.webp" alt="Author of the article">
      <h2>Greg Hooper</h2>
    </div>
  </article>
```
```css
@font-face {
    font-family: 'Figtree';
    font-weight: 500 800;
    font-style: normal;
    src: url(./assets/fonts/Figtree-VariableFont_wght.woff2) format('woff2');
}
```

### Continued development

In the future I would like to continue to put in practice my HTML, CSS and JavaScript knowledge.

### Useful resources

- [Convert Variable Fonts](https://https://everythingfonts.com/ttf-to-woff2) - Usefull tool to convert Variable Fonts to woff2 format
- [Getting started with Variable  Fonts](https://www.youtube.com/watch?v=0fVymQ7SZw0) - A good video by Kevin Powell on how to getting started with Variable  Fonts
- [Using web fonts](https://fonts.google.com/knowledge/using_type/using_web_fonts) - An article to understand how to work with Variable Fonts by Google
- [How to use fit-content](https://developer.mozilla.org/en-US/docs/Web/CSS/fit-content) - An mdn web docs to use fit-content, I used it to create the tag
- [How to use box-shadow](https://developer.mozilla.org/en-US/docs/Web/CSS/box-shadow) - An mdn web docs to use box-shadow, I used it to create a perfect box-shadow of the card

## Author

- Frontend Mentor - [@dedo-dev](https://www.frontendmentor.io/profile/dedo-dev)
- Linkedin - [@daniele-zeppieri](https://www.linkedin.com/in/daniele-zeppieri-0b1a36252/)
