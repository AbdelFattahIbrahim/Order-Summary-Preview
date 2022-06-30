# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot

![](./screenshot.bmp)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties


### What I learned

So on this challenge I had to improvise for the section on the pricing of the subscription. Several different properties for different blocks. I created a <div> with the background color of the block and then separated each piece of text with a span and added styles for each one separately as needed.

```css
.div2{
    width: 250px;
    background-color: hsl(225, 100%, 98%);
    padding-top: 10px;
    padding-bottom: 10px; 
    border-radius: 10px;
    margin-left: auto;
    margin-right: auto;
}
```

Here are the <span>s I used:

```html
<span style="font-weight: bold;">Annual Plan</span><br>
<span class="span2">$59.99/year</span>
<span style="font-weight: bold; font-size: small; color: blue;" class="span1">Change</span></p>
```


### Continued development

I still need more work to do on how to import fonts into the css. This font had spaces in its name and I kept getting errors trying to import it. I didn't waste much time on it as I want to get my hands on some more exercises quickly to move to the next step.
The annual plan box was particularly challenging becasue I could not fiugre out hor to senter the "Chnage" text in the box.
More practice and other problems to solve.


## Author

Abdel Fattah Ibrahim

## Acknowledgments

Developer Direction community. Josh for taking the time to lead the course help. Kyle for introducing me to the group. All the other members of the community for their support.