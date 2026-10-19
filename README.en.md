# Memory Game - Python

Project carried out during *prépa* (CPGE) as part of a computer science course.
This is a full implementation of the famous Memory card game, playable directly in the terminal or a Python editor, developed using VSCode.

## Features

* **Full Game Engine:** Management of a 52-card deck, random shuffling, and layout on a 4x13 grid.
* **Dynamic Display:** Text-mode (ASCII) visual rendering of the board with real-time updates of card states (hidden, revealed, or removed).
* **Two Game Modes:**
* `Human`: Play manually by entering card coordinates (e.g., A1, F3).
* `Computer`: Simulation where the AI plays against itself, using memory management to optimize its moves.


* **Difficulty Levels:** Configurable computer intelligence settings.
* **Demonstration Scenario:** Included script showcasing a game walkthrough.

## Project Structure

The architecture is modular to separate business logic from the UI display:

* `memory_humain.py`: Entry point for an interactive game.
* `memory_ordi.py`: Entry point for the AI simulation.
* `afficher_tapis.py`: Console graphic rendering logic.
* `scenario.py`: Demonstration script showcasing core features (initialization, flipping, removal).
* `tapis.py`, `paires.py`, `ordinateur.py` (etc.): Data management and AI modules.

## How to Play?

### Prerequisites

* Python 3.x installed.

### Launch

To start a human game:

```bash
python memory_humain.py

```
