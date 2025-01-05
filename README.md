# Maze Runner

Maze Runner is a console-based game implemented entirely in assembly language. The game challenges the player to navigate a maze, avoiding obstacles and finding the exit. It demonstrates efficient use of low-level programming concepts and offers an engaging experience.

## Features
- **Menu Page**: Choose between "Play" and "Credits" options.
- **Interactive Gameplay**: Navigate through the maze using the `W`, `A`, `S`, and `D` keys.
- **Superman Mode**: Activate by pressing `M` to increase the timer. Collecting a key saves your life.
- **Random Maze Generation**: Each playthrough offers a unique challenge with dynamically generated mazes.
- **Timer**: Adds an element of urgency to reach the exit before time runs out.
- **Visually Appealing**: Simple yet attractive graphics designed within the constraints of assembly programming.

## Getting Started

### Prerequisites
- An assembler like [NASM](https://www.nasm.us/) 
- An x86 emulator (e.g., [DOSBox](https://www.dosbox.com/)) or a compatible environment for running assembly programs.

### Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/aayesh/maze-runner.git
2. Assemble program
   nasm -f bin maze_runner.asm -o maze_runner.com
3. Run the program using an emulator or directly if your system supports it
   dosbox maze_runner.com
