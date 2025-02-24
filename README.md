# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7).

## Table of contents 

- [Overview](#overview)
    - [Screenshot](#screenshot)
    - [Links](#links)
- [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### Screenshot

![](./preview.png)

### Links

Live Site URL: [GitHub Pages]()

## My process

### Built with

- Semantic HTML 5 markup
- CSS logic properties
- Mobile-first workflow
- Flexbox and Grid
- RWD
- Sass
- CUBE CSS
- Accessibility

### What I learned

In this challenge, I discovered the Sass function `color.change()` from the `sass:color` module, which allows manipulating color channels and the transparency of a Sass variable. Thanks to this function, I didn’t have to duplicate the `$color-grey-500` variable to adjust its transparency.

```scss
@use "sass:color";

box-shadow: 40px 60px 50px 0px color.change($color-grey-500, $alpha: 0.25);
```

## Author

- LinkedIn [KonradJam](www.linkedin.com/in/konradjam)
- X [KonradJam_](https://x.com/KonradJam_)
- Frontend Mentor [KonradJam](https://www.frontendmentor.io/profile/KonradJam)
- Codewars [KonradJam](https://www.codewars.com/users/KonradJam)
- CodePen [KonradJam](https://codepen.io/konradjam)