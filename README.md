# Frontend Mentor - QR Code solution

This is a solution to the [QR Code challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued Development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Build out this QR code component and get it looking as close to the design as possible.

### Screenshot

![](./Screenshot%20QR%20code%20component.png)

### Links

- Github Repo URL: [QR Code Repo](https://github.com/amyspencerproject/qr-code)
- Live Site URL: [QR Code Page](https://amyspencerproject.github.io/qr-code/)

## My process

### Built with

- Semantic HTML5 markup
- CSS Variables
- CSS Grid
- Mobile-first workflow

### What I learned

One aspect I want to focus on is my workflow. What are the steps I automatically take when starting a project. This simple challenge is perfect for that.

- Created a style.css file with Andy Bell browser reset
- Downloaded font family and added to index.html and style.css
- Looked at design file and decided on what HTML elements should be used. This probably would not be a stand alone page so stuck with just the body and a footer. Created a container div to get the white background and hold the QR image and text. Anticipated that if this code were to be used in established page having classes specifically named would make it easy to integrate. So instead of styling the `<p>` I used a class name of `qr-code-text`
- Decide to use Grid for the layout system because I wanted the practice. Flex could have also been used.
- Used CSS variables.
- Center aligned the container div with respect to the body.
- Applied a `border-radius` of 10px to the image and a larger `border-radius` of 20px to the container div.
- Used padding and margins to match the position of the elements at 375px viewport size to the Figma file.
- The QR code is exactly the same size in the 1440px viewport. I appled a max width of 20rem to the container. No media queries needed!

### Useful resources

- I watched a [Kevin Powell video](https://www.youtube.com/watch?v=VQraviuwbzU) on 5 simple steps for repsonsive layouts.
- [CSS variables](https://www.w3schools.com/css/css3_variables.asp)

## Author

- Website - [Amy Spencer](https://spencerproject.com/)
- Frontend Mentor - [@amyspencerproject](https://www.frontendmentor.io/profile/amyspencerproject)
- Linkedin - [amyspencercodes](https://www.linkedin.com/in/amyspencercodes/)
