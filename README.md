# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./Frontend%20Mentor%20-%20NFT%20preview%20card%20component.png)

### Links

- Solution URL: [https://github.com/YangLongWang/preview-card](https://github.com/YangLongWang/preview-card)
- Live Site URL: [https://yanglongwang.github.io/preview-card/](https://yanglongwang.github.io/preview-card/)

## My process

### Built with

- HTML
- CSS

### What I learned

- solving the overlay problem with CSS.

To see how you can add code snippets, see below:

```css
.pic {
    width: 250px;
    height: 250px;
    background: url(./images/image-equilibrium.jpg) center no-repeat;
    background-size: cover;
    border-radius: 10px;
    cursor: pointer;
    margin-bottom: 15px;
}

.pic:hover {
    background: linear-gradient(hsl(178, 100%, 50%, 60%), hsl(178, 100%, 50%, 60%)), url(./images/image-equilibrium.jpg) center no-repeat;
    background-size: cover;
    opacity: 1;
}

.eye {
    width: 250px;
    height: 250px;
    background: url(./images/icon-view.svg) center no-repeat;
    opacity: 0;
    z-index: 3;
}

.eye:hover {
    border-radius: 10px;
    opacity: 1;
}
```


### Useful resources

- (https://www.w3schools.com/howto/tryit.asp?filename=tryhow_css_image_overlay_opacity) - This helped me for solving the overlay problem.

## Author

- Website - [Longyang Wang](https://github.com/YangLongWang)
- Frontend Mentor - [@YangLongWang](https://www.frontendmentor.io/profile/YangLongWang)


