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

![](/ScreenShots_MyWork/Desktop_Vision.png)
![](/ScreenShots_MyWork/Mobile_Vision_375px.png)

### Links

- Solution URL: [](https://your-solution-url.com)
- Live Site URL: [](https://your-live-site-url.com)

## My process

### Built with

- HTML 5
- CSS custom properties
- Flexbox
- VS code

### What I learned

This section recaps over some of major learnings while working through this project:

```html
<div class="container">
    <div class="card-img"></div>
    <div class="card-content">
      <div class="card-content-header">
        <h5>Perfume</h5>
        <h2>Gabrielle Essence Eau De Parfum</h2>
      </div>
      <div class="card-content-body">
        <p>
          A floral, solar and voluptuous interpretation composed by Olivier Polge, 
          Perfumer-Creator for the House of CHANEL.
        </p>
      </div>
      <div class="card-content-footer">
        <div class="card-price">
          <p class="card-price-promotion">$149.99</p>
          <p class="card-price-oldPrice">$169.99</p>
        </div>
        <div class="card-buy">
          <button class="card-buy-addCart">
            <img src="images/icon-cart.svg" alt="">
            Add to Cart
          </button>
        </div>
      </div>
    </div>
  </div>  
```
```css
  @media only screen and (max-width: 375px){
      .container{
          flex-direction: column;
      }
      .container .card-img{
          background-image: url(../images/image-product-mobile.jpg);
          width: 400px;
          height: 300px;
          border-radius: 10px 10px 0px 0px;
      }
      .card-content-header h2{
          font-size: 35px;
      }
      .card-content{
          width: 100%;
          padding: 25px 42px;
      }
  }
```

### Continued development

Working with a combination of html+css to make more improvements


### Useful resources

- [Flex box Guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) 

- [Response images](https://imagekit.io/responsive-images/)


## Author

- Frontend Mentor - [Ahmed Mahmoud Sanad](https://www.frontendmentor.io/profile/Ahmed-MSanad)


