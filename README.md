# Frontend Mentor - Fylo dark theme landing page solution

This is a solution to the [Fylo dark theme landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/fylo-dark-theme-landing-page-5ca5f2d21e82137ec91a50fd). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Full Screenshot

![](https://github.com/Karllouise-code/fylo-dark-theme-page/blob/master/images/fyloscreenshot.png)

### Links

- Solution URL: [https://www.frontendmentor.io/solutions/css-flexbox-grid-8Lh3uD6Cg](https://www.frontendmentor.io/solutions/css-flexbox-grid-8Lh3uD6Cg)
- Live Site URL: [https://karllouise-code.github.io/fylo-dark-theme-page](https://karllouise-code.github.io/fylo-dark-theme-page/)

### Built with

- HTML5
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

My knowledge on HTML and CSS is developed because of the given challenge. My confusion on flexbox and on css grids are now clear.

```html
<h1>Some HTML code I'm proud of</h1>
<script
  src="https://kit.fontawesome.com/de376feec1.js"
  crossorigin="anonymous"
></script>
```

```css
.proud-of-this-css {
  :root {
    /** Primary */
    --intro-email-background: hsl(217, 28%, 15%);
    --main-background: hsl(218, 28%, 13%);
    --footer-background: hsl(216, 53%, 9%);
    --testimonials-background: hsl(219, 30%, 18%);
    /** Accent */
    --cta-light: hsl(176, 68%, 64%);
    --cta-dark: hsl(198, 60%, 50%);
    /** Neutral */
    --font-color: hsl(0, 0%, 100%);
  }
}
```

```js
const proudOfThisFunc = function checkInputs() {
  //get values from the inputs
  const emailValue = email.value.trim();

  if (emailValue === "") {
    //show error
    // add error class
    setErrorFor(email, "Please enter a valid email address");
  } else if (!isEmail(emailValue)) {
    setErrorFor(email, "Please enter a valid email address");
  } else {
    //add success class
    setSuccessFor(email);
  }
};
```

### Continued development

For my future projects I want to try some projects wherein I got to test my javascript skills and then learn more about animations and try some css frameworks.

### Useful resources

- MDN Web Docs - [MDN Web Docs](https://developer.mozilla.org/en-US/) - This helped me for understanding the use of syntax to use on my css. I really liked this website and will use it going if there's a term I cannot understand.
- Kevin Powell - [Kevin Powell](https://www.youtube.com/kepowob/playlists?view=50&sort=dd&shelf_id=2) - This is an amazing instructor which helped me finally understand CSS GRIDS and CSS FLEXBOX. I'd recommend it to anyone still learning this concept.

## Author

- Github - [Karl Louise Rito](https://github.com/Karllouise-code)
- Frontend Mentor - [@Karllouise-code](https://www.frontendmentor.io/profile/Karllouise-code)
- Twitter - [@karl_rito](https://twitter.com/karl_rito)

## Acknowledgments

I would like to thank anyone who have helped me complete this project.
