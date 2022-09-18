# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshots](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements
- See responsive design to window size

### Screenshots

![Design preview for the order summary component coding challenge](https://github.com/jcgager/order-summary-component/blob/master/design/desktop-demo.png?raw=true)

![Design preview for the order summary component coding challenge](https://github.com/jcgager/order-summary-component/blob/master/design/mobile-demo.png?raw=true)

### Links

- Solution URL: [frontendmentor.io/solutions](https://www.frontendmentor.io/solutions/order-summary-component-using-flexbox-Gyl-2sBWqt)
- Live Site URL: [jcgager.github.io/order-summary-component](https://jcgager.github.io/order-summary-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- Atomic CSS

### What I learned

I was reading an article that I stumbled upon while searching for some info on CSS Tricks about Atomic CSS. I played with the concepts in this project, creating a general short-hand class and assigning it one rule. This single rule can then be referred to in the HTML by any tags that require that rule. It helped simplify the code within the media query as well since updating the one rule would apply changes to several elements at once.

```css
/* Before the @media */
.fz-lg { font-size: 1.3rem; }

/* Within the @media */
.fz-lg { font-size: 1.8rem; }
```
This particular rule only changed one element in this project but the power it could have to leverage dozens of elements at once is a gamechanger for me. This process was like learning to VLOOKUP in excel for the first time! 

### Useful resources

- [Let’s Define Exactly What Atomic CSS is](https://css-tricks.com/lets-define-exactly-atomic-css/) - This helped me understand the concepts of atomic css.

## Author

- Frontend Mentor - [@jcgager](https://www.frontendmentor.io/profile/jcgager)
- Twitter - [@Soul3raser](https://www.twitter.com/Soul3raser)
