# CodAI - Chess Game with AI

A sophisticated chess game implementation featuring an intelligent AI opponent, built with Python and Pygame. This project demonstrates advanced chess algorithms including minimax with alpha-beta pruning, move validation, and game state evaluation.

![Chess Game](https://img.shields.io/badge/Chess-AI%20Game-blue)
![Python](https://img.shields.io/badge/Python-3.7+-green)
![Pygame](https://img.shields.io/badge/Pygame-2.0+-orange)

## 🎯 Features

- **Complete Chess Implementation**: Full chess rules with all piece movements and game logic
- **Intelligent AI Opponent**: Advanced AI using minimax algorithm with alpha-beta pruning
- **Multiple Game Modes**: 
  - AI vs Human
  - Human vs Human (2-player mode)
- **Professional UI**: Clean, intuitive interface built with Pygame
- **Move Validation**: Comprehensive legal move checking and validation
- **Game State Analysis**: Checkmate, stalemate, and check detection
- **Accuracy Evaluation**: Integration with Stockfish engine for move quality assessment
- **Visual Feedback**: Highlighted legal moves and game state indicators

## 🚀 Quick Start

### Prerequisites

- Python 3.7 or higher
- Pygame 2.0 or higher
- Chess library (`python-chess`)
- Stockfish chess engine (included in the project)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/pawarsrujal/chess.git
   cd chess-game-AI-project-master
   ```

2. **Create and activate virtual environment (recommended)**
   ```bash
   python -m venv venv
   
   # On Windows
   venv\Scripts\activate
   
   # On macOS/Linux
   source venv/bin/activate
   ```

3. **Install dependencies**
   ```bash
   pip install pygame python-chess
   ```

4. **Run the game**
   ```bash
   python playchess.py
   ```

## 🎮 How to Play

1. **Launch the game**: Run `playchess.py` to start
2. **Choose game mode**:
   - Click "AI" button to play against the computer
   - Click "2 player" button for human vs human
3. **Game Controls**:
   - Click on a piece to select it
   - Click on a valid destination square to move
   - Legal moves are highlighted automatically
   - Game state messages appear at the bottom

## 🧠 AI Implementation

### Core Algorithm
The AI uses a **minimax algorithm** with **alpha-beta pruning** for efficient move calculation:

- **Search Depth**: Configurable depth (default: 3 moves ahead)
- **Position Evaluation**: Sophisticated heuristic evaluation considering:
  - Material value
  - Piece positioning
  - King safety
  - Pawn structure
  - Mobility

### Key Features
- **Move Generation**: All legal moves for each piece type
- **Position Analysis**: Real-time board state evaluation
- **Performance Optimization**: Efficient move ordering and pruning





## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Author

**Srujal Pawar** - Developer and creator of CodAI Chess

---

**Happy Chess Playing! ♟️**

*May your moves be strategic and your AI be challenging!*
