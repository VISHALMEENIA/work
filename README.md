# Quiz App

A simple interactive quiz application built using HTML, CSS, and JavaScript. Users answer multiple-choice questions, earn points for correct answers, and complete the quiz before the timer runs out.

## Features

* Multiple-choice quiz questions
* 30-second countdown timer
* Automatic score calculation
* Displays final score after the quiz ends
* Restart button to play the quiz again
* Responsive and clean user interface

## Technologies Used

* HTML
* CSS
* JavaScript

## Project Structure

```text
quiz-app/
│
├── index.html
├── style.css
├── script.js
└── README.md
```

## How It Works

1. The quiz starts automatically when the page loads.
2. A question and four answer options are displayed.
3. Select an answer to move to the next question.
4. Each correct answer increases the score by one.
5. The quiz ends when all questions are answered or when the 30-second timer reaches zero.
6. The final score is displayed.
7. Click **Restart Quiz** to start again.

## How to Run the Project

1. Download or clone this project.
2. Open the project folder.
3. Open `index.html` in any web browser.

No additional installation is required.

## Customizing Questions

Quiz questions are stored in the `quizData` array inside `script.js`.

Example:

```javascript
{
  question: "What is the capital of France?",
  options: ["Berlin", "Madrid", "Paris", "Lisbon"],
  answer: "Paris"
}
```

To add more questions, add another object in the same format to the `quizData` array.

## Future Improvements

* Add a progress bar
* Show correct and incorrect answers
* Add different quiz categories
* Add difficulty levels
* Save high scores using local storage
* Add sound effects and animations

## Author

Created as a beginner-friendly JavaScript quiz project.
