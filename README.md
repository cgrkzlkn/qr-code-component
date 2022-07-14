# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### Screenshot

![](./images/screenshot.jpg)

### Links

- Solution URL: [https://www.frontendmentor.io/solutions/qr-code-component-using-css-flexbox-IDX6wzhjTn](https://www.frontendmentor.io/solutions/qr-code-component-using-css-flexbox-IDX6wzhjTn)
- Live Site URL: [https://cgrkzlkn.github.io/qr-code-component/](https://cgrkzlkn.github.io/qr-code-component/)

## My process

### Built with

- HTML
- CSS
- Flexbox

### What I learned

Defining color variables in :root selector was useful for me:

```css
:root {
  --white: hsl(0, 0%, 100%);
  --lightGray: hsl(212, 45%, 89%);
  --grayishBlue: hsl(220, 15%, 55%);
  --darkBlue: hsl(218, 44%, 22%);
}

body {
  background-color: var(--lightGray);
}
```

I used both HTML5 and ARIA landmarks for accessibility of the web page:

```html
<header role="banner"></header>
<main role="main"></main>
<footer role="contentinfo"></footer>
```

### Useful resources

- [CSSmatic Box Shadow Generator](https://www.cssmatic.com/box-shadow) - This tool helped me to generate box-shadow code for CSS.

- [Deque University - Landmark](https://dequeuniversity.com/rules/axe/4.3/landmark-one-main?application=axeAPI) - In this web page, I learned to use HTML5 landmarks for accessibility of the web page..

## Author

- Website - [Cagri Kizilkan](https://cagrikizilkan.com)
- Frontend Mentor - [@cgrkzlkn](https://www.frontendmentor.io/profile/cgrkzlkn)
- Twitter - [@cgrkzlkn](https://www.twitter.com/cgrkzlkn)
