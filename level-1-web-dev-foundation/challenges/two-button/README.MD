# Two Buttons Meme Generator

A fun, interactive meme generator built with HTML, CSS, and JavaScript.

## Project Structure

<!--
two-buttons/
├── index.html
├── style.css
└── script.js
-->

## Features

- Two editable button labels — click and type to customize
- Editable bottom banner text
- Animated 3D press effect on buttons
- Random reaction message on button click
- Image placeholder ready for your own photo

## How to Use

1. Open `index.html` in your browser
2. Click the text boxes above each button to customize the choices
3. Drop your own image into the project folder and update the src in the HTML
4. Edit the bottom banner label to describe who is sweating the decision

## Swapping in Your Image

In `index.html`, find the img tag inside `.image-placeholder` and replace `sweatyGuy.png` with your own image filename. Make sure the image is in the same folder as `index.html`.

<!-- <img src="sweatyGuy.png" alt="sweaty guy" /> -->

## Built With

- HTML
- CSS
- JavaScript

## Concepts Covered

- CSS Flexbox for layout
- `box-shadow` for 3D button effect
- `:hover` and `:active` pseudo-classes
- `object-fit: cover` for image sizing
- DOM manipulation with JavaScript
- `Math.random()` for random responses
