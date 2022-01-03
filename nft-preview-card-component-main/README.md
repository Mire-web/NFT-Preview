# Frontend Mentor - NFT preview card component solution

This is my solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). 

Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
    -[Editor](#editor)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](images\screenshot.PNG)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)

## My process
Let me walk you through how I solved the challenge

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
#### Editor
- VS code

### What I learned

I learnt in a more practical manner how pseudo classes and elements work, i also learnt how exactly positioning works in css.
Generally, I got to practice my skill and figure where i needed to improve, which turns out to be advanced CSS. 

```css
.container::after{
    content: "";
    display: block;
    position: absolute;
    background-color: cyan;
    border-radius: 15px;
    width: 270px;
    height: 270px;
    left: 115px;
    top: 75px;
    opacity: 0;
    cursor: pointer;
}
```

### Continued development

I would continue to develop my css skill and js skill, currently on a 100DaysOfCode challenge, today being Day 1. i'll be posting update of my progress on twitter [@not_ifeanyi](https://twitter.com/not_ifeanyi) and hashnode [@RealMire](hashnode.com/@RealMire), i would appreciate feedbacks and do well to follow me and see how far I get, Thank you.

### Useful resources

- [resource](https://www.smashingmagazine.com/2011/07/learning-to-use-the-before-and-after-pseudo-elements-in-css/) - This is an amazing article which helped me finally understand pseudo elements. I'd recommend it to anyone still learning this concept.

## Author

- Frontend Mentor - [@Mire-web](https://www.frontendmentor.io/profile/Mire-web)
- Twitter - [@not_ifeanyi](https://twitter.com/not_ifeanyi)
