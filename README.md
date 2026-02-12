# Frontend Mentor - Sunnyside agency landing page solution

This is a solution to the [Sunnyside agency landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/agency-landing-page-7yVs3B6ef). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

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
- Vanilla CSS

### What I learned

Responsive images using the `<picture>` element to serve different images for mobile and desktop:

```html
<picture>
  <source
    media="(min-width: 768px)"
    srcset="./images/desktop/image-transform.jpg"
  />
  <img
    src="./images/mobile/image-transform.jpg"
    alt="Egg on a yellow background"
  />
</picture>
```

Using CSS filters to change the color of SVGs (like the footer logo and social icons) without needing inline SVG modification:

```css
.footer-logo img {
  filter: brightness(0) saturate(100%) invert(32%) sepia(12%) saturate(1637%)
    hue-rotate(118deg) brightness(97%) contrast(92%);
}
```

## Author

- Website - [Your Name](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
