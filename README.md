# Frontend Mentor - Stats Preview Card Component

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Links

- Solution URL: [https://www.frontendmentor.io/solutions/responsive-stats-preview-card-component-flexbox-layout-ItigZ0-15]
- Live Site URL: [https://imvillarosa.github.io/responsive-preview-card-component-ui/]

## My process

I started with structuring my HTML boilerplate in Desktop-first workflow and then created a .scss file in order to make use of CSS Custom properties for convenience in assigning colors to fonts and elements within the project. For the layout, I used Flexbox to achieve the positioning of the sections within the stats preview card component.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

This is basically a recap and implementing Flexbox properties that I've learned in the past but I'm happy to the css structure I have finished. See CSS code snippets that I'm really proud of below:

```css
:root {
  // PRIMARY COLORS
  --bg-clr-main: hsl(233, 47%, 7%);
  --bg-color-card: hsl(244, 38%, 16%);
  --bg-accent: hsl(277, 64%, 61%);

  // NEUTRAL COLORS
  --main-neutral: hsl(0, 0%, 100%);
  --p-neutral: hsla(0, 0%, 100%, 0.75);
  --stat-neutral: hsla(0, 0%, 100%, 0.6);
}
```

```css
// STATS IMAGES STYLING
.stats-img {
  background-image: 
  linear-gradient(rgba(170, 92, 219, 0.5)),
  url('https://source.unsplash.com/QckxruozjRg');
  background-size: cover;
  width: 50%;
  border-top-right-radius: 1.125em;
  border-bottom-right-radius: 1.125em;
}
```

### Continued development

I still struggle with how positioning works in Flexbox. Visualizing and implementing the layout can really be tricky but I have seen how powerful Flexbox can be if implemented properly depending on the outcome that you would want your design to look. I feel like I'll be learning more about pseudo elements in my future projects.  

### Useful resources

- [https://www.youtube.com/watch?v=_-aDOAMmDHI] CSS em and rem explained #CSS #responsive - This helped me understand the compounding effect of EM's and REM's. 

## Author

- Website - [https://codepen.io/navimarcial] I don't have any personal website at the moment and mostly store my projects and side projects here.
- Frontend Mentor - [https://www.frontendmentor.io/profile/IMVillarosa](https://www.frontendmentor.io/profile/yourusername)
- Instagram - [https://instagram.com/navimarcial/]

