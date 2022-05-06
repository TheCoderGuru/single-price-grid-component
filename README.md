# Frontend Mentor - Single price grid component solution

This is a solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

### Screenshot

![](./screenshot.png)



### Links

- Solution URL: [Check out the code here](https://github.com/TheCoderGuru/single-price-grid-component)
- Live Site URL: [Visit the live site here](https://single-price-grid-component-red-eight.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

This challenge allowed me to have a greater exposure to css grid since I never used it at this point however after watching some youtube tutorials by Kevin Powell and reading articles on CSS Tricks which included "A Complete Guide to CSS Grid" my direction was established while attempting this challenge and I found it easier to achieve the desktop layout.

The approach for coding the desktop version was to firstly establish how many columns were necessary in order to achieve the layout which resulted in a count of 2 columns. Secondly, in order to have the top-level container spanned across two columns, the css declaration ```grid-column: span 2``` would need to be specifically added on the respective class. The last step would be to have the bottom-level container divided into two equal sub-containers which meant that the containers would have to occupy the grid locations of ```1, 2``` and ```2, 2``` respectively.

I found it difficult to understand how exactly I am changing the top-level container from the desktop version where it spanned two columns to the mobile version of occupying only one column. This was a frustrating process however it dawned upon me that maybe if ```grid-column: span 2``` would be used to span two columns then what would be the result of ```grid-column: span 1``` which did exactly as I wanted.


### Continued development

I plan to try using css grid as much possible in order to become more comfortable with all of its various properties and its use cases in addition to attempt more css grid challenges to level up the complexity.


### Useful resources

- [CSS Tricks - CSS Grid](https://css-tricks.com/snippets/css/complete-guide-grid/) - This helped me with the flexbox concept and I am really glad to be recommend this article, will use it going forward.

- [MDN CSS Reference](https://developer.mozilla.org/en-US/docs/Web/CSS) - This is the guide to all the css properties with an indept explanation. Definitely recommend it.


## Author

- Frontend Mentor - [@TheCoderGuru](https://www.frontendmentor.io/profile/TheCoderGuru)
- Twitter - [@TheCoderGuru](https://www.twitter.com/TheCoderGuru)


