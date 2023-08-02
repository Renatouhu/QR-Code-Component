<img src="https://github.com/Renatouhu/Assets/blob/main/qr-code-component/Qr code photo.png" width="100%">

<p style="text-align:center;">This is a solution to the <a href="https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H">QR code component challenge on Frontend Mentor</a>. Frontend Mentor challenges help you improve your coding skills by building realistic projects. </p>

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

- Solution URL: [QR-Code-Component on GitHub](https://github.com/Renatouhu/QR-Code-Component)
- Live Site URL: [Live Site on Vercel](https://qr-code-component-ten-sand.vercel.app/)

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
