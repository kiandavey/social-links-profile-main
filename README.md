# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page
- Navigate the links cleanly and completely using only their keyboard

### Links

- Solution URL: [https://www.frontendmentor.io/solutions/social-links-profile-built-with-semantic-html-and-flexbox-X911](https://www.frontendmentor.io/solutions/social-links-profile-built-with-semantic-html-and-flexbox-X911)
- Live Site URL: 

## My process

### Built with

- Semantic HTML5 markup
- CSS Custom Properties (Variables)
- Flexbox layouts
- Keyboard Accessibility (:focus-visible)

### What I learned

During this challenge, I learned how to optimize semantic groupings for lists of external links. Instead of standard generic button configurations, wrapping anchors inside an unordered list improves the user experience for assistive technologies. 

I also refined my understanding of default browser spacing layouts, using custom overrides to remove default list nesting paddings:

```html
<ul class="socials">
  <li><a href="[https://github.com](https://github.com)" target="_blank" rel="noopener noreferrer">GitHub</a></li>
  <li><a href="[https://www.frontendmentor.io](https://www.frontendmentor.io)" target="_blank" rel="noopener noreferrer">Frontend Mentor</a></li>
</ul>
```
```css
.socials {
    list-style: none;
    padding: 0; 
}

.socials li a:hover,
.socials li a:focus-visible {
    background-color: hsl(75, 94%, 57%);
    color: hsl(0, 0%, 12%);
}
```

## Continued development
In upcoming projects, I intend to continue structuring elements with high accessibility standards from the initial phase, writing meaningful micro-commits on Git progressively as components reach completion to maintain cleaner delivery timelines.

## AI Collaboration
Tools Used: Gemini

Usage Strategy: Assisted in refining markup selection semantics, implementing focus state visual structures for keyboard accessibility compliance, and debugging list item box container alignment behaviors.

## Author
Frontend Mentor - [@kiandavey](https://www.frontendmentor.io/profile/kiandavey)
