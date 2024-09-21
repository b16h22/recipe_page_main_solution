# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm).

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

![](./screenshots/desktop_design.png)
![](./screenshots/mobile_design.png)

### Links

- Solution URL: [Github repo](https://github.com/b16h22/recipe_page_main_solution)
- Live Site URL: [Github pages](https://b16h22.github.io/recipe_page_main_solution/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I learned how to style Unordered lists, Ordered lists & Tables with CSS. Also learned to build a reponsive layout that works different on desktop and mobile screens by using the CSS Media Query


```css
    li {
      font-family: Outfit;
      padding: 6px 16px;
      margin-left: -16px;
      list-style-position: outside;
      color: hsl(30, 10%, 34%);
    }

    li::marker {
      color: hsl(14, 45%, 36%);
    }
```

```css
    @media screen and (max-width:720px) {

      .card {
        padding: 0;
        border-radius: 0;
        margin-top: 0;
        margin-bottom: 0;
        max-width: 100%;
      }

      .coverimage {
        border-radius: 0;
        max-width: 100%;
      }

      .recipe {
        max-width: 100%;
        margin: 40px;   
      }

    }
```

### Useful resources

- [CSS Lists](https://www.w3schools.com/css/css_list.asp) - This is a good article that helped me understand CSS Lists styling.
- [CSS Media Query](https://www.w3schools.com/css/css_rwd_mediaqueries.asp) - This is a good article that helped me understand CSS Media Query and responsive layouts.

## Author

- Frontend Mentor - [@b16h22](https://www.frontendmentor.io/profile/b16h22)
