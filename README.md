# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Desktop-first workflow
- [Bootstrap](https://getbootstrap.com/) - Bootstrap framework

### What I learned

I think I have improved my Flexbox uses, though I struggle to see when it is better to use flexbox over the Bootstrap column and card system.

Besides that, I liked the use of the @media to be able to change a background photo based on screen size.

To see how you can add code snippets, see below:

```html
<div class="divPlan">

  <div class="divIconPricing">
    <div class="">
      <img src="images/icon-music.svg" alt="music icon">
    </div>

    <div class="divPricing">
      <h4 class="darkBlue">Annual Plan</h4>
      <p class="grey price">$59.99/year</p>
    </div>
  </div>
  <div class="">
    <button type="button" name="button" class="center btn btn-link text-decoration-none">Change</button>
  </div>
</div>
```
```css
.divPlan {
  display: flex;
  flex-direction: row;
  justify-content: space-around;
}

.container {
  display: flex;
  flex-direction: column;
  width: 350px;
  margin-left: auto;
  margin-right: auto;
  background-color: white;
  border-radius: 20px;
  padding: 0 0 10px 0;
}

.divIconPricing {
  display: flex;
  width: 175px;
  justify-content: space-around;
}
```

### Continued development

As mentioned in the previous section, the section with the icon, pricing, and change button is not my favorite. It doesn't feel clean or effective to me. I would like to learn a more effective way to shifting that row.

## Author

- Frontend Mentor - [@TaylorC19](https://www.frontendmentor.io/profile/TaylorC19)
