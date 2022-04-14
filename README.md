# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Overview

### Links
[Click me to visit the Live Site](https://practice.codingkelvin.fun/qr_code_component/)

### Screenshot

![](https://imgbed.codingkelvin.fun/uPic/ZkV4MA.png)

### Built with

- Semantic HTML5 markup
- CSS custom properties


### What I learned
> Using Absolute Position to Vertically and Horizontally center a `div`.
```html
<body>
  <div class="box"></div>
</body>
```
Because I want to vertically center a `div` that is contained in the `body`, it is important to give the body a height and a width, which is the 100% of the `HTML` page.
```css
html {
    height: 100%;
    width: 100%;
}

body {
    position: relative;
    height: 100%;
    width: 100%;
}

.box {
    position: absolute;
    width: 290px;
    height: 430px;
    /* Vertically Center and Horizontally Center */
    top: 50%;
    left: 50%;
    transform: translateY(-50%) translateX(-50%);
}
```



### Continued development

- Try to learn **Vertically Align Items** with CSS

### Useful resources

- [5 ways to vertically center with CSS](https://www.youtube.com/watch?v=qJVVZYTYA9U&t=3s) - A Youtube video that gives me the idea of how to center an item.
- [Why is my top: 50% CSS not working?](https://stackoverflow.com/questions/41502260/why-is-my-top-50-css-not-working) - A stack overflow answer that inspires me to give the `body` width and a height.


## Author

- My Blog - [Kelvin Qiu](https://www.codingkelvin.fun)


## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.

