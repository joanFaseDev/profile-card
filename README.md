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
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

- Build out the project to the designs provided

### Screenshot

![](./images/profile-card-desktop.png)
![](./images/profile-card-mobile.png)

### Links

- Solution URL: [Project on Github](https://github.com/joanFaseDev/profile-card)
- Live Site URL: [Project hosted through Vercel](https://profile-card-ochre-seven.vercel.app/)

## About myself

Hi everyone! I'm an aspiring front-end developper so this project is probably not the best learning material out there yet i'll try to note what i deem important and that to the best of my abilities. Which brings me to my second point: english isn't my first language so please forgive me for any mispellings or grammatical errors, past or future. Now that's out of the way, let's dig in!

## My process

### Analysis

- Interesting background made out of two partially overflowed SVGs and, on a layer below, what appears to be a gradient.
- Only difference between mobile and desktop design seems to be larger margins between the Followers, Likes and Photos entries at the bottom of the card.
- Card can be divided in three parts: Photo, infos and social medias.

### Planning

#### HTML

- Create a _main_ element to act as the profile card.
- Create two _sections_, one for the user's info, the other for his social medias.
- In the first _section_, create two _divs_. The first for the photo and the background's card. The second for the name, age and city. Use _h2_ and _h3_ for the various entries, mainly because these elements are already weighted. Plus their font size seems to match the template.
- In the second _section_, create three _divs_. One for each metrics (followers, likes and photos). By doing so, aligning theses entries later will be really easy. Plus each _div_ can be transformed in a flexbox to align vertically its number and its name.

#### CSS

- Use Flexbox to align the three parts as well as the items nested inside.
- Use Negative margin to easily offset the user's photo on the SVG background.
- User view units on the SVGs in the body to make them responsive.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

- I learned a lot about background properties and how difficult it can be to position different elements out of their containers (It's probably not THAT difficult. It just seems so at my level.).
- Admitting its own inability to solve a problem and asking for advice is better than stubbornly insisting by oneself. Trying alone have its own merits, it also have a time limit!

### Continued development

- I need to review the position property and its different values.
- I also need to learn to adapt more quickly when difficulties arise for i have a tendancy to not think enough and go further and further in the wrong way.

### Useful resources

- [MDN Article || At-rules](https://developer.mozilla.org/en-US/docs/Web/CSS/At-rule) - Explain how At-rules CSS statements change the way the language works and how to use them.

## Author

- Frontend Mentor - [@joanFaseDev](https://www.frontendmentor.io/profile/joanFaseDev)
