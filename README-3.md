# Raccoon Raid

A Python-based keyboard and graphical interface game where you control a clever raccoon navigating challenges to collect food and avoid danger. Utilizes advanced data structures (linked lists, binary trees) and recursive algorithms for efficient game entity management and clean code design.

---

## Table of Contents

- [Project Overview](#project-overview)  
- [Features](#features)  
- [Prerequisites](#prerequisites)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Code Structure](#code-structure)  
- [Data Structures & Algorithms](#data-structures--algorithms)  
- [Testing](#testing)  
- [Contributing](#contributing)  
- [License](#license)  

---

## Project Overview

Raccoon Raid is an interactive game where you guide a raccoon through levels filled with obstacles, food, and hazards. Built with Python, the game features a graphical interface and responsive keyboard controls to deliver an engaging play experience.

---

## Features

- **Graphical Interface**: Real-time rendering of sprites (raccoon, bins, background).  
- **Keyboard Controls**: Smooth movement with arrow keys or WASD.  
- **Dynamic Entity Management**:  
  - **Linked Lists** to track active game objects (food, bins).  
  - **Binary Trees** for spatial partitioning and quick collision checks.  
- **Recursive Mechanics**: Game logic and tree operations use recursion (max depth 3) for clarity and efficiency.  
- **Multiple Levels**: Progressively challenging stages with unique layouts.

---

## Prerequisites

- Python 3.8+  
- `pygame` library  

---

## Installation

1. **Clone the repository**  
   ```bash
   git clone https://github.com/your-username/raccoon-raid.git
   cd raccoon-raid
   ```

2. **Install dependencies**  
   ```bash
   pip install pygame
   ```

---

## Usage

Launch the game with:

```bash
python a1_game.py
```

- **Move**: Arrow keys or `W`, `A`, `S`, `D`  
- **Objective**: Collect all food items and reach the exit without being caught in the bin.  
- **Quit**: Press `Esc` or close the window.

---

## Code Structure

```
├── a1.py            # Core classes and game logic
├── a1_game.py       # Main entry point and event loop
├── a1_sample_test.py# Unit tests for core functionality
├── assets/          # Image and sprite assets
│   ├── background.png
│   ├── raccoon.png
│   ├── closed_food.png
│   ├── raccoon_in_bin.png
│   └── smart.png
└── README.md        # This file
```

---

## Data Structures & Algorithms

- **Linked List**  
  - Manages dynamic lists of food items and bins, allowing constant-time insertion/removal.  
- **Binary Tree**  
  - Spatial partitioning for efficient collision detection and entity queries.  
- **Recursion**  
  - Tree traversals and game-state updates implemented recursively (max depth 3) for elegant logic.

---

## Testing

Run unit tests with:

```bash
pytest a1_sample_test.py
```

Ensure all tests pass before playing.

---

## Contributing

Contributions and bug reports are welcome! Please fork the repository, create a new branch, and submit a pull request.  

---

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
