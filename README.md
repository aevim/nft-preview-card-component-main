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

![](./public/img/screenshot.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- Flexbox
- Mobile-first workflow
- Sass
- BEM
- Yarn

### What I learned
This was a bit more challenge, specially because I forgot to check the design folder 
to see how the layout should react to hovering. It was a huge mistake, and I learn from that.
From now on I will always take a carefull look into how I will build the html to make 
the work with css a bit easier. Centralizing the second image when hovering was a bit of a 
challenge, specially doing the background color change. I did try box-shadow but it did not work 
cuz inset don't work in image, so I have to search a bit and my solution was to add a div tag and use it 
to add the color. Another thing that I learn that was very usefull was the transform to make 
position: absolute with top: 50% and left: 50% to centralize the image.

```css
transform: translate(-50%,-50%);
```
## Author

- Frontend Mentor - [@aevim](https://www.frontendmentor.io/profile/aevim)
