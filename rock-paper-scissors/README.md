Rock Paper Scissors Game

A simple and interactive Rock Paper Scissors game built using HTML, CSS, and JavaScript. Play against the computer and track your wins, losses, and ties in real time!

Features:
Play Rock, Paper, or Scissors against a computer opponent
Random computer move generation
Live score tracking (Wins, Losses, Ties)
Score saved using localStorage (persists after page reload)
Reset score functionality
Clean and responsive UI with custom styling

Demo

Simply open the 10-rock-paper-scissors.html file in your browser to start playing.

Technologies Used
HTML5 – Structure of the game
CSS3 – Styling and layout
JavaScript – Game logic and interactivity

How to Play
Click on Rock, Paper, or Scissors.

The computer randomly selects its move.
The result is displayed instantly:
You Win
You Lose
Tie

Your score updates automatically and is saved locally.
Click Reset Score to start over.

Game Logic
Rock beats Scissors
Scissors beats Paper
Paper beats Rock

The computer’s move is generated using:
Math.random()

Local Storage
The game uses localStorage to store your score:
localStorage.setItem('score', JSON.stringify(score));

This allows your progress to persist even after refreshing the page.

Reset Functionality
Clicking the reset button:

Clears the score
Updates the UI
Removes stored data from localStorage

Screenshots
<img width="1452" height="809" alt="image" src="https://github.com/user-attachments/assets/8a46a272-bbe8-427d-9b0b-073beca317d1" />
