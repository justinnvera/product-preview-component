# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - Product preview card component solution](#frontend-mentor---product-preview-card-component-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [The challenge](#the-challenge)
    - [Screenshot](#screenshot)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Continued development](#continued-development)
  - [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](/screenshot.jpg)


### Links

- Solution URL: [Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa/hub/product-preview-component-css-flexbox-pxnXUceqDs)
- Live Site URL: [Vercel]((https://product-preview-component-nine.vercel.app)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [React](https://reactjs.org/) - JS library
- [Next.js](https://nextjs.org/) - React framework
- [Styled Components](https://styled-components.com/) - For styles

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

I learned how to design mobile first. I also learned that you need to set the width and height of the parent element in order to set a height of its children based on that parent element. 

In the example below, I had to set the width and height of the <main> tag first and then I can base the width and height of its child element which in this case is <div.hero-image-contaner> to be 100% width and height. This one got me stumped for a while until I finally got it.

```html
<div class="hero-image-container"></div>
```
```css
main {
    display: flex;
    justify-content: center;
    align-items: center;
    margin-top: 5rem;
    width: 650px;
    height: 400px;
    background-color: hsl(0, 0%, 100%);
    border-radius: 10px;
}
main .hero-image-container {
    width: 100%;
    height: 100%;
    background-image: url("/images/image-product-desktop.jpg");
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;
    border-top-left-radius: 10px;
    border-bottom-left-radius: 10px;
}
```
### Continued development

I will keep focusing and researching on how to code in mobile-first and also research more about CSS Flex and Grid positioning.

## Author

- Website - [Justin Vera](justinvera.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/justinnvera)
