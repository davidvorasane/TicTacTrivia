
Tic Tac Trivia:



Project Proposal

Tic Tac Trivia is a browser-based game built with React that combines the classic strategy of Tic Tac Toe with the challenge of trivia questions. Players must correctly answer a trivia question before they are allowed to place their mark (X or O) on the board. The game encourages both critical thinking and knowledge recall while maintaining the simple, competitive nature of Tic Tac Toe.
This project is designed to demonstrate React component architecture, state management, and API integration while creating an interactive and engaging game experience.


Concept

Traditional Tic Tac Toe is simple and often solved quickly. Tic Tac Trivia adds an extra layer of difficulty by requiring players to answer a trivia question before making a move.


Basic Gameplay

Two players take turns.
When a player selects a square:
A trivia question appears.
If the player answers correctly:
Their symbol (X or O) is placed on the selected square.
If the player answers incorrectly:
The turn is skipped and the other player goes.
The first player to get three in a row wins.


Objectives

The primary goals of this project are:
Practice building a full React application.
Implement interactive game logic.
Work with component-based architecture.
Manage application state effectively.
Integrate an external trivia API.
Create a responsive and intuitive UI.


🎲 Tic Tac Toe Game Board

3x3 grid.
Tracks player turns.
Detects win or draw conditions.
❓ Trivia Question System.
Question appears when a square is selected.
Multiple-choice answers.
Correct answer allows move placement.
🔄 Turn-Based Gameplay.
Alternating player turns.
Incorrect answers skip a turn.
🏆 Win Detection.
Detects horizontal, vertical, and diagonal wins.
Displays winner or draw message.
🔁 Game Reset.
Restart the game anytime.
Reset board and score.


Planned Tech Stack

React – Frontend framework.
JavaScript (ES6+).
CSS / Styled Components (TBD).
Open Trivia DB API (for questions).


Component Structure

src/
│
├── components/
│   ├── Board.jsx
│   ├── Square.jsx
│   ├── TriviaModal.jsx
│   ├── QuestionCard.jsx
│   └── ScoreBoard.jsx
│
├── pages/
│   └── Game.jsx
│
├── utils/
│   └── triviaApi.js
│
├── App.jsx
└── main.jsx


Game Flow

Player selects an empty square.
Trivia question modal appears.
Player selects an answer.
If correct:
Square is filled with player's mark.
If incorrect:
Turn passes to the next player.
Game checks for win/draw.
Continue until game ends.


Learning Goals

This project will help reinforce:
React hooks (useState, useEffect).
Component communication via props.
Conditional rendering.
API fetching.
Game state logic.
UI/UX design in React.


Installation

git clone https://github.com/yourusername/tic-tac-trivia.git,
cd tic-tac-trivia,
npm install,
npm run dev,
