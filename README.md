-----------------
Simple Calculator
------------------

Overview
--------
This project is a simple web-based calculator created using HTML, CSS, and JavaScript. 
It demonstrates how to build a basic calculator interface and functionality, 
which allows users to perform arithmetic operations such as addition, subtraction, multiplication, and division.

Table of Contents
-----------------
* Features
* Technologies Used
* Code Structure
* Key Concepts
* How to Use


Features
---------

* Basic Arithmetic Operations: Perform addition, subtraction, multiplication, and division.

* Responsive Design: The calculator is designed to be centered and properly aligned on any screen size.

* Interactive Buttons: Buttons change color when hovered over or pressed, providing a better user experience.

Technologies Used
------------------
* HTML: Used for structuring the content of the calculator.

* CSS: Used for styling the calculator, making it visually appealing and responsive.

* JavaScript: Used for handling the calculator’s logic, such as input processing, calculations, and clearing the display.

Code Structure
---------------
* HTML (index.html)
The HTML file defines the structure of the calculator. It contains:
A div element with the ID calculator, which holds the entire calculator interface.
An input element with the ID display, which serves as the screen of the calculator, showing the current input and results.
A series of button elements representing the calculator keys, each triggering different JavaScript functions when clicked.

* JavaScript (index.js)
The JavaScript file provides the logic for the calculator:

- appendToDisplay(input): Appends the clicked number or operator to the display.

- clearDisplay(): Clears the display, resetting it to an empty state.

- calculate(): Evaluates the expression shown in the display and updates the display with the result. If there’s an error (e.g., due to an invalid expression), it shows an error message.

* CSS (style.css)
The CSS file handles the styling of the calculator:
The calculator is centrally aligned on the page using Flexbox.
The display area is styled with a large font size to show numbers clearly.
Buttons are styled to be circular, with distinct styles for operator buttons.
Hover and active states are defined for buttons to enhance the user experience.

Key Concepts
------------

1. HTML Elements

* div: A container element used to group together the calculator’s parts.

* input: Used for the display screen of the calculator, where readonly ensures that users cannot type directly into it.

* button: Represents each button on the calculator, such as numbers, operators, and the equals sign.

2. CSS Layout with Flexbox
Flexbox is used to center the calculator in the viewport, ensuring it remains centered regardless of screen size.

3. JavaScript DOM Manipulation

* document.getElementById: Used to reference and manipulate HTML elements in the JavaScript code.

* Event Listeners: The onclick attribute in HTML is used to trigger JavaScript functions when buttons are pressed.

4. JavaScript Functions
* eval(): This function evaluates a string expression and executes it as code. It’s used here to compute the arithmetic expressions entered by the user.

How to Use
----------
Clone or download the project files.
Open the index.html file in any web browser.
Use the buttons to enter numbers and operators. Press = to see the result, or C to clear the display.
