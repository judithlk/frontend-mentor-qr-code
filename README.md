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

### Screenshot

![](./images/judith%20qr-code%20desktop%20view.png)

### Links

- Solution URL: [https://github.com/judithlk/frontend-mentor-qr-code](https://github.com/judithlk/frontend-mentor-qr-code)
- Live Site URL: [https://judithlk.github.io/](https://judithlk.github.io/)
## My process

I started out with the basic HTML of the page, index.html. Next I created my .scss and .css files and started Sass watching in the terminal.

Using the style guide and the design images I was given, I proceed to work on my .scss file after linking the .css to the HTML file.

I ensured to design for mobile first, and then for other screen sizes.

### Built with

- HTML5
- CSS 
- Flexbox
- Mobile-first workflow
- [Sass](https://www.sass-lang.com/) - Sass preprocessor


### What I learned

I started learning Sass yesterday and I was able to implement it in this project. Below is a snippet of my Sass code making use of @mixin and @include.

```scss
@mixin wrapper-style($height, $width) {
    min-height: $height;
    width: $width;
}

.wrapper {
    @include wrapper-style($height: 50vh, $width: 75vw);
}
```


### Continued development

Moving forward, I want to make use of preprocessors more in styling my webpages.


### Useful resources

- [Sass Basics](https://www.sass-lang.com/) - This tutorial walked me through the use of Sass
- [W3Schools Sass Tutorial](https://www.w3schools.com/sass/) - This tutorial also came in handy for me.


## Author

- Website - [Judith Yusuf](https://www.github.com/judithlk/)
- Frontend Mentor - [@judithlk](https://www.frontendmentor.io/profile/judithlk)
- Twitter - [@judithyusuf__](https://www.twitter.com/judithyusuf__)
- LinkedIn - [Judith Yusuf](https://www.linkedin.com/in/judith-yusuf-21u14n/)

