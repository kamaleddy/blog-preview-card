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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](./screenshot/Desktop%20View.png)
![](./screenshot/Mobile%20View.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [My Github live site](https://kamaleddy.github.io/blog-preview-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Local Fonts
- Flexbox
- Pseudo-classes
- Mobile-first workflow

### What I learned

1. Writing clean and semantic HTML that screen readers and browsers understand better.

```html
<main>
  <section class="content">
    <p><span>Learning</span></p>
    <p>Published 21 Dec 2023</p>
    <h1>HTML & CSS foundations</h1>
    <p>
      These languages are the backbone of every website, defining structure,
      content, and presentation.
    </p>
  </section>
</main>
```

2. Understanding how to use custom fonts

```css
@font-face {
  font-family: "Figtree";
  src: url(./assets/fonts/static/Figtree-ExtraBold.ttf) format("truetype");
  font-weight: 800;
  font-style: extra-bold;
}
```

3. Media query for mobile devices (max-width: 375px)

```css
@media (max-width: 375px) {
  main {
    width: 327px;
  }
}
```

4. Cursor change on interactive elements

```css
.content h1:hover {
  color: var(--bg-color);
  cursor: pointer;
}
```

### Continued development

- Make the blog title and image clickable, linking to a blog post.
- Add Hover Effects on Image or Card
- Use rem/em for consistent scaling instead of px in media queries.

### Useful resources

- [CSS Pseudo-classes](https://www.geeksforgeeks.org/css/css-pseudo-classes/) - This helped me because of the simple explanation with some test code.

## Author

- Github - [@kamaleddy](https://github.com/kamaleddy)
- Frontend Mentor - [@kamaleddy](https://www.frontendmentor.io/profile/kamaleddy)
