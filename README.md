# Pig Game
Pig Game is a simple web application that simulates a dice game where two players compete to reach a target score.  
An exercise in DOM manipulation and event handling.

<img src="https://i.imgur.com/0Tr91uG.png?raw=true" alt="CODAM" style="max-width: 50%;">

### Getting Started
- Clone the repository and open the index.html file in your preferred web browser.  
  `git clone https://github.com/your-username/pig-game.git`
- Roll the dice to accumulate points while avoiding rolling a 1.
- Click "Hold" to add your current points to your total score and switch to the next player.
- The first player to reach the target score(100 points) wins the game.

### Features
- Dice Rolling: Roll a six-sided die to earn points, with a risk of losing your turn if a 1 is rolled.
- Score Tracking: Keep track of each player's total score and current round score.
- Player Switching: Automatically switch to the next player's turn after rolling a 1 or clicking "Hold".
- Win Detection: Declare the winner when a player reaches the target score.

### Key Concepts
- **Event Handling:**  
  Utilizing event listeners to detect clicks on buttons and trigger corresponding actions such as rolling the dice or holding the current score.
- **Conditional Statements:**  
  Implementing conditional logic to determine game outcomes, such as switching players or declaring a winner based on dice rolls and scores.
- **DOM Manipulation:**  
  Dynamically updating HTML elements to display game state changes, including scores, dice images, and player turns.

### Technologies Used
- HTML
- CSS
- JavaScript

### Sources
- [The complete javascript course 2024](https://www.udemy.com/course/the-complete-javascript-course/?couponCode=ST12MT030524)
- [MDN introduction to DOM](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction)

### Acknowledgements
This project was created as a part of Jonas Schmedtmann's JavaScript course on Udemy and a learning exercise to practice fundamental JavaScript concepts such as event handling, DOM manipulation, and conditional statements.*

**HTML and CSS files were provided as part of the course curriculum, with the JavaScript implementation being my primary focus.*
