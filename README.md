# Frontend Mentor - Results summary component solution

This is a solution to the [Results summary component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/results-summary-component-CE_K6s0maV). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshot

![](./Screenshot%20(16).png)



### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow


### What I learned

How to style svgs
How to build responsive websites
Using media quries

```css
@media (max-width: 1000px) {
    .container{
        height: 80%;
        flex-direction: column;
        text-align: center;
    }
    .results, .results_summary
    {
        width: 100%;
    }
    .results_summary{
        border-bottom-right-radius: 0px;
        border-top-right-radius: 0px;
        border-bottom-left-radius: 20px;
        border-bottom-right-radius: 20px;
    }
    .scores tr{
        width: 90%;
    }
}
```



### Continued development

Project can be improved upon by using javascript to make the site more dynamic.


### Useful resources

- [Example resource 1](https://getcssscan.com/css-box-shadow-examples) - This helped me for learn to style box shadows. I really liked this pattern and will use it going forward.



## Author

- Website - [Mends Opoku Desmond](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/Desmends27)
