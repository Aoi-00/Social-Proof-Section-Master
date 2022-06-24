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


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the section depending on their device's screen size

### Screenshot

![Desktop 1440px](./images/desktop%201440x880.png)

![Mobile 375px](./images/mobile%20375px.png)
### Links

- Solution URL: [Source code](https://github.com/Aoi-00/Social-Proof-Section-Master)
- Live Site URL: [Hosted site](https://aoi-00.github.io/Social-Proof-Section-Master/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

Tried a mobile-first workflow for this particular challenge.
Made use of grid-area-template for this challenge instead of the usual grid-row/column or flexbox layouts.
Used pseudo selectors for cascading effects of review and rating.

```css
body {
        display            : grid;
        grid-template-areas: "header ratings"
            "reviews reviews"
            "attribution attribution";
        grid-template-columns: repeat(2,1fr) ;
        grid-template-rows: 1fr 1fr 10px;
    }
```

### Continued development

More practice on responsive layouts needed. Will be trying out Kevin Powell's free "Conquering Responsive Layout" 21 days challenge.


### Useful resources

- [stackoverflow](https://stackoverflow.com/) - This helped me with scrollbar and other viewport/sizing issues.


## Author

- Github - [Lee Hong Ying](https://github.com/Aoi-00/)
- Frontend Mentor - [@Aoi-00](https://www.frontendmentor.io/profile/Aoi-00)
- Discord - [Aoi#2708](https://discordapp.com/users/Aoi#2708/)

