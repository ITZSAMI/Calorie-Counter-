# Interactive Calorie Counter (JavaScript)

A browser-based calorie tracking app built with HTML, CSS, and vanilla JavaScript.

This project allows users to set a daily calorie budget, add food and exercise entries dynamically, and calculate whether they are in a calorie surplus or deficit.

The entire application runs in the browser with no external libraries or frameworks.

## Live Demo

If deployed on GitHub Pages:

[View Live App](https://itzsami.github.io/Calorie-Counter-/)

## Overview

This project was built to practice DOM manipulation, dynamic form generation, and structured event handling in JavaScript.

Instead of hardcoding fixed input fields, entries are created dynamically based on user interaction. The logic handles calorie aggregation across multiple categories and updates the interface in real time after calculation.

The app separates concerns between:
- Input handling
- Validation
- Calculation logic
- UI updates

## Features

- Set a daily calorie budget
- Add unlimited entries for:
  - Breakfast
  - Lunch
  - Dinner
  - Snacks
  - Exercise
- Dynamic input generation
- Real-time calorie calculation
- Surplus or deficit detection
- Basic input validation (prevents invalid numeric formats)
- Reset functionality to clear all entries

## How It Works

1. The user sets a calorie budget.
2. Entries are added dynamically to selected categories.
3. On submission:
   - All numeric inputs are collected
   - Input is sanitized and validated
   - Calories are summed by category
4. Remaining calories are calculated:

   Remaining = Budget − Consumed + Exercise

5. The result is displayed as:
   - Calorie Deficit (green)
   - Calorie Surplus (red)


## Input Validation

The app includes:

- String sanitization to remove unwanted characters
- Detection of invalid scientific notation formats (e.g., 1e5)
- Error handling to prevent incorrect calculations


## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6)
- DOM manipulation
- Event listeners

No frameworks or external libraries were used.


## Possible Improvements

- Persist data using localStorage
- Add macro tracking (protein, carbs, fats)
- Add charts for visual progress
- Improve UI with animations
- Add mobile-specific layout refinements

## Why This Project?

This app focuses on interactive logic rather than visual complexity. It demonstrates the ability to:

- Generate dynamic UI elements
- Process and validate user input
- Structure JavaScript logic cleanly
- Manipulate the DOM efficiently

It’s a small but complete browser application built without frameworks.



