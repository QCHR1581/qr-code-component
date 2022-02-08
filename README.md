# Frontend Mentor - QR code component solution

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)

## Overview

The task was to create a site which looks like this: 
desktop-design.jpg

A QR Code whith text underneath which all is inside a white triangle. 

### Screenshot

Screenshot from my solution:
![](images/screenshot.png)

### Links

- Solution URL: [Add solution URL here](index.html)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

1. Step: Implement the necessary elements: image, text and rectangle. 
          - This was done in HTML and CSS. The correct images was linked in HTMl and the rectangle was created in CSS. 
            Which was also linked to the HTML file.
2. Step: Arrange every element so that they look like in the solution.
          - This was done in CSS. I used Flexbox to do this. The parent was the class "box" and the childs had the classes "rectangle", "image" and "text". 
3. Step: Edit the look of the elements so that they look like in the solution
          - This was done in CSS. The image and the rectangle had to have rounded corners. I used border-ration to make them look like that. 


### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I learned how to position elements whithin a website. 

My HTML code for this was: 

<div class="box">
    <div class="rectangle">
      <div class="image">
        <img src="images/image-qr-code.png">
      </div>
      <div class="text">
        <h1>Improve your front-end <br>
          skills by building projects</h1>
        <p>  Scan the QR code to visit Frontend<br>
           Mentor and take your coding skills to<br>
            the next level</p>
      </div>
      </div>
  </div>
  
  The CSS code for this was: 
  
  .box {
    display: flex;
    flex-direction:column;
    justify-content: center;
    align-items: center;
    flex-wrap: wrap;
    height: 99.49vh;
    }
    
    A relly important thing concerning Goolge Fonts was this: 
    
    **You have to import also the bold version therefore you can make the normal font bold!!!!**

### Continued development

I want to get a better understanding of creating a good looking layout in CSS. Therefore I want to learn more about Flexbox but also more about Bootstrap and CSS Grid. 

### Useful resources

- [Flexbox resource website](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - This helped me to know how to use Flexbox. It gives you a clear overview and displays the concept in simple way. 
- [Flexbox resource video](https://www.youtube.com/watch?v=dD8kgEOw1To) - This video was really helpful seeing Flexbox in live action. It sums it really shortly up and shows how the concept works in real live. 

