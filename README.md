# Frontend Mentor - Fylo dark theme landing page solution

This is a solution to the [Fylo dark theme landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/fylo-dark-theme-landing-page-5ca5f2d21e82137ec91a50fd). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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




## Overview

- This is the solution to the Fylo dark theme landing page challenge on Frontend Mentor. Frontend Mentor challenges help you improve your coding skills by building realistic projects.

### The challenge

- Build it to look as close as possible to the design provided.

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![desktop-preview](https://user-images.githubusercontent.com/49578782/140789503-925f1c1b-9e56-44f5-a324-2f2135399413.jpg)



### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

- Started with mobile design than use media queries for desktop layout. I used IrfanView app to get the size for width, height, padding, margin 

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- [Styled Components](https://fontawesome.com/) - Used it for the social media icons


### What I learned

- I learned to use pseudo elements when needed. In the code example below i use ::before to position the quotes behind the first testimonial div 

```css
.testimonials::before {
  content: url(/images/bg-quotes.png);
  position: absolute;
  top: -2.4rem;
  left: 2.2rem;
  z-index: -1;
}
```


### Continued development

- Currently learning css grid for my next project/challenge 


### Useful resources

- [Example resource 1](https://developer.mozilla.org/en-US/) - I did some digging on mdn if there is anything that i needed help with.



## Author

- Frontend Mentor - [@Dblack84](https://www.frontendmentor.io/profile/Dblack84)
- Twitter - [@D_black84](https://twitter.com/D_Black84)

