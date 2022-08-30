# Frontend Mentor - FAQ accordion card solution

This is a solution to the [FAQ accordion card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/faq-accordion-card-XlyjD0Oam). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See hover states for all interactive elements on the page
- Hide/Show the answer to a question when the question is clicked

### Screenshot

![](./screenshots/screenshot.png)

### Links

- Solution URL: [URL](https://your-solution-url.com)
- Live Site URL: [URL](https://lisviks.github.io/faq-accordion-card-frontendmentor/)

## My process

### Built with

- Semantic HTML5 markup
- Flexbox
- Mobile-first workflow

### What I learned

To show/hide text with only css.

```html
<label for="text">Read More</label>
<input type="checkbox" id="text" />
<p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Libero, repellat?</p>
```

```css
body {
  margin: 2rem;
}

label {
  padding: 1rem 2rem;
  border: 1px solid green;
  background-color: green;
  color: white;
}

input[type='checkbox'] {
  display: none;
}

p {
  display: none;
}

input[type='checkbox']:checked ~ p {
  display: block;
}
```

### Useful resources

- [Show/Hide text with CSS](https://stackoverflow.com/a/19357606)

## Author

- Website - [Deividas Rimkus](https://github.com/Lisviks)
- Frontend Mentor - [@Lisviks](https://www.frontendmentor.io/profile/Lisviks)
- Twitter - [@DRimkusDev](https://www.twitter.com/DRimkusDev)
