# Age Calculator

A simple JavaScript-based web application that calculates a person's age based on their birthdate. The user inputs their birthdate, and the calculator returns the age in years, months, and days.

## Description

The Age Calculator allows users to calculate their age from their birthdate. The application uses a date input field, and when the user selects their birthdate and clicks the "Calculate" button, the app computes their age in terms of years, months, and days. It works using JavaScript's `Date` object, ensuring that the age calculation accounts for leap years and varying days in months.

## Features

- **User Input**: Allows users to input their birthdate using a date picker.
- **Calculate Age**: Computes age in years, months, and days based on the input date.
- **Real-Time Calculation**: Automatically calculates and displays the age when the user clicks the "Calculate" button.
- **Validation**: Ensures the input date is not a future date by setting a max date limit for the input field.

## Technologies Used

- **HTML**: Provides the structure for the date input, button, and result display.
- **CSS**: Styles the Age Calculator with a modern and visually appealing design, including a gradient background and smooth UI elements.
- **JavaScript**: Handles the core functionality of the age calculation and the input validation.

## How It Works

1. **User Input**:
   - The user selects their birthdate from a date input field.

2. **Click on "Calculate"**:
   - When the "Calculate" button is clicked, the JavaScript function `calculateAge()` is triggered.

3. **Age Calculation**:
   - The function calculates the user's age by comparing the input date to the current date.
   - It calculates the years, months, and days between the two dates and accounts for months with different days and leap years.

4. **Display Result**:
   - The calculated age (in years, months, and days) is displayed below the input fields in the `#result` paragraph.

5. **Input Validation**:
   - The input date field ensures that the user cannot select a future date by setting the `max` attribute to the current date.
