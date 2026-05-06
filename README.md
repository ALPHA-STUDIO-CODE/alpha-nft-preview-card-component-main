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
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [Add solution URL here](https://github.com/ALPHA-STUDIO-CODE/alpha-nft-preview-card-component-main)
- Live Site URL: [Add live site URL here](https://alpha-studio-code.github.io/alpha-nft-preview-card-component-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

```html
<div class="info">
  <span class="ETH">
    <img src="./images/icon-ethereum.svg" alt="ethereum icon" />
    <p>0.041 ETH</p>
  </span>
  <span class="time-left">
    <img src="./images/icon-clock.svg" alt="clock icon" />
    <p>3 days left</p>
  </span>
</div>
```

```css
.info {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin: 0.8rem 0;
}

.info span,
.info p {
  display: flex;
  align-items: center;
}

span img {
  margin-right: 0.278rem;
}

.ETH {
  color: var(--cyan-400);
  font-weight: 600;
}
```

## Author

- Frontend Mentor - [@ALPHA-STUDIO-CODE](https://www.frontendmentor.io/profile/ALPHA-STUDIO-CODE)
- Twitter - [@ALPHASTUDIOCODE](https://x.com/ALPHASTUDIOCODE)

## Acknowledgments

Thanks to Frontend Mentor for giving us this place to learn, train, and grow. Thanks also to W3Schools for their in-depth documentation and to Overflow for bringing developers together to work on problems.
