# Lotto Number Picker

![Lotto Number Picker](random-number-picker.png)

The "Lotto Number Picker" is a web application that allows you to generate sets of 6 random numbers between 1 and 59. Each time you click the "Pick 6 Random Numbers" button, a new set of unique numbers is generated and displayed on the page. The application also stores all the generated sets in the local storage, allowing you to review the history of picked numbers.

## Table of Contents

- [Features](#features)
- [Usage](#usage)
- [How it Works](#how-it-works)
- [Clear Local Storage](#clear-local-storage)
- [Technologies Used](#technologies-used)
- [License](#license)

## Features

- Generate 6 random numbers between 1 and 59.
- Ensure that each set of numbers contains unique values.
- Display each set of numbers after clicking the "Pick 6 Random Numbers" button.
- Store all the generated sets in the local storage for future reference.
- Clear the stored history of numbers using the "Clear Local Storage" button.

## Usage

1. Clone this repository to your local machine or download the ZIP file.
2. Open the `index.html` file in your web browser.
3. Click the "Pick 6 Random Numbers" button to generate a new set of numbers.
4. The generated set of numbers will be displayed below the button.
5. Continue clicking the button to generate and display additional sets of numbers.
6. To clear the stored history of numbers, click the "Clear Local Storage" button.

## How it Works

The "Lotto Number Picker" web application is built with HTML, CSS, and JavaScript. The JavaScript code utilizes the `Math.random()` method to generate random numbers within the specified range (1 to 59). It ensures that each set of numbers contains unique values by using a loop to pick random numbers and check if they are already in the set. The application stores all the generated sets in the local storage using the `localStorage.setItem()` method.

## Clear Local Storage

If you wish to clear the stored history of generated numbers, simply click the "Clear Local Storage" button. This will remove all the sets of numbers from the local storage, and the list of generated numbers on the page will be reset.

## Technologies Used

- HTML
- CSS
- JavaScript

## License

The "Lotto Number Picker" web application is open-source software licensed under the [MIT License](LICENSE).


