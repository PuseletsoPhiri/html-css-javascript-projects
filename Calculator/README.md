Calculator Web App
A simple and responsive calculator built using HTML, CSS, and JavaScript. This project demonstrates basic DOM manipulation, event handling, and local storage usage in a browser environment.

Features
Perform basic arithmetic operations:

Addition (+)

Subtraction (−)

Multiplication (×)

Division (÷)

Real-time display updates

Persistent calculation using localStorage

Clear/reset functionality

Simple and clean UI design

Technologies Used
HTML5
CSS3
JavaScript

Project Structure
calculator/
│── calculator.html        # Main HTML structure
│── calculator.css    # Styling
│── calculator.js     # Logic and functionality
│── README.md         # Project documentation

Screenshot
<img width="1510" height="905" alt="image" src="https://github.com/user-attachments/assets/6b046ad3-edab-4c8e-9f56-e70c209c600f" />

How It Works
User clicks buttons to build a calculation string
The string is stored in a variable (calculation)

When = is clicked:
The expression is evaluated using eval()
Result is displayed on screen
Data is saved in localStorage so it persists after refresh

Example
Input: 7 + 3 * 2
Output: 13
