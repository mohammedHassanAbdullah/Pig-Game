# Pig-Game
🎲 Dice Game 🏆
This JavaScript project is a simple dice-based game where two players take turns rolling a dice. The goal is to reach a score of 100 first. The game includes the following features:
1) Rolling the Dice 🎲: Generates a random number (1-6) and adds it to the active player's score unless they roll a 1, which forces them to switch turns.
2) Holding the Score : Players can choose to "hold" their current score, adding it to their total and passing the turn to the other player.
3) Winning the Game🎉🎉: The first player to reach 100 points wins.
4) New Game: Resets the game state to start over.

🛠️ Main Functions:
1) init(): Initializes or resets the game.
2) SwitchPlayer(): Switches the active player when needed.
3) Event listeners for rolling the dice, holding the score, and starting a new game.

The UI updates dynamically based on player actions, and game logic ensures a fair turn-based experience.
