# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- See hover and focus states for all interactive elements on the page

### Screenshot

![Desktop Card](/screenshots/preview-card-desktop.png)
![Mobile Card](/screenshots/preview-card-mobile.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Blog Preview Card](https://bobfisherman18.github.io/blog-preview-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

My biggest challenge was resizing the webpage with the appropriate dimensions, so that users can still read the webpage whether they have a tablet, phone, laptop, Chromebook, or desktop. In addition, I learned how to use flex box. I was able line up the texts and images vertically.

```css
/* <main> element content-box
example:
 352 Width @ 1440*960
-269 Width @ 1357*960	     
  83
  /2
41.5
83 for every increment the resolution decreases
subtract 41.5 on both right and left margins
copied and pastied 14 times
don't know if there is an easier way to do this
  */

@media screen and (max-width: 1356px) {
  main {
    margin: 240px 497.5px 240px 498.5px;
  }
}
@media screen and (max-width: 1273px) {
  main {
    margin: 240px 456.5px 240px 457.5px;
  }
}

/*flex container in a flex container */
.name {
  display: flex;
  align-items: center;
  margin-top: -5px;
  margin-bottom: 10px;
}
```

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

### Continued development

I will continue to use CSS Flexbox.

### Useful resources

- [W3Schools](https://www.w3schools.com/) - This what helped me learn HTML and CSS.
- [Youtube](https://www.youtube.com/@BroCodez) - This Youtuber also helped me learn HTML and CSS. In addition, I watched a lot of Youtube videos about HTML and CSS. Youtube is your best friend in learning web development!

## Author

- GitHub - [BobFisherman18](https://github.com/BobFisherman18)
- Frontend Mentor - [@BobFisherman18](https://www.frontendmentor.io/profile/BobFisherman18)
- LinkedIn - [Jonah Rivera](https://www.linkedin.com/in/jonah-rivera-812490183/)

## Acknowledgments

I would like to thank Frontend Mentor for giving me the opportunity to practice my front-end development!
