# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

First attempt to go over the challenge.

### Links

- Live Site URL: [https://davydikkes.github.io/fm-qr-component/](https://davydikkes.github.io/fm-qr-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom variables

### What I learned

I used custom variables into CSS that I can use into many cases, it becomes reusable and store into one place.

Example:
```css
:root {
    /* Colors */
    --slate-300: #D5E1EF;
    --slate-500: #68778D;
    --slate-900: #1F314F;
    --white: #FFF;
}

 background-color: var(--slate-300);
```

Alse used some kind of CSS normalization here:
```css
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
```

## Author

- Frontend Mentor - [@DavydIkkes](https://www.frontendmentor.io/profile/DavydIkkes)

