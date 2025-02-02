# Tic-Tac-Toe

Tic-Tac-Toe is a Python-based implementation of the classic Tic-Tac-Toe game. This project includes a console-based frontend and allows different types of players.

## Features
- Play against another human or AI.
- Command-line interface (CLI) for easy interaction.
- Modular code structure for extensibility.

## Installation
To get started, clone the repository and install any necessary dependencies:

```sh
git clone https://github.com/yourusername/TIC-TAC-TOE.git
cd TIC-TAC-TOE-main
```

Ensure you have Python installed (preferably Python 3.10 or later). You can install dependencies using:

```sh
pip install -r requirements.txt
```

## How to Play
Run the following command to start the game in the console:

```sh
python -m frontends.console
```

## Project Structure
```
TIC-TAC-TOE-main/
│── frontends/
│   ├── console/
│   │   ├── __main__.py  # Entry point for CLI
│   │   ├── cli.py       # Command-line interactions
│   │   ├── players.py   # Player logic
│   │   ├── renderers.py # Game rendering logic
│── README.md           # Project documentation
│── requirements.txt    # Dependencies
```

## Contributing
Contributions are welcome! Feel free to fork the repo, make changes, and submit a pull request.

## License
This project is licensed under the MIT License.
