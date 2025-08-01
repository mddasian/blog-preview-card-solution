# Frontend Mentor - Blog preview card solution

This is my solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS).

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](/screenshot/blog-preview-card.png)
![](/screenshot/blog-preview-card-hover.png)

### Links

- Solution URL: [Add solution URL here](https://github.com/mddasian/blog-preview-card-solution)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox


### What I learned

I practiced applying my skills in HTML and CSS in Frontend Mentor's Blog Preview Card Challenge. This problem was like the previous challenge, QR Code Component, but it had more features to it. Looking at the design, I visualized whether or not some elements needed padding or margin, what size and weights the text was, and deciding to use flexbox or grid. 


```html
<div class="card">
  <img id="illust" src="/assets/images/illustration-article.svg">
  <div>
    <p id="p-1">Learning</p>
    <p id="p-2">Published 21 Dec 2023</p>
    <p id="p-3">HTML & CSS foundations</p>
    <p id="p-4">These languages are the backbone of every website, defining structure, content, and presentation.</p>
  </div>
  <div class="author">
    <img id="avatar" src="/assets/images/image-avatar.webp">
    <p id="p-5">Greg Hooper</p>
  </div>
</div>
```
```css
.card {
    background-color: hsl(0, 0%, 100%);
    box-shadow: 10px 10px;
    border-color: black;
    border-style: solid;
    border-width: 0.1em;
    padding: 1.5em; 
    display: flex;
    flex-direction: column;
    width: 22em;
    border-radius: 20px;
    margin-bottom: 10px;
}
```