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
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![screenshot of my solution](/images/product-preview-card.png)

### Links

- [Solution](https://github.com/anabfuentes/product-preview-card)
- [Live site](https://anabfuentes.github.io/product-preview-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

The below HTML code was probably the biggest thing I learned and I'm happy to have found. I got this idea from Kevin Powell who I acknowledge and link below. I was really struggling to figure out how to effectively change images at my set breakpoint. I found this to be my favorite and most effective method. Previous to this project, I didn't know about the srcset element for changing out images.


```html
<picture class="product-image">
  <source
      srcset="images/image-product-desktop.jpg"
      media="(min-width: 600px)"
      />
      <img
      src="images/image-product-mobile.jpg"
      alt="Gabrielle Essence perfume bottle laying flat on a white surface, surrounded by leafy, green plants"
      />
</picture>
```

### Continued development

I want to continue to read up on and figure out useful implementations of CSS Grid. I primarily use Flexbox, but there were a few moments during coding for this project that Grid seemed simpler, so I definitely want to become more knowledgable in this area.

I also found some great articles and videos I want to look further, the topics include CSS Resets, Custom CSS Properties, and how to best section html code.

### Useful resources

- ["A Complete Guide to CSS Grid" via CSS-Tricks](https://css-tricks.com/snippets/css/complete-guide-grid/) - This helped me more easily format this project. I really liked incorporating a mixture of Grid and Flexbox and I found this guide to be extremely easy to read through and implement.
- [Video: "Taking on a Frontend Mentor challenge | Responsive Product Preview Card Component" by Kevin Powell](https://www.youtube.com/watch?v=B2WL6KkqhLQ) - I initially watched this video as I wanted to see examples of how people coded the main images for the challenge and this definitely helped with that, but also introduced me to so many other CSS concepts that I'm eager to learn more about. Some of the topics I found most interesting/helpful: Implementing a CSS reset, Implementing custom properties, :is():, and a great way to change images based on different media breakpoints.

## Author

- Website - [Ana Fuentes](https://www.anafuentes.com/)
- Frontend Mentor - [@anabfuentes](https://www.frontendmentor.io/profile/anabfuentes)
- LinkedIn - [Ana Fuentes](https://www.linkedin.com/in/anafuentesdeveloper/)

## Acknowledgments

To figure how to change the main image based on the mobile and desktop breakpoints, I followed along with a tutorial [Kevin Powell](https://youtube.com/kevinpowell) has available on YouTube. After watching his solution, I saw there were a lot of great CSS methods he used that I tried out in my code as well. Thanks so much for making your tutorial available and showing me some new CSS and HTML tricks!

