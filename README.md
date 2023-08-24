# Dynamic Div Styling using Dropdowns

This project demonstrates how to dynamically manipulate the properties of a `<div>` element using JavaScript and DOM manipulation. The project includes a webpage with five dropdowns that allow users to change various styling properties of the `<div>` element such as color, background color, padding, font size, and font weight.

## Features

- Five dropdowns to control the following properties of the `<div>` element:
  - Color
  - Background Color
  - Padding
  - Font Size
  - Font Weight

- JavaScript functions to handle the selection changes in the dropdowns and apply the chosen styles to the `<div>` element.

## How it Works

1. **index.html**: This is the main HTML file that contains the structure of the webpage. It includes the `<div>` element that we will be styling, and it also loads the `styles.js` JavaScript file.

2. **index.js**: This JavaScript file contains the logic for manipulating the styling of the `<div>` element. It does the following:

   - Retrieves references to the dropdown elements and the `<div>` element using DOM methods like `getElementById`.

   - Adds event listeners to the dropdowns to listen for changes in their selections.

   - Defines functions that get triggered when dropdown selections change. These functions read the selected values and use them to update the styling properties of the `<div>` element.

3. **styles.css**: This CSS file contains initial styling for the `<div>` element and the dropdowns. It provides a starting point for the styles that will be manipulated dynamically.

