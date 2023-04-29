# Frontend Mentor - Results summary component solution

This is a solution to the [Results summary component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/results-summary-component-CE_K6s0maV). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents
  - [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- Learned to deal position: absolute;
- use media queries to make the website responsive 

### Screenshot

![](./screenshot.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

- Analyze the layout and structure of the webpage.
- Create the HTML skeleton of the webpage.
- Add content to the webpage using HTML tags.
- Style the webpage using CSS.
- Add images and media files to the webpage.
- Test the webpage on different browsers and devices to ensure it's responsive and functional.
- Make necessary adjustments and improvements to the webpage based on the testing results.


### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

To see how you can add code snippets, see below:

```html
<img src="./images/icon-reaction.svg" alt="Reaction-icon" />
 <!-- I was stunned at first by the data.json file but it was easy to import the images to their places (I know that I'm not supposed to do it like this but I'm not using JS this time ) -->
```
```css

/* from */
.card{
  position: absolute;
  top: 50%;
  transform: translate(-50%, -50%);
  left: 50%;
}
/* to */
@media (max-width: 768px) {
    .card{
        width: 100%;
        flex-direction: column;
        top: auto;
        left: auto;
        transform: none;
    }
}
/* at first I thought that position: static; would cance the code I wrote at first but surprise for me it didn't work and gave me a headache till i discoverd the right way to cancel it */
```

### Useful resources

- [ChatGPT](https://www.chatgpt.com) - This helped me to write my HTML in Semantic and to avoid spending my time googling my issues
