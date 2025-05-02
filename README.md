# 🎯 Vue.js 3 Trivia Game

A simple, interactive trivia quiz built with Vue.js 3 that fetches real-time questions from the [Open Trivia Database API](https://opentdb.com/). It tracks your score and lets you challenge yourself against computer-generated questions.

## 🚀 Features

- Pulls trivia questions dynamically from Trivia DB API (category: "Science: Computers").
- Randomized answer order for each question.
- Tracks player wins and losses.
- Real-time feedback on submitted answers.
- Clean and responsive UI built with Vue and SCSS.

## 🖥️ Preview

![image](https://github.com/user-attachments/assets/87ffb7a2-6bb7-4f44-89e2-68f256b259b6)

## 📦 Technologies

- Vue.js 3
- Axios
- SCSS
- Trivia DB API

## 🧠 How It Works

1. On app load, one trivia question is fetched from the API.
2. Answers are randomized before display.
3. The user selects an answer and submits it.
4. Feedback is shown immediately, along with a "Next question" button.
5. The app keeps track of correct (win) and incorrect (lose) responses.

## 📥 Installation

```bash
# Clone the repo
git clone https://github.com/yourusername/vue-trivia-game.git
cd vue-trivia-game

# Install dependencies
npm install

# Run development server
npm run dev
```
> Make sure you have Node.js and npm installed.

## 🔗 Trivia API

This app uses:

https://opentdb.com/api.php?amount=1&category=18

This pulls one computer science trivia question per request.

## 🔜 Future improvements

- Add combobox to choose the category of the questions.
- Store session score in localStorage.
- Add button to reset the score and start a new game.
- Add difficulty selection.
- Add timer and score multipliers.
- Improve accessibility and mobile responsiveness.
