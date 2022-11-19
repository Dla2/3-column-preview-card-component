# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./images/screenshot/Screenshot-3-column%20preview%20card%20component.png)


### Links

- Solution URL: [Solution](https://github.com/Dla2/3-column-preview-card-component.git)
- Live Site URL: [](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Mobile-first workflow

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:


```css
@media(min-width: 1200px) {
    body {
        max-width: 1400px;
        height: 100vh;
        margin: 0 auto;
        display: grid;
        place-content: center;
    }
    .threeColumns {
        display: grid;
        grid-template-columns: 1fr 1fr 1fr;
        grid-template-rows: none;
        width: 1000px
    }

    .columnOne {
        border-top-right-radius: 0;
        border-bottom-left-radius: 12px;
        row-gap: 35px;
    }

    .columnTwo {
        row-gap: 35px;
    }

    .columnThree {
        border-bottom-left-radius: 0;
        border-top-right-radius: 12px;
        row-gap: 35px;
    }

    img {
        width: 25%;
    }
}
```


### Continued development

Learn more about building websites that are responsive.

### Useful resources


## Author

- Website - [Sente]()
- Frontend Mentor - [Dla2](www.frontendmentor.io/profile/Dla2)


## Acknowledgments

