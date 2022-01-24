# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
 
 Here I used:

 1- Grid

 2- Flexbox

 3- Less use of margins and more of padding

 4- Importing fonts

 5- Structuring content inside grid containers 

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![demonstration.png]

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

This was my how-to-guide, use it as you wish!

- First we set a basic structure for the HTML where we set up the container, wrapper and boxes.

- Then with the style-guide.md we select the fonts and all the necessary elements for the challenge.

- We import the fonts from google fonts, personally I had an issue with a particular font ('Big shoulders Display'), so I linked it directly to the HTML.

- Insert the svg images as you like, by your own device or by drawing the svg directly in the HTML.

- Then in a stylesheet, separate each important section of the document to address every part with order.

- In the variables and assets section, create the variables and import your fonts.

- In card components style each container, thereby I mean the container, wrapper and boxes in this case.

- The major display here was flexbox to set easily the whole structure.

- Set up a wrapper to display boxes in a grid container.

- Used border radius and overflow to round and hide the corners from the main container.

- Added double classes to boxes in the HTML to address easier each box and common elements, such as the anchor, paragraph and headings.

- Padding the inner content of boxes to eliminate complications with text.

- In the content section, you add styles to the paragraph, here go the fonts, colors, styling of the anchor, margins and the transition of fading the anchor.

- Lastly the media queries where adapted to turn the grid columns from 3 to 1, this using as advantage the logic from grid, where all elements fit inside a single column without overlapping each other.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid


### What I learned

* Using double classes

* Adding padding to center the content instead of margins.

* Altering with one class various elements.

This styles inside the wrapper were extremely useful, so as for the anchor:

```css
 .wrapper {
        display: grid;
        grid-template-columns: 1fr 1fr 1fr;
        margin: 2rem;
        border-radius: 12px;
        overflow: hidden;
    }

    .box a {
        text-decoration: none;
        padding: 17px 28px;
        background: var(--Verylightgray);
        display: inline-block;
        margin-top: 60px;
        border-radius: 26px;
        border: 2px solid var(--Verylightgray);
        transition: all .4s ease-in-out;
    }

```
- Learn to imrprove my skills with grid and flexbox.

- Structure better the content inside the page.

- Use less margins and more the specific properties from the css and html

### Useful resources

- [Frontend course, theory](https://platzi.com/clases/frontend-developer/) - 

- [Frontend course, practical](https://platzi.com/clases/frontend-developer-practico/) -

 I find this resources extremely helpsful such as the entire platform.

## Author

- My repo - [@rockwatch](https://github.com/rockwatch)
- Frontend Mentor - [@rockwatch](https://www.frontendmentor.io/profile/rockwatch)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)


## Acknowledgments

All my respect and gratitude to [@Platzi](https://github.com/platzi) and [@teffcode](https://github.com/teffcode)

The community and who reads this, you rock!
