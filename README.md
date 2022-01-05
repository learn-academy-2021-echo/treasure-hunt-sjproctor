# React Treasure Hunt Game

### Remember:
- Pseudocode!!
- Ask clarifying questions

### User Stories
- As a user, I can see a page with a 3 by 3 grid board game with a question mark in each square.
  - Branch: gameboard
  - Added a div to the Square component
  - Added styling to get a border on the square
  - Mapped over the Square component
  - Passed the value from the array in state (aka the question mark)
  - Added a gameboard div around the mapped logic
  - Styled the gameboard and the question mark
- As a user, when I click on one of the question marks an alert appears with the index position of that question mark in the array.
  - Branch: index-position
  - Passed index from the map to Square
  - Set up handleClick and onClick for Square
  - Set up a handleGamePlay method in App.js that receives the index from Square using functional props
- As a user, when I click on one of the question marks instead of the alert the question mark turns into a tree emoji.
- As a user, if I select the winning square the question mark will become a treasure emoji.
- As a user, if I select the losing square the question mark will become a bomb emoji.
- As a user, I can see a counter that shows how many guesses I have left. The counter starts at 5 and decrements one every time I click on a square that is not the treasure nor the bomb.
- As a user, I can see a message informing me that I won the game if I select the square that contains the treasure.
- As a user, I can see a message informing me that I lost the game if I select the square that contains the bomb.
- As a user, I cannot continue to play the game after I win or lose.
- As a user, I can see a message informing me that I lost the game when I run out of turns (the counter reaches zero).
- As a user, I can click on a “Play Again” button that will restart the game.
