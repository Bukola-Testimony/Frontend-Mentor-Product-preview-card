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
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot


##### Desktop Design
>![My solution preview](https://github.com/Bukola-Testimony/Frontend-Mentor-Product-preview-card/blob/599f500dee21cff835e9219552c77d7b62a52ffd/images/Screenshot.png)
<br/>
<br/>

> ##### Mobile Design
<img src="./design/mobile-design.jpg" alt="mobile"/>

### Links
 
- Solution URL: [Add solution URL here](https://your-solution-url.com)
- live site URL: [live site](https://bukola-testimony.github.io/Frontend-Mentor-Product-preview-card/)


## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

Some of my learnings during this project is adding different images to the html file. I didn'nt know this before and had to browse online to find the solution. 
Note: see code below

I also learnt how to create zig-zag lines and circles/dots with html and CSS. Another learning point for me is creating the media queries and strike through elements.

This project has helped to improve my media query skills.

```html
<h1>Some HTML code I'm proud of</h1>
 <div class="deco">

    <div style="text-align:end">
      <span class="dot"></span>
      <span class="dot"></span>
      <span class="dot"></span>
    </div>
    
    <div style="text-align:end">
      <span class="dot"></span>
      <span class="dot"></span>
      <span class="dot"></span>
    </div>
    
    <div style="text-align:end">
      <span class="dot"></span>
      <span class="dot"></span>
      <!-- <span class="dot"></span> -->
    </div>
    
    <div style="text-align:end">
      <span class="dot"></span>
      <span class="dot"></span>
      <!-- <span class="dot"></span> -->
    </div>
    
    <div style="text-align:end">
      <span class="dot"></span>
      <span class="dot"></span>
      <!-- <span class="dot"></span> -->
    </div>
    
    <div style="text-align:end">
      <span class="dot"></span>
      <span class="dot"></span>
      <!-- <span class="dot"></span> -->
    </div>
  </div>


  <picture class = "image">

        <source  class = "mobile" media="(max-width:375px)" srcset="./images/image-product-mobile.jpg" width ="320px"; height ="200px"  alt="product image">
        
        <source  class = "desktop" media="(max-width:1440px)" srcset="./images/image-product-desktop.jpg" width ="250px";
        height ="350px";  alt="product image">

        
        <img src="./images/image-product-desktop.jpg" alt="hidden image">
        
      </picture>
```


```css
.dot {
    height: 20px;
    width: 20px;
    background-color: rgb(156, 158, 254);
    border-radius: 50%;
    display: inline-block;
    
  }
```


## Author

- Website - [Bukola Testimony](https://bukola-testimony.github.io/My-Portfolio-website/)
- Frontend Mentor - [@Bukola-Testimony](https://www.frontendmentor.io/profile/Bukola-Testimony)
- Twitter - [@BukolaTestimony](https://twitter.com/BukolaTestimony)




