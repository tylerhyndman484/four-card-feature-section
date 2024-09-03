# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](/Four-Feature-Card-Screenshot.png)

### Links

- Solution URL: [GitHub](https://github.com/tylerhyndman484/four-card-feature-section.git)
- Live Site URL: [Netlify](https://four-card-feature-project-fm.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

This project was a very helpful one to complete as i have struggled recently to do grid layouts that arent necessarily simple as just adding rows and columns. I got great exposure to using grid-template-areas and manipulating the layout to be exactly how i wanted it. Getting the two side card to split between the rows to be centered was a challenging one for me to figure out.

```css
@media screen and (min-width: 650px) {
  .cardContainer {
    margin: auto;
    max-width: 900px;
    gap: 1.5rem;
    grid-template-columns: 1fr 1fr 1fr;
    grid-template-areas: 
      "Supervisor Team Calculator"
      "Supervisor Karma Calculator";
  }
  

  .cardOne {
    grid-area: Supervisor;
  }

  .cardTwo {
    grid-area: Team;
  }

  .cardThree {
    grid-area: Karma;
  }

  .cardFour {
    grid-area: Calculator;
  }
}
```

### Continued development

I am going to continue to develop myself on the use of grid and flexbox to be more comfortable manipulating the layout of a site.

## Author

- Website - [No website yet](https://www.your-site.com)
- Frontend Mentor - [@tylerhyndman484](https://app.netlify.com/teams/tylerhyndman484)
- Twitter - [@TylerHyndman](https://www.linkedin.com/in/tyler-hyndman-11327b140/)

## Acknowledgments

I wanted to shout out paulina-kottlewska on github. I could not figure out what i was doing wrong with the grid-template-areas because no matter what i did, my side cards would not center vertically. Her solution on this project really helped me grasp it, so i wanted to shout that out!
