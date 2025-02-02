# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot
<br>Mobile</br>
![](./mobile%20Screenshot%202025-02-02%20at%2023-33-45%20Frontend%20Mentor%20Four%20card%20feature%20section.png)

<br>Desktop</br>
![](./desktop%20Screenshot%202025-02-02%20at%2023-33-08%20Frontend%20Mentor%20Four%20card%20feature%20section.png)

### Links

- Solution URL: [here]()
- Live Site URL: [here]()

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned


using flex to position the image in the card to the bottom right. Tried position relative and absolute but doesn't seem to work well.

```html
<div class="card__image-section">
	<img src="/images/icon-supervisor.svg" alt="supervisor icon" />
</div>
```

```css
.card__image-section {
	display: flex;
	justify-content: flex-end;
}

.card img {
	display: block;
}
```

to have the alignment of the cards in the desktop, I just use flex. 


