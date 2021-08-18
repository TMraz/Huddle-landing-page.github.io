# Frontend Mentor - Huddle landing page with alternating feature blocks solution

This is a solution to the ![Huddle landing page with alternating feature blocks challenge on Frontend Mentor](./design/desktop-preview.jpg). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

[Desktop version](./design/desktop-design.jpg)
[Mobile version](./design/mobile-design.jpg)

### Links

- [Solution URL](https://github.com/TMraz/Huddle-landing-page.github.io)

- [Live Site URL](https://tmraz.github.io/Huddle-landing-page.github.io/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- [Styled Components](./css/main.css) - For Desktop style
- [Styled Components](./css/mobile.css) - For Mobile style

### What I learned

Snippets, see below:

Change of the svg color:

```css
 /* change of the svg color */

.contact img {
    filter: invert(50%) sepia(76%) saturate(0%) hue-rotate(1deg) brightness(100%) contrast(1000%);

    height: 1.5rem;
    margin: 1.5rem 0;
}

```

Change of list style type to svg:

```css
 /* change of list style type to svg */
.contact-list li:first-child {
    list-style-image: url(../img/icon-location.svg);
}
```

Rounded favicons:

```html
<div class="social">
  <ul>
    <li class="social-item">
      <i class="fa fa-facebook"></i>
    </li>
  </ul>
</div>
```

```css
/* === social list style=== */
.social ul [class*="fa fa-"]{
    border: 1px solid #fff;
    border-radius: 50%;
    color: #fff;
    display: inline-block;
    height: 40px;
    line-height: 40px;
    margin: auto 3px;
    width: 40px;
    font-size: 18px;
    text-align: center;
}

.social-item {
    margin: .1rem;
    display: inline-block;
    list-style: none;
}

.social [class*="fa fa-"]:hover,
.social [class*="fa fa-"]:active {
    border: 1px solid var(--color-btn);
    color: var(--color-btn);
    cursor: pointer;
}

```

### Useful resources

- [Change of the svg color](https://www.codegrepper.com/code-examples/css/how+to+change+the+color+of+svg+using+css) 

- [Rounded favicons](https://codepen.io/KevinCSTing/pen/vyLyXg) 


