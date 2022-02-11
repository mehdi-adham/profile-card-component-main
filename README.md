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
  - [Useful resources](#useful-resources)
- [Author](#author)



## Overview

### The challenge

- Build out the project to the designs provided

### Screenshot

![](images/screenshot.jpg)


### Links

- Solution URL: [My solution URL](https://www.frontendmentor.io/solutions/profile-card-component-TGTtbwZ89)
- Live Site URL: [My live site](https://mehdi-adham.github.io/profile-card-component/index.html)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox


### What I learned

I use multiple background images for body element.


```css
body{
    font-size: var(--name-stats-font-size);
    font-family: var(--Kumbh-Sans-font);
    background-color: var(--Dark-cyan);
    background-image: url(images/bg-pattern-top.svg), url(images/bg-pattern-bottom.svg);
    background-repeat: no-repeat, no-repeat;
    background-position: bottom 35vh right 50vw, top 50vh left 50vw;
    /*background-position: top 50vh left 10vw, bottom -515px right -125px;*/
    /*background-size: 800px auto, 800px auto;*/
}
```


### Useful resources

- [CSS Multiple Backgrounds - w3schools](https://www.w3schools.com/Css/css3_backgrounds.asp) - In this chapter you will learn how to add multiple background images to one element.


## Author

- Website - [Mehdi Adham](https://github.com/mehdi-adham)
- Frontend Mentor - [@mehdi-adham](https://www.frontendmentor.io/profile/mehdi-adham)


