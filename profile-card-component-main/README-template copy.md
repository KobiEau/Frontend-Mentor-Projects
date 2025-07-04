# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- Build out the project to the designs provided
- To build a profile card with the designs provided

### Screenshot
Find the screenshot of the site in the images folder

### Links

- Solution URL: [Solution URL](./images/Website_Screenshot%202025-07-03%20235120.png)
- Live Site URL: [Profile Card](https://kobieau.github.io/Frontend-Mentor-Projects/profile-card-component-main/index.html)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- Google Fonts

### What I learned

 **recap over some of your major learnings while working through this project.** 

- It's better to group stats and their values in the same div instead of separating them.
```html
 <div class="stats">
    <div class="stat-child">
      <div class="stat-number">80K</div>
        <div class="stat-description">Followers</div>
    </div>
      <div class="stat-child">
        <div class="stat-number">803K</div>
        <div class="stat-description">Likes</div>
      </div>

      <div class="stat-child">
        <div class="stat-number">1.4K</div>
        <div class="stat-description">Photos</div>
      </div>
  </div>
```
```css
.stats{
    display: flex;
    flex-direction: row;
    text-align: center;
    justify-content: space-evenly;
    align-items: center;
    text-align: center;
}
```

### Continued development

**Areas that I want to continue focusing on in future projects.**

- I would improve the background designs and the alignment of the statistics


### Useful resources

- [CSS Flexbox crash course](https://www.youtube.com/watch?v=wsTv9y931o8&t=126s) - This helped me to learn the basic ins and outs of CSS flexbox.


## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

## Acknowledgments

- My instructors Paul Dwamena and Salim Jamal built something similar and I drew inspiration from that.
