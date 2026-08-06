# Frontend Mentor - Four card feature section solution. [Original challenge.](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK)

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learnt](#what-i-learnt)
  - [Useful resources](#useful-resources)
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

All of the screenshots of the layout are located in the "screenshots" directory (./screenshots/...)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [GitHub Pages](https://redbegoon.github.io/four-card-feature-section-layout/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learnt

When working on this project I learnt how to use grid in this type of projects. Here is how: 

```html
<section class="section-cyan">
  ...
</section>
<section class="section-red">
  ...
</section>
<section class="section-orange">
  ...
</section>
<section class="section-blue">
  ...
</section>
```
```css
main {
    width: 69.625rem;
    height: 33.25rem;
    margin: 0 auto;

    display: grid;                                  /* Styling main section via*/
    grid-template-columns: repeat(3, 21.875rem);    /* grid layout */
    grid-template-rows: repeat(4, 6.8125rem);
    gap: 2rem;
}

.section-cyan {                         /* Setting grid areas for box sections */
    grid-area: 2 / 1 / 4 /3;
}
.section-red {
    grid-area: 1 / 2 / 3 / 2;
}
.section-orange { 
    grid-area: 3 / 2 / 4 / 2;
}
.section-blue { 
    grid-area: 2 / 3 / 3 / 3;
}
```

### Useful resources

- [MDN documentation](https://developer.mozilla.org/en-US/docs/Web)
- [Doka.guide](https://doka.guide)

### AI Collaboration

In this project AI was not used.

## Author

- GitHub - [Redbegoon](https://github.com/Redbegoon)
- Frontend Mentor - [@Redbegoon](https://www.frontendmentor.io/profile/Redbegoon)

## Acknowledgments

I want to thank Frontend Mentor community. I see, that this community want's to grow and grow, no matter what. It's really inspiring. From my side, I also help some newbies, cause it's cool and you feel like you're doing a kind thing.
