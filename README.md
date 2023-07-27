# Frontend Mentor - Results summary component solution

This is a solution to the [Results summary component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/results-summary-component-CE_K6s0maV)

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Responsive design

### What I learned

Instead of using vw for the width on media query for mobile size
screens we can set %, which will make sure that the horizontal scoll
bar is avoided by adjusting the content to remain within the container.

To see how you can add code snippets, see below:

```html
<h1>Some HTML code I'm proud of</h1>
```

```css
@media only screen and (max-width: 500px) {
  .container {
    margin: 50px auto;
    width: 100%;
    display: grid;
    grid-template-columns: auto;
  }
}
```

### Continued development

I will further explore about css, how I can make web pages responsive and
some other cool css tricks. I also have a plan to create a media query for
landscape viewport on mobile devices.

I have not set border-boxing correctly, I will update it soon.

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)

## Acknowledgments

Kewin Powell told in his 21-day responsive design series about
how can we make our web pages responsive by setting width to 100%.
