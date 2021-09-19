# Frontend Mentor - Social proof section solution

This is a solution to the [Social proof section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-proof-section-6e0qTv_bA). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout for the section depending on their device's screen size

### Screenshots

![](./images/desktop layout.png)
![](./images/mobile layout.png)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process
- I coded with a mobile-first workflow. First I worked on the html structure and getting everything in-place, and then I worked on the css. I used grid to allow for ease of layout switching when using media queries for larger device sizes.

### Built with

- HTML5 markup
- CSS
- CSS Grid & Flexbox
- Mobile-first workflow


### What I learned

I'm very new to html & css so this was a great learning experience for me. It was my first time working with a mobile-first workflow and also my first time using grid. Using grid-area-templates like:

```css
.container {
  display:grid;
  grid-template-columns: 1fr 1fr;
  grid-template-rows: 1fr 1fr;
  grid-template-areas: 
  "content1 content2"
  "content3 content3";
}
```
was really useful for me. It makes layout creation a lot easier and is good for visual learners like myself. It also allows you to completely redesign your layout with media queries super easily.


### Continued development

Since it was my first time using grid, I think I have some ways to go until I'm fully comfortable with positioning etc. I need to work on positioning grid-items and get that drilled into my head. My solution is probably very messy due to it being my first time, but I'm looking forward to improving!


## Author

- Frontend Mentor - [@beeching](https://www.frontendmentor.io/profile/beeching)

