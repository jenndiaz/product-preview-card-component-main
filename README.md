# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). 

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements
- Styled to be responsive on 375px screens and 1440px screens 


### View Solution 

[Github Page](https://github.com/jenndiaz/product-preview-card-component-main)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties


### What I learned

This project was an overview of many topics which I learned previously but have not worked with in a while. Two concepts I reviewed while completing the challenge were CSS media queries and the css property `object-fit`. 

## CSS Media Queries

In this project I used media queries to make the project mobile responsive. They can also be used to target screen resolution, for printing, device orientation, and operating style preferences. Most commonly used within CSS, they are composed of an optional media type, media features, and logical operators. 

Learn More: 

[MDN: using media queries](https://developer.mozilla.org/en-US/docs/Web/CSS/Media_Queries/Using_media_queries)

[CSS-Tricks: A Complete Guiade to CSS Media Queries](https://css-tricks.com/a-complete-guide-to-css-media-queries/)

## `object-fit`

`object-fit` is a CSS property, it sets how the context should resize to fit with in it's container. Property is specified using the values; `contain`, `cover`, `fill`, `none`, and `scale down`. In this project I use `object-fit: cover;` with in my `max-width: 375px` breakpoint for the `product-image` class. This allows the product picture for maintain is aspect ratio when fitting the container. So when the user views the image on smaller screen the image is clipped instead of not filling the container or streching the image. 


Learn More:

[MDN object-fit](https://developer.mozilla.org/en-US/docs/Web/CSS/object-fit) 







