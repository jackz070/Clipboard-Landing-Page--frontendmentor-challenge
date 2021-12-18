# Frontend Mentor - Clipboard landing page solution

This is a solution to the [Clipboard landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/clipboard-landing-page-5cc9bccd6c4c91111378ecb9). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Links

- Solution URL: [Add solution URL here](https://github.com/jackz070/Clipboard-Landing-Page--frontendmentor-challenge)
- Live Site URL: [Add live site URL here](https://jackz070.github.io/Clipboard-Landing-Page--frontendmentor-challenge/)

## My process

This challenge was my first attempt at writing a lot of code before previewing it. It went really well for me!
After doing coming up with the design system for this project I've wrote whole markup and created many global classes before previewing the result. It was really refreshing to employ more thinking and conceptualizing than viewing and trial and error approach.

I've then built the page, desktop-first, in a couple of hours. The media queries are a all over the place, I hope to fix them.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Desktop-first workflow
- A lot more conceptualizing than I've ever done before
- Global CSS classes instead of specific selectors when possible

### What I learned

I've learnt of the value of certain selectors I've avoided using before, in this case the so-called Lobotomized Owl Selector (more info here: https://alistapart.com/article/axiomatic-css-and-lobotomized-owls). It allowed me to get the flow of the page much easier, with all the content boxes that have another before them receiving desired margins.

```css
.container > * + * {
  margin-top: 6rem;
}
```

### Continued development

I'm hoping to fix the media queries in this project, and work on ordering them better in the future. The three general topics I'm focusing on are:

- fluid designs, so that my media queries won't involve repeating so much code again
- understanding and using the 'funny' selectors
- choosing projects that are more complex so that it makes practicing using sass more beneficial

### Useful resources

- https://alistapart.com/article/axiomatic-css-and-lobotomized-owls - an article about he aforementioned Lobotomized Owl Selector
- https://every-layout.dev/ - when looking for some small layout problem solution I've come across this page by Heydon Pickering & Andy Bell and their practical writing on creating layouts in CSS made me excited about it all!

## Author

- Website - Jacek Smoter
- Frontend Mentor - https://www.frontendmentor.io/profile/jackz070
