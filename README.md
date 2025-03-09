# Calculator Project

This is a simple yet modern calculator application built using HTML, CSS, and JavaScript. It includes all basic arithmetic functions (addition, subtraction, multiplication, and division), along with features like percentage calculation, clear (AC), and delete (DEL) buttons.

## Features

- **Basic Operations**: Addition, subtraction, multiplication, division, and percentage.
- **Delete & Clear**: You can delete the last entry or clear the entire input.
- **Responsive Design**: The layout adapts to various screen sizes (from desktops to mobile devices).
- **Stylish Interface**: Includes smooth animations, gradient background, and sleek button designs.

## Technologies Used

- **HTML5**: For the structure and layout of the calculator.
- **CSS3**: For styling, animations, and responsiveness.
- **JavaScript**: For handling user input, performing calculations, and updating the display.

## Installation

To run the calculator on your local machine, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/Yash990-bit/JS-Stopwatch
    ```

2. Navigate into the project folder:
    ```bash
    cd calculator-project
    ```

## How it Works

1. **HTML (index.html)**:
    - The calculator is structured with buttons for numbers, operators, and special functions (`AC`, `DEL`, `=`, and `%`).
    - An input field (`inputBox`) is used to display the current calculation or result.

2. **CSS (style.css)**:
    - The calculator has a modern design, using gradients, box shadows, and a responsive layout.
    - It includes animations such as smooth hovering effects for buttons.

3. **JavaScript (script.js)**:
    - **Button functionality**: Handles each button click and updates the input display accordingly.
    - **Arithmetic Operations**: Uses the `eval()` function to calculate the result when the `=` button is clicked.
    - **Error Handling**: If there's an invalid calculation, it displays `Error` in the input field.
    - **Clear/Delete**: The `AC` button clears the input, and the `DEL` button removes the last character.

### Key JavaScript Functions:

- **`eval()`**: Evaluates the string of mathematical operations entered by the user and returns the result.
- **Event Listeners**: Each button has an event listener to append its value to the input field or trigger a calculation.

## Demo

You can see a live demo of the calculator here: 
[(https://arthimetic.netlify.app/)]
