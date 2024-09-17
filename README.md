# 2048 game
This project is a JavaScript implementation of the classic 2048 game. The game logic includes core functionalities like initializing a 4x4 grid, handling user inputs (arrow keys) to move and merge cells, generating new cells, and tracking the score. Key features include:

- Gameplay: Players use arrow keys to move tiles, merging identical values. Randomly generates '2' or '4' tiles after each move.
- Game State: Tracks the current board state, score, win, and loss conditions.
- Win/Lose Detection: The game displays a win message upon reaching 2048 in any cell and a loss message when no more valid moves are possible.
- Restart Mechanism: A start/restart button initializes and resets the game, updating the UI dynamically.
The UI updates with each move, showing the new cell values, score, and game messages. This implementation efficiently handles keyboard events and DOM manipulation to provide an interactive gameplay experience.

- [DEMO](https://vladkorobka.github.io/2048_game/)
- [Reference](https://play2048.co/)

## Technologies Used
- **HTML**: Provides the structure of the game board, buttons, and messages. It defines the basic layout of the game grid and elements like the score display, win/loss messages, and the start/restart button.
- **SCSS**: Used for styling the game’s UI, giving it a visually appealing look. SCSS offers more flexibility than standard CSS, allowing the use of variables, nesting, and mixins to maintain a clean and manageable stylesheet. It controls the appearance of grid cells, colors, animations, and dynamic class changes based on the game’s state (e.g., changing styles as tiles merge).
- **JavaScript**: The core of the game logic, JavaScript manages all the dynamic behaviors.

## How to Run the Application Locally

### 1. Clone the Repository
- Click the green "Code" button on this repository's GitHub page and copy the provided URL to your clipboard.
- Open your terminal and navigate to your desired projects folder.
- Clone the repository by running the following command:
  ```git clone [PASTE_URL_HERE]```
### 2. Install Dependencies
- Open the project folder in your favorite text editor.
- Install all the packages by running:
  ```npm install```
- If you encounter any installation issues, try using the following command:
```npm install --legacy-peer-deps```
### 3. Start the Application
- To run the application locally, execute:
```npm start```
