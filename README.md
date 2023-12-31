# Frontend Mentor - [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7).

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](https://i.imgur.com/c0bG6oO.png)

### Links

- Live Site URL: [Live](https://solracss.github.io/fem-testimonials-grid-section/)

## My process

### Built with

[![My Skills](https://skillicons.dev/icons?i=html,css,sass,vscode,vite)](https://skillicons.dev)

### What I learned

1. Configure Vite to serve simple static site from `src/` folder, and having all `img` copied to `dist` after `run build` script is executed.

2. Use some of Sass magic like loops for creating few utility classes

````css
@each $color, $shade-map in $colors {
	@each $shade, $value in $shade-map {
		.clr-#{$color}-#{$shade} {
			color: $value;
		}
		.bg-#{$color}-#{$shade} {
			background-color: $value;
		}
	}
}```
````
