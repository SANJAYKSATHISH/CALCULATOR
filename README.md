# CALCULATOR

HTML:
The HTML code creates a simple web-based calculator with a structured layout of buttons for digits, operations, and functions. 
Key Components

1.Metadata
   - `<!DOCTYPE html>`: Declares the HTML document type.
   - `<head>`: Contains meta tags for character encoding, compatibility, viewport settings, and a link to an external CSS stylesheet.

2.Calculator Layout
   - `<div class="container">`: Centers the calculator.
   - `<div class="calculator">`: Main container for calculator elements.
     - `<input type="text" id="inputBox" placeholder="0" />`: Displays calculations and results.
     - **Button Rows:**
       - Top: AC, DEL, %, /
       - Second: 7, 8, 9, *
       - Third: 4, 5, 6, -
       - Fourth: 1, 2, 3, +
       - Bottom: 00, 0, ., =

3.JavaScript
   - `<script src="script.js"></script>`: Links to an external JavaScript file for functionality.

In essence, the HTML provides the structure for a calculator, while CSS and JavaScript handle styling and functionality, respectively.

JAVA SCRIPT:

Functionality

1. Setup
   - `let input = document.getElementById('inputBox');`: Selects the input field.
   - `let buttons = document.querySelectorAll('button');`: Selects all buttons.

2. Button Click Handling
   - Converts button `NodeList` to an array and adds click event listeners to each button.

3. Actions
   `=`: Evaluates the expression and updates the input.
   AC`: Clears the input.
  `DEL`: Deletes the last character.
   Other Buttons: Appends their text to the input.

The code manages user interactions by updating the calculator display based on button clicks.

CSS:

The CSS styles a calculator with a modern look:

Global Styles: Resets margins and paddings; uses the `Poppins` font.
Body: Centers the calculator and applies a dark gradient background.
Calculator: Adds a border, padding, rounded corners, and shadow for a 3D effect.
Input Field: Styles the display area with a shadow, right-aligned text, and white color.
Buttons: Styles with rounded edges and shadows; `equalBtn` has an orange background, and `operator` buttons are green.

The design features a dark theme with contrasting button colors for clarity.
