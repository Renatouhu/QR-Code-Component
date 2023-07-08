# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### Screenshot

![mobile](./images/mobile.png)
![desktop](./images/desktop.png)

### Links

- Solution URL: [Add solution URL here](https://github.com/Renatouhu/QR-Code-Component)
- Live Site URL: [Add live site URL here](https://qr-code-component-ten-sand.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

Using two options to center the QR Section

```css
.main{
  display: flex;
  justify-content: center;
  align-items: center;
}
```

or using this option

```css
.qrSection {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}
```
## Author

- Frontend Mentor - [@Renatouhu](https://www.frontendmentor.io/profile/Renatouhu)