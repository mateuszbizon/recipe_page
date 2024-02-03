# Frontend Mentor - Recipe Page

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
    - [Links](#links)
- [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### Links

- Live Site URL: [https://mateuszbizon.github.io/recipe_page/](https://mateuszbizon.github.io/recipe_page/)

## My process

### Built with

- html5
- scss
- flexbox
- gulp

### What I learned

This was first project where I used gulp. It helped me to make live server while making changes and live sass compiler. I also learned how I can change color or anything with li elements in lists using pseudoelement named **marker**.

```scss
@mixin list-item($markerColor, $color) {
	padding-left: 15px;
	color: $color;

	&::marker {
		color: $markerColor;
	}
}
```

### Useful resources

- [w3schools](https://www.w3schools.com/howto/howto_css_bullet_color.asp)

## Author

- Frontend Mentor - [@mateuszbizon](https://www.frontendmentor.io/profile/mateuszbizon)