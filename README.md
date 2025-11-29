# Hunt the Ace ♠️

A classic "Three-card Monte" style memory game built for the web. The objective is simple: follow the Ace of Spades as the cards are shuffled and pick the correct card to win points.

## 🚀 Features

* **Interactive Gameplay:** Smooth card dealing and flipping animations using CSS transitions.
* **Dynamic Shuffling:** Randomized card shuffling logic visualized with CSS transforms.
* **Score Tracking:** Points are awarded based on the difficulty/round number.
* **Persistence:** Uses the browser's `localStorage` to save your current round and score, so you can refresh or return later without losing progress.
* **Responsive Design:** optimized for both desktop and mobile screens.

## 🛠️ Technologies Used

* **JavaScript (ES6+):** Handles game logic, DOM manipulation, and state management.
* **CSS3:** Uses CSS Grid for layout and Keyframes/Transitions for card animations (`fly-in`, `shuffle`).
* **HTML5:** Semantic structure for the game interface.

## 🎮 How to Play

1.  **Start:** Click the **Play Game** button.
2.  **Watch:** The cards will stack up and shuffle automatically on the screen.
3.  **Guess:** Click on the card you believe is the **Ace of Spades**.
4.  **Win:**
    * **Round 1:** 100 Points
    * **Round 2:** 50 Points
    * **Round 3:** 25 Points
    * **Round 4:** 10 Points
5.  **Game Over:** The game ends after 4 rounds.

## 📂 Project Structure

```bash
HuntTheAceJSGame/
│
├── index.html      # Main HTML structure
├── style.css       # Game styling and animations
├── index.js        # Game logic and event handling
└── images/         # Asset folder for card images (King, Jack, Queen, Ace)
