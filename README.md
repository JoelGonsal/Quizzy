# Quizzy

A simple and interactive multiple-choice quiz application built with HTML, CSS, and JavaScript. Questions are fetched randomly from the Open Trivia Database API.

## ✨ Features

* 🧠 Random multiple-choice questions
* 🎯 Four answer options
* ✅ Correct answer detection
* ❌ Incorrect answer feedback
* 📊 Live score tracking
* 🟢 Highlights the correct answer
* 🔴 Highlights an incorrect answer
* ⏭️ Automatically moves to the next question
* 🔄 50 questions fetched from the API
* 📱 Simple and interactive interface

## 🛠️ Technologies

* HTML5
* CSS3
* JavaScript
* Open Trivia Database API

## 🎮 How It Works

```text
Start Quiz
    ↓
Fetch Questions
    ↓
Display Question
    ↓
Select Answer
    ↓
Correct / Incorrect
    ↓
Update Score
    ↓
Next Question
```

The application fetches 50 multiple-choice questions from the Open Trivia Database and displays them one at a time.

## 📁 Project Structure

```text
Quizzy/
│
├── index.html
├── style.css
├── app.js
└── README.md
```

## 🚀 Run Locally

Clone the repository:

```bash
git clone <repository-url>
cd Quizzy
```

Open `index.html` in your browser.

No installation or backend server is required.

## 🌐 API

This project uses the Open Trivia Database API to retrieve quiz questions:

```text
https://opentdb.com/api.php?amount=50&type=multiple
```

The API provides multiple-choice questions along with the correct and incorrect answers.

## 🏆 Scoring

* A correct answer increases the score by 1.
* An incorrect answer does not increase the score.
* The correct answer is highlighted after an incorrect selection.
* The next question appears automatically after a short delay.

## 📸 Screenshots


