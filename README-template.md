# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)


## Overview
The task was create a good looking qr component. I created this using the plain HTMl and CSS.

### Screenshot

![](./screenshot.png)

### Links

- Solution URL: 
- Live Site URL: 

## My process

Observed the different component of the tasks and understood the structure of the HTML. Noted it down to make the coding process smooth. I wrote the HTML and styled it with the CSS. That's it required for this task.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid


### What I learned

First time solving a available problems on an online plateform. Hope to continue solving the different tasks to get condident. Learn to work in professional way and how could I used simple tasks to save the time required for completing the projects.

```html
 <main>
    <div id="qr-comp">
      <div id="qr-code">
        <img src="./images/image-qr-code.png" alt="qr-code">
      </div>
      <h1>Improve your front-end skills by building projects</h1>
      <p>Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
    </div>
  </main>
```
```css
#qr-comp{
    width: 320px;
    height: fit-content;
    background-color: var(--white);
    padding: 16px;
    border-radius: 12px;
    font-family: "Outfit", serif;
    text-align: center;
}

#qr-code > img{
    width: 100%;
    border-radius: 10px;
    object-fit: cover;
}

#qr-comp h1{
    color: var(--slate-900);
    font-size: 24px;
    font-weight: var(--h-font-weight);
    margin: 22px auto;
}

#qr-comp p{
    color: var(--slate-500);
    font-size: var(--p-font-size);
    font-weight: var(--p-font-weight);
    padding: 12px;
}
```

### Continued development

I have the planned to continue to work on the tasks available on the frontendmentors.com to get more confidence in my skills and built a powerful protfolio as I already have the bundle of knowledge in the web development and zero confidence in my skills. I want to be confident and only way seem possible to me is by solving the problems.

## Author

- Name - Muhammad Arham
- Frontend Mentor - [@FA23BCS233](https://www.frontendmentor.io/profile/FA23BCS233)
