# Tower of Hanoi Game

This project implements the **Tower of Hanoi** puzzle in a graphical format using JavaScript, HTML, and CSS. The user can input the number of disks, and the game will visualize the process of solving the puzzle by moving disks between three pegs.

## Technologies Used

- **HTML5**: For structuring the webpage.
- **CSS**: For styling the pegs, disks, and game area.
- **JavaScript (ES6)**: For implementing the logic of the Tower of Hanoi algorithm, moving disks between pegs, and dynamically updating the DOM.

## How the Game Works

1. **Tower of Hanoi Algorithm**: 
   - The Tower of Hanoi is a mathematical puzzle where you have three pegs and `n` disks of different sizes. The goal is to move all disks from one peg to another, following these rules:
     - Only one disk can be moved at a time.
     - A disk can only be placed on top of a larger disk or an empty peg.

2. **Visual Representation**:
   - The disks and pegs are visually represented on the screen using div elements. The game simulates the movement of the disks based on user input.

3. **User Interaction**:
   - The user can enter the number of disks using an input field. The "Make Move" button starts the game, and the disks will move automatically between the pegs to solve the puzzle.

## Features

- **Dynamic Disk Initialization**: Disks are dynamically created based on the user input (number of disks).
- **Animated Disk Movement**: The game animates the movement of disks between pegs, updating the position of each disk in real-time.
- **Recursive Algorithm**: The puzzle is solved using a recursive algorithm that follows the rules of the Tower of Hanoi.

## How to Use

1. **Setup**:
   - Clone or download the repository.
   - Make sure the following files are in place:
     - `index.html`: The main HTML file.
     - `tower.js`: Contains the logic for moving disks and initializing the game.
     - `hanoi.js`: Contains the recursive Tower of Hanoi algorithm.
     - `styles.css`: Provides the styling for the game interface.

2. **Running the Game**:
   - Open the `index.html` file in any modern browser.
   - Enter the number of disks in the input field.
   - Click the "Make Move" button to start the game.
   - Watch as the disks move between the pegs to solve the puzzle.

## Example

Here’s an example of how the game looks:

```html
<input type="number" id="numDisk" placeholder="Enter the Number">
<button onclick="makeMove()" id ="makemove">Make Move</button>
<div class="game" id="game"></div>
