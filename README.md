# Calculator Project

## Introduction

<p>This is a simple calculator project built using <strong>HTML</strong>, <strong>CSS</strong>, and <strong>JavaScript</strong>. It provides basic calculator functionalities such as addition, subtraction, multiplication, and division.</p>

## Project View Link

<p>Check out the live demo of the Calculator App <a href="https://thebishalprasad.github.io/Calculator/" target="_blank">here</a>.</p>

## Getting Started

<p>To use the calculator, simply open the <code>index.html</code> file in a web browser. The calculator interface will be displayed, allowing you to perform calculations.</p>

## Features

<ul>
  <li><strong>Addition:</strong> Click the <code>+</code> button or use the <code>+</code> key to add numbers.</li>
  <li><strong>Subtraction:</strong> Click the <code>-</code> button or use the <code>-</code> key to subtract numbers.</li>
  <li><strong>Multiplication:</strong> Click the <code>*</code> button or use the <code>*</code> key to multiply numbers.</li>
  <li><strong>Division:</strong> Click the <code>/</code> button or use the <code>/</code> key to divide numbers.</li>
  <li><strong>Decimal Point:</strong> Click the <code>.</code> button or use the <code>.</code> key to add a decimal point to a number.</li>
  <li><strong>Delete:</strong> Click the <code>DEL</code> button to delete the last entered digit.</li>
  <li><strong>All Clear:</strong> Click the <code>AC</code> button to clear the calculator's display and reset the calculations.</li>
  <li><strong>Equals:</strong> Click the <code>=</code> button or use the <code>Enter</code> key to calculate the result.</li>
</ul>

## Code Structure

<p>The project consists of the following files:</p>

<ul>
  <li><code>index.html</code>: The HTML structure of the calculator interface.</li>
  <li><code>styles.css</code>: The CSS file that styles the calculator interface.</li>
  <li><code>script.js</code>: The JavaScript file that contains the calculator logic.</li>
</ul>

<p>The JavaScript code defines a <code>Calculator</code> class with various methods to handle different calculator operations, such as clearing the display, deleting digits, appending numbers, choosing operations, computing the result, and updating the display.</p>

<p>The <code>updateDisplay</code> method is responsible for updating the calculator's display with the current and previous operands.</p>

## Special Functions Used

<p>The project utilizes several JavaScript functions and concepts, including:</p>

<ul>
  <li><code>querySelectorAll</code>: This function is used to select multiple elements from the DOM using CSS selectors.</li>
  <li><strong>Event Listeners</strong>: The <code>addEventListener</code> function is used to attach event listeners to the calculator buttons, enabling them to respond to user clicks.</li>
  <li><strong>String Manipulation</strong>: The code uses various string manipulation methods, such as <code>slice</code>, <code>toString</code>, <code>split</code>, and <code>innerText</code>, to manipulate and display numbers.</li>
  <li><strong>Parsing</strong>: The <code>parseFloat</code> function is used to parse the operands as floating-point numbers for accurate calculations.</li>
  <li><strong>Switch Statement</strong>: The <code>switch</code> statement is used to perform different computations based on the chosen operation.</li>
  <li><strong>Object Initialization</strong>: The <code>Calculator</code> class constructor is used to initialize the calculator's previous and current operands, as well as the operation.</li>
</ul>

## Conclusion

<p>This calculator project provides a simple implementation of a calculator interface using HTML, CSS, and JavaScript. It can be further enhanced and customized to add more functionality or improve the user experience. Feel free to modify and adapt the code to suit your specific requirements.</p>
