# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- See hover and focus states for all interactive elements on the page. 

### Screenshot

![](./assets/images/Screenshot-2025-09-24-173310.png)


### Links

- Solution URL:  http://127.0.0.1:5500/index.html
- Live Site URL: https://ibidiuntold.github.io/social-media-challenge/

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid



### What I learned

- I learned how to mark down code in GitHub. This was the first time I ever learned something on it. 
- I learned how to properly style anchor links using html and css. 

HTML codes I am really proud of: 
```html
 <div class="intro">
    <img src="/assets/images/avatar-jessica.jpeg" alt="Profile Picture">
    <h1>Jessica Randall</h1>
    <p id="address">London, United Kingdom</p>
    <p>"Front-end developer and avid reader."</p>
      <div class="links">
        <a class="links one" href="#">GitHub</a>
        <a class="links two" href="#">Frontend Mentor</a>
        <a class="links three" href="#">LinkedIn</a>
        <a class="links four" href="#">Twitter</a>
        <a class="links five" href="#">Instagram</a>
      </div>
  </div>
```

CSS styles I am proud of:
```css
.links {
    display: block;
    margin: 15px 20px;
    max-width: fit-content;

}
.one, .two, .three, .four, .five {
    background-color: hsl(0, 0%, 20%);
    border: none 1px;
    border-radius: 3px;
    width: 220px;
    height: 40px;
    text-align: center;
    padding: 12px;
    max-height: fit-content;
    max-width: 250px;
    color: #f5f6f7;
    text-decoration: none;
    display: block;
    margin: 20px auto;
    font-family:Arial, Helvetica, sans-serif;
}

a:hover {
    background-color: hsl(75, 94%, 57%);
    color: hsl(0, 0%, 12%);
}
```

### Continued development

I hope to use this as a means of focusing on CSS flexbox and learn how to style my code more, while complementing writing with my HTML5 semantics. I also hope to reuse this code at some time in the near future for my other endeavors. 

### Useful resources

1. ChatGPT and Git Copilot helped out a lot in some instances. 
2. Markdown Language guide (https://www.markdownguide.org/extended-syntax/#fenced-code-blocks) helped me to learn how to mark down written code in Git


## Author

- Website - Iyango Williams(www.linkedin.com/in/iyango-williams-657504249)
- Frontend Mentor - [@ibidiuntold](https://www.frontendmentor.io/profile/ibidiuntold)
- Twitter - [@ibidi_untold](https://x.com/Ibidi_Untold)


