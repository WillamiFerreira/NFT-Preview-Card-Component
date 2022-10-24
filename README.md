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

![projeto_05_screenshot](https://user-images.githubusercontent.com/98838062/197515034-2ea6d0a1-4f57-46a8-be12-1f345054fe5c.png)

### Links

- Solution URL: [Github Repository](https://github.com/WillamiFerreira/NFT-Preview-Card-Component.git)
- Live Site URL: [Live site on Pages](https://willamiferreira.github.io/NFT-Preview-Card-Component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Mobile-first workflow


### What I learned

I learned how to use the position property better, mainly it's values: relative and absolute, as well as how to overlap one image over another one.

To see how you can add code snippets, see below:

```html
<div class='father'>
  <img class="cristal" src="images/image-equilibrium.jpg">
  <div class="view-sign">
    <img src="images/icon-view.svg">
  </div>
</div>
```
```css
.img{
  display: block;
}
.cristal{
  width: 100%;
}

.father{
  position: relative;
  width: 200px;
  height: 200px;
}
.view-sign{
  position: absolute;
  top: 50px;
  left: 50px;
}
```

### Useful resources

- [Stack Overflow Question](https://pt.stackoverflow.com/questions/44678/qual-a-diferen%C3%A7a-entre-displaynone-e-visibilityhidden) - 
This helped me to show the view icon only when the mouse cursor is on it(hover).
- [iMasters ](https://imasters.com.br/css/como-sobrepor-imagens-com-div-e-css) - This help to better understand how the position property works, and how to overlap one image over another.

## Author

- Frontend Mentor - [@WillamiFerreira](https://www.frontendmentor.io/profile/WillamiFerreira)
- Twitter - [@ferrersgab](https://www.twitter.com/ferrersgab)

