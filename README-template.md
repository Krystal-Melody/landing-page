# Frontend Mentor - Clipboard landing page solution

This is a solution to the [Clipboard landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/clipboard-landing-page-5cc9bccd6c4c91111378ecb9). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![](./images/screenshot.png)


### Links

- Solution URL: https://github.com/Krystal-Melody/landing-page.git
- Live Site URL: https://krystal-melody.github.io/landing-page/

## My process

### Built with

- Semantic HTML5 markup
- Flexbox
- Mobile-first workflow


### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.


```html
<header class="cta">
  <div class="header">
    <div class="container flex">
      <img src="images/logo.svg" class="logo">
      <h1>A history of everything you copy</h1>
      <p>Clipboard allows you to track and organize everything you 
        copy. Instantly access your clipboard on all your devices.</p>
      <div class="flex-button">
      <div>  
        <button class="btn green">Download for iOS</button>
      </div>
      <div>
        <button class="btn purple">Download for Mac</button>
      </div>
```

-This HTML pattern was used for both the top and bottom of the landing page (minus the .header class). Working through this project helped me to start identifying what styles can be used in multiple areas before starting to code. 



### Continued development

For this challenge, I utiltzed Firefox Developer Edition for my live editor. I noticed that the hover and active states were not displaying properly, however they worked fine with Chrome. Going forward, I will focus on compatibility between browsers and best practices on how to handle these situations.


### Useful resources

- https://codepen.io/kanishkkunal/pen/obGojO - This helped me to get the glow effect for the buttons. I really liked this pattern and will use it going forward.

- https://css-tricks.com/a-complete-guide-to-links-and-buttons/ - This article helped me to understand when it's best to use a link vs a button. For this project, I chose to use a button tag because it was commanding a download and not necessarily linking to another page.


## Author

- Frontend Mentor - [@IndigoStar88] https://www.frontendmentor.io/profile/IndigoStar88

