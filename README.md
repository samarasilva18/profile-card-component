# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

In this README I go over my process of development for this challenge, the things I learned and the tools I used trying to get my page as close to the design as possible.

### The challenge

- Build out the project to the designs provided

### Screenshot

![](./screenshot.png)
![](./screenshot-mobile.png)

### Links

- Solution URL: [Solution](https://www.frontendmentor.io/)
- Live Site URL: [Live Site](https://samarasilva18.github.io/profile-card-component)

## My process

1. As always, I decided to do the project with a Mobile-First mindset.
2. I structured the HTML, and I actually learned something really important this time. It's not good practice to use only component names such as "h1" or "p" in the stylization, and it's good to give elements their class for better scalability and for later maintenance, so I'm going to watch out for that from now on and maybe update older projects with this better practice!
3. I stylized the page using Flexbox and Sass, the most difficult part being the background-position.
4. I stylized the background again for the desktop version.
5. I wrote the README.
6. I uploaded the project to GitHub.

### Built with

- CSS custom properties
- Flexbox
- Mobile-first workflow
- [Sass](https://sass-lang.com/) - Preprocessor

### What I learned

I learned a lot about Sass during this project, it really was an interesting and eye-opening tool! I really liked the ability to nest things in Sass in particular!

```scss
.profile-section {
    text-align: center;
    a {
        color: $color-black;
        font-weight: 700;
        font-size: 1.2rem;
        margin-top: 1rem; 
    }
    p {
        color: $color-gray;
        font-size: 0.6rem;
        margin-top: 0.4rem;
        letter-spacing: 0.1rem;
    }
}
```

### Continued development

I finally tried out a new tool, Sass! It was a pretty fun and challenging experience to get it working and to figure out how to use it! Next I'm eyeing REACT, and I'm going to tackle a project of higher level such as a junior challenge!

### Useful resources

- [Sass Guide](https://sass-lang.com/guide/) - Sass has amazing documentation that really helped me set up the preprocessor and figure out how to use it for the first time!
- [CSS Background Position Property](https://www.w3schools.com/cssref/pr_background-position.php#:~:text=The%20background%2Dposition%20property%20sets,repeated%20both%20vertically%20and%20horizontally.) - This was incredibly helpful for me to be able to put the background images where they are shown in the designs! I couldn't make it fully responsive, so if anyone could help me out I'd be really grateful!

## Author

- Frontend Mentor - [@samarasilva18](https://www.frontendmentor.io/profile/samarasilva18)
- Github - [samarasilva18](https://github.com/samarasilva18)