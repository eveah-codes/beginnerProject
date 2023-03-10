# Frontend Mentor - Advice generator app solution

This is a solution to the [Advice generator app challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/advice-generator-app-QdUG-13db). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the app depending on their device's screen size
- See hover states for all interactive elements on the page
- Generate a new piece of advice by clicking the dice icon

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Mobile-first workflow



### What I learned

I got to practice error handling with asynchronous programming

```js
   fetch(url)
        .then(response => response.json())
        .then(response => {
            adviceId.textContent += `Advice #${response.slip.id}`
            advice.textContent = `"${response.slip.advice}"`
        })
        .catch(error) {
        console.error("Error fetching advice:", error);
        return { error: "An error occured while fetching advice." };
    }
```

### Continued development

I would like to cache the response so I can improve the page's performance


## Author

- Website - [African Techie](https://www.africantechie.com)
  
