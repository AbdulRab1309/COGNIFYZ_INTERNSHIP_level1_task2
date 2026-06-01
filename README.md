#COGNIFYZ_INTERNSHIP_LEVEL1_TASK2

# JavaScript Logic Analysis - Level 2 Task

## Project Overview

This project demonstrates basic JavaScript functionality through three interactive tasks:

1. Color Changer
2. Time-Based Greeting
3. Addition Calculator

The application is built using HTML, CSS, and JavaScript and showcases DOM manipulation, event handling, user input validation, and dynamic styling.

---

## Features

### 1. Color Changer

* Generates a random hexadecimal color.
* Changes the background color of a specific container when the button is clicked.
* Demonstrates JavaScript event handling and DOM manipulation.

### 2. Time-Based Greeting

* Detects the user's current system time.
* Displays an appropriate greeting message based on the time of day.
* Uses JavaScript's Date object and conditional statements.

### 3. Addition Calculator

* Accepts two numeric inputs from the user.
* Validates user input.
* Calculates and displays the sum.
* Shows an error message if invalid values are entered.

---

## Technologies Used

* HTML5
* CSS3
* JavaScript (ES6)

---

## Project Structure

```text
Project Folder
│
├── index.html
└── README.md
```

---

## How to Run

1. Download or clone the project files.
2. Open `index.html` in any modern web browser.
3. Interact with the available features:

   * Change container colors.
   * Get time-based greetings.
   * Perform addition calculations.

No additional software or dependencies are required.

---

## JavaScript Concepts Implemented

### DOM Manipulation

Accessing and modifying HTML elements using JavaScript.

### Event Handling

Responding to user actions such as button clicks.

### Random Color Generation

```javascript
const randomColor = '#' + Math.floor(Math.random() * 16777215)
.toString(16)
.padStart(6, '0');
```

### Date and Time Operations

```javascript
const currentHour = new Date().getHours();
```

### Input Validation

```javascript
if (isNaN(num1) || isNaN(num2)) {
    // Handle invalid input
}
```

---

## Expected Output

* Dynamic background color changes for the Color Changer section.
* Personalized greeting messages based on the current system time.
* Correct addition results with proper validation.

---

## Learning Outcomes

By completing this project, you will gain experience with:

* HTML structure and forms
* CSS styling and animations
* JavaScript fundamentals
* Event listeners
* Conditional statements
* User input validation
* Dynamic content updates

---

## Author

**Abdul Rab**
Web Development Intern

---

## License

This project is created for educational and internship learning purposes.
