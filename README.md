# Frontend Mentor - Product list with cart solution

This is a solution to the [Product list with cart challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-list-with-cart-5MmqLVAp_d). 
Frontend Mentor challenges help to improve coding skills by building realistic projects. 


## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
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

- Add items to the cart and remove them
- Increase/decrease the number of items in the cart
- See an order confirmation modal when they click "Confirm Order"
- Reset their selections when they click "Start New Order"
- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page


### Screenshot

[!Screenshot](screenshot.webp)


### Links

- Page URL: [[https://hermanbossou.github.io/product-list-with-cart-main/]([https://hermanbossou.github.io/product-list-with-cart-main/])


## My process

### Built with

- Semantic HTML5 markup
- CSS: Flexbox and Grid for the layout
- JavaScript: DOM manipulation, event handling, and cart logic


### What I learned

During this project, I focused on:

	1. Responsive Image Handling: Implementing the <picture> element to serve the most 			appropriate asset based on the user's viewport, improving performance.

2. UI State Management: Managing the transition between the "Add to Cart" button and the "Quantity Selector" using sibling elements and utility classes like .hidden.

3. SVG Integration: Using Inline SVGs to allow full CSS control over icons for better interactive states (:hover and :focus).

4. DOM Traversal: Effectively using methods like .closest() to navigate and update specific product cards without interfering with others.


### Development Roadmap

- **Phase 1**: Complete the static integration (HTML/CSS) for the full layout.

- **Phase 2**: Implement the JavaScript logic for real-time cart calculations and UI updates.

- **Phase 3**: Refactor the project to fetch data dynamically from data.json instead of hardcoding 	the product list.



### AI Collaboration

For this project, I used Google Gemini AI to optimize my workflow:

- Debugging Assistant: Gemini helped me identify and fix CSS selector issues and JavaScript DOM traversal logic.

- Refactoring: I used AI to brainstorm more efficient ways to structure the sibling elements for the "Add to Cart" state.

- Documentation: The AI assisted in drafting a professional README that highlights my technical skills.


## Author

- Frontend Mentor - [@HermanBossou](https://www.upwork.com/freelancers/~01eddad045ad5f65dd)
- Freelance - WordPress Developer & Frontend Integrator


