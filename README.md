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
- [Author](#Cousnay)


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](images/Desktop-view%20Frontend%20Mentor%20Product%20preview%20card%20component.png)
![](images/Mobile-view%20Frontend%20Mentor%20Product%20preview%20card%20component.png)


### Links

- Live Site URL: [Live site URL](https://disney-banje.github.io/Product-card/)

## My process

### Built with

- HTML
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

-  Image responsivnes using the Art direction.
-  Using the overflow property.
-  Fiting an image inside a container.
-  Object-fit property.

Code snippets used in process, see below:

```HTML
 <picture>
  <source media="(max-width: 800px)" srcset="images/image-product-mobile.jpg" />
  <source media="(min-width: 800px)" srcset="images/image-product-desktop.jpg" />
  <img src="images/image-product-mobile.jpg" alt="Gabrielle channel perfume" />
 </picture>

```

```css
.product-card {
  border-radius: 12px;
  overflow: hidden;
}

.product-images img {
    width: 100%;
    height: 100%;
    object-fit: cover;
}
```

### Continued development

I think I still have some work to do on  css layout to be more confortable with the concept, and also try to improve my Task completion speed which I think Is a key attribute to have in the industry.


### Useful resources

- [Mdn](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images#art_direction) - This helped me to come up with a way to create image responsivness for the card.
- [w3schools](https://www.w3schools.com/) - This was an amazing resource to complete my project.
- [GitHub Docs](https://docs.github.com/en/pages/quickstart) - Amazing resources to learn how to deploy your website using github pages.


## Author
- Twitter - [@Cousnay](https://twitter.com/Cousnay)


