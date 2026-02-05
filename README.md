![C](https://img.shields.io/badge/Language-C-blue)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)
![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20Linux-lightgrey)


# 🐍 Classic Snake Game (Smooth Console Version) – C Programming

A cross-platform console-based Snake Game developed in C with smooth movement, level-based difficulty scaling, and real-time keyboard input handling.

This project demonstrates system-level programming concepts, terminal control, input handling, and game loop logic using C.

## Game Objective

Control the snake to eat food and grow longer while avoiding collisions with walls or itself. The game speed increases with levels, increasing difficulty.

---

## 🎮 Features

✅ Smooth snake movement  
✅ Real-time keyboard input (non-blocking controls)  
✅ Level-based speed increase  
✅ Pause and Resume functionality  
✅ Cross-platform compatibility (Windows & Linux)  
✅ Collision detection (walls & self)  
✅ Score tracking system  

---

## 🕹️ Controls

| Key | Action |
|------|------------|
| W / ↑ | Move Up |
| A / ← | Move Left |
| S / ↓ | Move Down |
| D / → | Move Right |
| P | Pause Game |
| Q | Quit Game |

---

## ⚙️ Technologies Used

- C Programming
- Standard Libraries (stdio.h, stdlib.h, time.h)
- Platform-Specific Libraries:
  - Windows → conio.h, windows.h
  - Linux → termios.h, unistd.h, fcntl.h

---

## 🧠 Concepts Demonstrated

- Game loop implementation
- Non-blocking keyboard input
- Terminal raw mode control
- Memory handling and structures
- Cross-platform preprocessor directives
- Collision detection algorithms
- Dynamic difficulty scaling

---

## 📸 Demo

Below is a sample gameplay screen:

![Snake Gameplay](screenshots/gameplay.jpg)


---
## Requirements

• GCC Compiler
• Terminal / Command Prompt
• Windows / Linux / MacOS


## 🚀 How to Run

### Windows

1. Install MinGW or any GCC compiler.
2. Open terminal in project folder.
3. Compile:
   gcc snake.c -o snake.exe
4. Run:
   snake.exe
----
## Project Structure

snake-game-c-console/
│
├── snake.c
├── screenshots/
│   └── gameplay.png
├── README.md
└── .gitignore

## 🔮 Future Improvements

- GUI version using SDL or OpenGL
- High score saving system
- Multiplayer mode
- Sound effects integration
- Mobile or web adaptation

---

## 📚 Learning Outcome

This project strengthened understanding of:

- Real-time system interaction
- Cross-platform compatibility design
- Game logic structuring
- Debugging low-level input handling

---

## 👩‍💻 Author

**Pratheeksha Shalbin**  
Food Technology Undergraduate | Exploring AI, Software Development & Digital Food Systems


🔗 LinkedIn: *https://www.linkedin.com/in/pratheeksha-shalbin/*

---

## 📜 License

This project is open-source and available under the MIT License.


