# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./images/ppc-desktop.png) ==> Desktop Version
![](./images/ppc-mobile.png) ==> Mobile Version



### Links

For some reason, while there is no problem in VSCode or Chrome, the styles are completely broken on GitHub.

[html](https://github.com/Pandacea12/Project-Repository/blob/main/Pages/product-preview-card-component-main/product-preview-card-component.html)
[css](https://github.com/Pandacea12/Project-Repository/blob/main/styles/product-preview-card-component.css)

- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Sass


### What I learned

How to use the "display: none" property to easily switch picture between mobile and desktop sizes.

After struggling for a bit with the small white band under the picture in the Desktop version, I realized one of the uses of the "display: block" property because said white band was a space for descenders since img is an inline element by default.

### Continued development

Keeping in mind the "display: none" technique for pictures will be useful in the future.


## Author

- Website - [Gwenaëlle Laffont](https://pandacea12.github.io/Project-Repository/)(Doesn't currently work)
- Frontend Mentor - [Pandacea12](https://www.frontendmentor.io/profile/Pandacea12)


## Acknowledgments

- [Stackoverflow](https://stackoverflow.com/questions/7774814/remove-white-space-below-image) - This helped me realize the origin of my problem as well as how to solve it.