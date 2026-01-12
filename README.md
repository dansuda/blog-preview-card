# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS).

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

![](/screenshot.png)

### Links

- Solution URL: [Solution URL](https://github.com/dansuda/blog-preview-card)
- Live Site URL: [Live site URL](https://dansuda.github.io/blog-preview-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I learnt how to link a local fontface in a css stylesheet using the @fontface "at rule."
```css
@font-face {
    font-family: 'FigTree';
    src: url(assets/fonts/Figtree-VariableFont_wght.ttf);
    font-weight: 500 800;
}
```

I also learnt how items can inherit characteristics from parent items and make work easier and the code less redundant.
```css
*, *::before, *::after {
    box-sizing: inherit;
    font-family: inherit;
    font-size: inherit;
}
```

I learnt many new properties like the ```box-shadow``` and ```border``` and it's different values and what they mean.

### Continued development

What I want to continue focusing on is finishing projects without some help and being able to be completely comfortable with the basics so I can start going into more complex techniques and 'languages'.


### Useful resources

- (https://www.w3schools.com) - This helped me to understand syntaxes of different properties and values. I really liked this pattern and will use it going forward.
- (https://www.stackoverflow.com) - This is an amazing website which helped me  understand why some workflow methods are better than others. Like how when dealing with online fonts, it's better to use a link tag in the html than importing with the css because the browser favors the former more than the latter. I'd recommend it to anyone who writes code.

## Author

- Frontend Mentor - [@dansuda](https://www.frontendmentor.io/profile/dansuda)
