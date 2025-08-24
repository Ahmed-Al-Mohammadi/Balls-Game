# Balls Game

## Description

This project is a simple yet engaging console-based game developed in Python using `pygame` and `mediapipe`. It features real-time hand detection via webcam input, allowing players to interact with falling balls by making a "punch" gesture. The objective is to hit as many falling balls as possible to increase the score.

## Features

-   **Real-time Hand Detection**: Utilizes `mediapipe` to detect hand landmarks from webcam feed.
-   **Interactive Gameplay**: Players use a "punch" gesture to hit falling balls.
-   **Score Tracking**: Keeps track of the player's score.
-   **Dynamic Ball Generation**: Balls appear randomly from the top of the screen.
-   **Console-Based Interface**: All interactions and displays are handled within the console.

## Project Structure

```
Balls-Game/
├── ball_game.ipynb                 # Jupyter Notebook containing the game's source code.
└── README.md                       # This README file.
```

## Getting Started

### Prerequisites

To run this game, you will need Python installed along with the following libraries:

-   `pygame`
-   `mediapipe`
-   `opencv-python`
-   `numpy`

You can install these using pip:

```bash
pip install pygame mediapipe opencv-python numpy
```

### Installation

1.  **Clone the repository**:
    ```bash
    git clone https://github.com/Ahmed-Al-Mohammadi/Balls-Game.git
    cd Balls-Game
    ```

### Running the Game

1.  **Open the Jupyter Notebook**: Launch Jupyter Notebook and open `ball_game.ipynb`.
2.  **Run all cells**: Execute all cells in the notebook to start the game. Ensure your webcam is connected and accessible.

## How to Play

-   The game will open a window displaying your webcam feed.
-   Balls will start falling from the top of the screen.
-   Use your hand to make a "punch" gesture (index finger extended below the wrist) to hit the falling balls.
-   Each hit ball increases your score.
-   The game continues indefinitely, challenging you to achieve the highest score.

## Contributing

Contributions are welcome! If you have suggestions for improvements or new features, please:

1.  Fork the repository.
2.  Create a new branch (`git checkout -b feature/YourFeature`).
3.  Make your changes.
4.  Commit your changes (`git commit -m 'Add some feature'`).
5.  Push to the branch (`git push origin feature/YourFeature`).
6.  Open a Pull Request.

## License

This project is licensed under the MIT License - see the `LICENSE` file in the repository for details.

## Contact

For any questions or suggestions, please open an issue in the GitHub repository
