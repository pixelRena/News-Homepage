# Frontend Mentor - News homepage solution

This is a solution to the [News homepage challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/news-homepage-H6SWTa1MFl). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshot


### Links

- Solution URL: 
- Live Site URL: [https://pixelrena.github.io/News-Homepage/](https://pixelrena.github.io/News-Homepage/)

## My process

### Built with

- [![Bootstrap][Bootstrap]][Bootstrap-url]
- [![Html][Html]][Html-url]
- [![Sass][Sass]][Sass-url]
- [Abril FatFace Font](https://fonts.google.com/specimen/Abril+Fatface?preview.text=W.&preview.text_type=custom)

### What I learned
- I learned how to override bootstraps classes without using !important. Whenever I did research it was suggested to never use !important unless it is for quick testing because of how it can cause problems later for those who many have the same classes. I never knew how to do this before surprisingly but you have to be really specfic when overriding it. I never used offcanvas until today, so that was also a neat trick I learned from Bootstrap.

## Author

- Website - [Serena](https://devserena.herokuapp.com/)
- Frontend Mentor - [@pixelRena](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@pixelRena](https://twitter.com/pixelRena)

## Acknowledgments

- Stackoverflow ["Bootstrap 4.0 - Use flex columns"](https://stackoverflow.com/questions/46076910/bootstrap-4-0-use-flex-columns) - This helped me solve the problem where I was having issues creating 2 columns for the last row on each column. I found that my problem was that I did not add another d-flex class as I should have to trigger the 'flex-column' class.
- Stackoverflow ["Bootstrap Change Navbar Link Colors"](https://stackoverflow.com/questions/48735679/bootstrap-change-navbar-link-colors) - I understood why I shouldn't use !important and how to actually override bootstraps class names
- [Bootstrap 5.2 Offcanvas Examples](https://getbootstrap.com/docs/5.2/examples/navbars-offcanvas/) - This was very helpful in showing my a live demo of a responsive offcanvas that actually shows the nav-items on large screens, learned that I had to implement some overriding properties


[Bootstrap]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com/docs/5.2/getting-started/introduction/
[Html]: https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white
[Html-url]: https://www.w3schools.com/html/
[Sass]: https://img.shields.io/badge/Sass-CC6699?style=for-the-badge&logo=sass&logoColor=white
[Sass-url]: https://sass-lang.com/
