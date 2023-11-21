# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued Learning](#continued-learning)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](./images/Screenshot%202023-11-14%20at%208.48.55%20PM.png)

### Links

- Solution URL: [This is the GitHub repository for the solution.](https://github.com/Logano-7/htmlCSSchallengeTestimonial)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

I really appreciated this project because of how valuble CSS Grid is. I wanted something that would teach me more about it. So I could apply what I learn to my own passion projects. I especially appreciate learning about the !Important command and how important (no pun intended) that is to getting everything working properly. The only real roadblock I faced was figuring out how to wrap the CSS Grid. Finally I noticed I mispelled "auto-fill" (typing "autofill" instead).

To see how you can add code snippets, see below:

```html
<img id="img5" src="./images/image-kira.jpg" alt="" />
<div class="cardUser">
  <div class="name">Kira Whittle</div>
</div>
```

```css
.proud-of-this-css {
  @media (max-width: 768px) {
    main {
      margin-top: 20px;
      grid-template-columns: repeat(auto-fill, minmax(50%, 1fr));
      grid-template-rows: minmax(auto, auto);
    }

    .cardMain {
      grid-column: unset !important ;
      grid-row: unset !important ;
    }
  }
}
```
### Continued Learning

While I was able to learn how to recreate this website, I would love to continue to dig depper into CSS Grid and Flexbox. Of course as I learn react and other frontend librarys and frameworks, I look forward to learning animations and all kinds of stuff I havn't even heard of yet.

### Useful resources

- Resource 1 - (https://youtu.be/uuOXPWCh-6o?si=s67NrvD9qWz_sNCx) - This helped me get a better grasp on CSS Grid. It was short and concise. I highly recommend Fireship Turtorials.
- Resource 2 - (https://youtu.be/yU7jJ3NbPdA?si=hNJce7IJb91Ti_kA) - This video helped a lot when having to figure out the Media Quereies for the project. Media Quereies are so important in Web development, and this tutorial is a great place to start.
- Resource 3 - (https://www.w3schools.com) - W3 Schools was critical is helping me understand concepts I wasn't too familiar with, but knew existed. 

## Author

- Website - [Logan Martin](https://www.linkedin.com/in/logan-martin-7-js)
- Frontend Mentor - [@Logano-7](https://www.frontendmentor.io/profile/Logano-7)
- GitHub - [@Logano-7](https://github.com/Logano-7).
