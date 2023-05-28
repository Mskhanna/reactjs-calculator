## Description
This app is a simple calculator that allows users to perform basic arithmetic operations. It provides a user interface with buttons for digits, operations, and functionalities like clear, delete, and evaluate. The calculator displays the previous and current operands along with the chosen operation.

## Functionalities

- **Adding a digit**: Users can input digits by clicking on the corresponding buttons. The digits are displayed as the current operand.

- **Choosing an operation**: Users can select an arithmetic operation (+, -, *, ÷) by clicking on the respective buttons. The chosen operation is displayed between the previous and current operands.

- **Clearing**: Clicking on the "AC" button clears the calculator's state, resetting all operands and the chosen operation.

- **Deleting a digit**: Clicking on the "DEL" button removes the last digit from the current operand.

- **Evaluating**: Clicking on the "=" button performs the arithmetic operation on the previous and current operands, based on the chosen operation. The result is displayed as the current operand, and the previous operand, operation, and current operand are cleared for the next calculation.

## Technologies used

- **React**: The app is built using React, a JavaScript library for building user interfaces.

- **React Hooks**: The useReducer hook is used to manage the state of the calculator and handle user actions.

- **JavaScript**: The app's logic is written in JavaScript, including the reducer function that updates the state based on the dispatched actions.

- **CSS**: The app's styles are defined using CSS, with the styles defined in an external stylesheet (styles.css).

- **Intl.NumberFormat**: The Intl.NumberFormat object is used for formatting the operands to display them in a user-friendly format.

- **JSX**: The app's user interface is defined using JSX, which is a syntax extension for JavaScript that allows writing HTML-like code within JavaScript files.

View the app here: https://mskhanna.github.io/reactjs-calculator/
