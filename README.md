# Tic-Tac-Toe App

This is a simple Tic-Tac-Toe game built using Flutter. The app allows two players to input their names, start a game, and play against each other. It also features game reset and restart functionality.

## Features

- **Player Name Input**: Players can enter their names before starting the game.
- **Tic-Tac-Toe Gameplay**: Standard 3x3 grid Tic-Tac-Toe game.
- **Game Reset**: Players can reset the game to the initial state without changing player names.
- **Game Restart**: Players can restart the game, which takes them back to the player name input screen.

## Getting Started

### Prerequisites

- [Flutter](https://flutter.dev/docs/get-started/install) must be installed on your machine.

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/tic-tac-toe-app.git
    cd tic-tac-toe-app
    ```

2. Install the dependencies:
    ```sh
    flutter pub get
    ```

3. Run the app:
    ```sh
    flutter run
    ```

## Description

### HomeScreen

The `HomeScreen` allows players to input their names and start the game. It contains a form with two text fields for entering the names of Player 1 and Player 2. When both names are entered and validated, the game starts, and the players are navigated to the `GameScreen`.

### GameScreen

The `GameScreen` contains the main gameplay logic. It initializes a 3x3 grid and handles player moves, checking for winners and handling draw situations. The current player's turn is displayed, and the board updates with each move. 

- **Game Logic**: The game checks for a win or draw after each move and displays a dialog with the game result.
- **Reset Game**: Resets the game board to an empty state, keeping the player names intact.
- **Restart Game**: Navigates back to the `HomeScreen` for re-entering player names.

## Contributing

Contributions are welcome! Please fork this repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.