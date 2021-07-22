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


**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](./screenshot.jpg)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it. 

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

Tried different layouts for this design. Since this was my first challenge from Frontend Mentor, I was so naive when I first started. So my first approach to this solution is obviously float and I am not satisfied with the solution I submitted.

After some time, I learnt about FlexBox and Grid layouts and tried both with desktop-first approach. Since I was able to do it after several attempts, I thought of trying mobile-first approach. I chose to use Flex box layout because it is a simple 2 card layout and does not involve 2 dimensional. Flex box is perfect for single dimension. 

Other bigger learning aspect is making it RESPONSIVE. I chose 4 breakpoints . 

Default         -   Mobile            -   375px   -   900px
1st Breakpoint  -   Tablet Potrait    -   900px   -   1200px
2nd Breakpoint  -   Tablet Landscape  -   1200px  -   1440px
3rd Breakpoint  -   Laptop            -   1440px+

I had tough time making the image fit in the flex container when making it responsive. But I found out making the height to 100% solves this!

```css

        @include respond(tab-port){
            height: 100%;
            border-radius: 0 10px 10px 0;
        }

```

### Continued development

From this challenge, I learnt a lot as a beginner and I would like to continue learn more about flex box properties like flex-wrap, Grid layout and how to make responsive with these layouts.

### Useful resources

Advanced CSS course by Jonas Schmedtmann from Udemy - This course helped me to confidently approach this solution.

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

