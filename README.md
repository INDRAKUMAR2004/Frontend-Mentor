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

![](./screenshot.jpg)

### Links

- Solution URL: [Solution URL](https://www.frontendmentor.io/solutions/responsive-landing-page-using-css-grid-I3EJDPWkG0)
- Live Site URL: [Live site URL](https://responsivecssgrid.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
    <link rel="shortcut icon" href="favicon-32x32.png" type="image/x-icon">
</head>
<body>
    <div class="container">
        <div class="img-bg">
            
            <img src="image-qr-code.png" alt="">
            <p class="head">
                Improve your front-end skills by building projects
            </p>
            <p class="second">
                Scan the QR code to visit Frontend Mentor and take your 
                coding skills to the next level
            </p>
        </div>
    </div>
</body>
</html>
```
```css
@import url('https://fonts.googleapis.com/css2?family=Changa:wght@200..800&family=Kanit:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&family=Outfit:wght@100..900&family=Sevillana&display=swap');

*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    background: rgb(213, 225, 239);
}

.container{
    display: flex;
    flex-wrap: wrap;
}

.img-bg{
    background-color: rgb(255, 255, 255);
    border-radius: 20px;
    padding-top: 30px;
    width: 220px;
    height: 400px;
    margin-top: 100px;
   margin-left: 500px;

}

.container img{
    width: 200px;
    margin-left: 11px;
    border-radius: 10px;
    margin-top: -20px;
}

.head{
    font-family: Changa;
    background-color: white;
    font-size: 12px;
    display: flex;
    text-align: center;
    word-wrap: break-word;
    width: 200px;
    margin-left: 10px;
    font-weight: 600;
    color: rgb(31, 49, 79);
}

.second{
    background-color: white;
    font-family: Changa;
    font-size: 5px;
    display: flex;
    text-align: center;
    font-weight: 100;
    color: rgb(31, 49, 79);
    width: 200px;
    margin-left: 10px;
    height: 20px;
}

@media (max-width:450px){
    body{
        width: 450px;
    }

    *{
        margin-right: 320px;
    }

    .img-bg{
        background-color: rgb(255, 255, 255);
        border-radius: 20px;
        padding-top: 30px;
        width: 420px;
        height: 700px;
        margin-top: 400px;
       margin-left: 500px;
    
    }

    .container img{
        width: 390px;
        margin-left: 15px;
        border-radius: 10px;
        margin-top: -20px;
    }

    .head{
        font-family: Changa;
        background-color: white;
        font-size: 32px;
        display: flex;
        text-align: center;
        word-wrap: break-word;
        width: 400px;
        margin-left: 10px;
        font-weight: 600;
        color: rgb(31, 49, 79);
    }
    
    .second{
        background-color: white;
        font-family: Changa;
        font-size: 25px;
        display: flex;
        text-align: center;
        font-weight: 100;
        color: rgb(31, 49, 79);
        width: 400px;
        margin-left: 10px;
        height: 20px;
    }
}

@media (max-width:800px){
    body{
        width: 800px;
    }

    *{
        margin-right: 450px;
    }

    .img-bg{
        background-color: rgb(255, 255, 255);
        border-radius: 20px;
        padding-top: 30px;
        width: 420px;
        height: 700px;
        margin-top: 400px;
       margin-left: 500px;
    
    }

    .container img{
        width: 390px;
        margin-left: 15px;
        border-radius: 10px;
        margin-top: -20px;
    }

    .head{
        font-family: Changa;
        background-color: white;
        font-size: 32px;
        display: flex;
        text-align: center;
        word-wrap: break-word;
        width: 400px;
        margin-left: 10px;
        font-weight: 600;
        color: rgb(31, 49, 79);
    }
    
    .second{
        background-color: white;
        font-family: Changa;
        font-size: 25px;
        display: flex;
        text-align: center;
        font-weight: 100;
        color: rgb(31, 49, 79);
        width: 400px;
        margin-left: 10px;
        height: 20px;
    }
}
```


If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.


## Author

- Website - [INDRAKUMAR K](https://indrakumarkannan.netlify.app)
- Frontend Mentor - [@INDRAKUMAR2004](https://www.frontendmentor.io/profile/INDRAKUMAR2004)
- Twitter - [@INDRAKUMARK2004](https://x.com/INDRAKUMARK2004)