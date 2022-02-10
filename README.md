# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout depending on their device's screen size

### Screenshot
This is the screenshot for desktop
![This is the screenshot for desktop](https://github.com/kmeganiz/stats-preview-card-component-main/blob/main/stat-preview-card_desktop_screenshot.jpg)

This is the screenshot for mobile
![This is the screenshot for desktop](https://github.com/kmeganiz/stats-preview-card-component-main/blob/main/stat-preview-card_mobile_screenshot.jpg)

### Links

- Solution URL: [https://github.com/kmeganiz/stats-preview-card-component-main/](https://github.com/kmeganiz/stats-preview-card-component-main)
- Live Site URL: [https://kmeganiz.github.io/stats-preview-card-component-main/](https://kmeganiz.github.io/stats-preview-card-component-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned
I am a beginner, below are the step by step, I am doing mobile first

1. Create a card. As below:
```
<div class="card"></div>
```

2. Add the image into the card.
```
<img src="images/image-header-desktop.jpg" class="img-header"  alt="office">
```

3. Add the heading
```
<h1></h1>
```
4. Add the paragraph
```
<p></p>
```
5. Add the statistic content, I am using unordered list 
```
<ul>
  <li></li>
</ul>
```
6. We could remove the bullet in ul do in the css style using: 
```
.stat ul {list-style-type: none;}
```
7. Applying min-height: 100vh to the body element means that the initial body height will take 100% of the viewport height, whereas the use of min-height instead of height will let the body element grow even more if necessary.

8. For mobile the flex direction is column, hence for desktop is row.
```
body {
  background-color: var(--main-bg);
  display: flex;
  min-height: 100vh;
  flex-direction: column;
}
```
9. Since only require


### Continued development
Still continue to develop


### Useful resources
- [CSS Variables - The var() Function](https://www.w3schools.com/css/css3_variables.asp) - We can do a global variables declare it inside the :root selector. 
- [CSS Card in CSS](https://www.w3schools.com/howto/howto_css_cards.asp) - first thing first create the card
- [CSS Padding](https://www.w3schools.com/css/css_padding.asp) - add padding to put space in between the content
- [CSS Line Height Property](https://www.w3schools.com/cssref/pr_dim_line-height.asp) - using this one for the paragraph
- [CSS Unordered List](https://www.w3schools.com/html/html_lists_unordered.asp) - create unordered list
- [Unordered List without Bullets in CSS](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_lists_unordered_none) - let's remove the bullet
- [CSS Border Radius](https://www.w3schools.com/cssref/css3_pr_border-radius.asp) - add the border radius top and bottom
- [CSS Text Transform](https://www.w3schools.com/cssref/pr_text_text-transform.asp) - change all text to uppercase
- [CSS Filter](https://www.w3schools.com/css/tryit.asp?filename=trycss_ex_images_filters) - I am using this to do the purple overlay.
- [CSS Flexbox](https://www.w3schools.com/css/css3_flexbox.asp) - Applying the flex.
- [CSS Grid](https://www.w3schools.com/css/css_grid.asp) - I am still currentyly studying this, decided to use flex instead.


## Author

- Website - [Katherin Meganis Phang](https://www.kmeganiz.com)
- Frontend Mentor - [kmeganiz](https://www.frontendmentor.io/profile/kmeganiz)
- Twitter - [@kmeganiz](https://www.twitter.com/kmeganiz)
- LinkedIn - [kmeganiz](https://www.linkedin.com/in/kmeganiz/)


## Acknowledgments
Thank you to Grace @grace-snow

### Licence
I am using this [MIT Licence](https://choosealicense.com/licenses/mit/#suggest-this-license)
So I get my licence here.
