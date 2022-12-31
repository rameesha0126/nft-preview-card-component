# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - NFT preview card component solution](#frontend-mentor---nft-preview-card-component-solution)
  - [Table of contents](#table-of-contents)
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

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

[Mobile View](./Mobile-view.png)
[Desktop View](./Desktop-view.png)

### Links

- Solution URL: [Solution](https://github.com/rameesha0126/nft-preview-card-component.git)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Float
- Mobile-first workflow

### What I learned

- Using CSS Float property to place objects on left and right of screen.

```html
<div class="left-float">
  <img src="images/icon-ethereum.svg" alt="ethereum" class="icons">
  <p>0.041 ETH</p>
</div>
<div class="right-float">
  <img src="images/icon-clock.svg" alt="clock" class="icons">
  <p>3 days left</p>
</div>
```
```css
.left-float {
    display: flex;
    flex-direction: row;
    align-items: center;
    float: left;
}

.right-float {
    display: flex;
    flex-direction: row;
    align-items: center;
    float: right;
}
```

### Continued development

- Using mask property to create the active element on the image property. 

### Useful resources

- [W3schools CSS Tutorial](https://www.w3schools.com/css/default.asp)

## Author

- Github - [Rameesha0126](https://github.com/rameesha0126)
- Frontend Mentor - [@rameesha0126](https://www.frontendmentor.io/profile/rameesha0126)
