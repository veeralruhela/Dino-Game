# 🦖 Dino Game (Pygame)

A simple **Chrome Dino style endless runner game** built using **Python and Pygame**.

In this game, the player controls a dinosaur that must jump over incoming cactus obstacles. The background scrolls continuously, creating the illusion of movement. The longer you survive, the higher your score.

This project demonstrates how to build a small 2D game using **object-oriented programming in Python** with **Pygame**.

---

# 🎮 Gameplay

The dinosaur automatically runs forward while obstacles appear from the right side of the screen.

The player must **jump at the correct time** to avoid collisions with the cactus. If the dinosaur collides with an obstacle, the game ends.

Your score increases the longer you survive.

---

# ✨ Features

* Endless runner gameplay
* Smooth background scrolling
* Animated dinosaur character
* Random cactus spawning
* Collision detection system
* Score and high score system
* Sound effects (jump, point, game over)
* Restart system
* Simple and clean game loop

---

# 🧱 Project Structure

```
project-folder
│
├── dino.py
│
└── assets
    │
    ├── images
    │   ├── bg.png
    │   ├── dino0.png
    │   ├── dino1.png
    │   ├── dino2.png
    │   └── cactus.png
    │
    └── sounds
        ├── jump.wav
        ├── point.wav
        └── die.wav
```

---

# ⚙️ Requirements

* Python 3.8+
* Pygame

Install pygame with:

```
pip install pygame
```

---

# ▶️ How to Run

Run the game using:

```
python dino.py
```

A game window will open and the gameplay will start once you press **SPACE**.

---

# 🎮 Controls

| Key          | Action    |
| ------------ | --------- |
| SPACE        | Jump      |
| R            | Restart   |
| Close Window | Exit Game |

---

# 🧠 How the Game Works

The game uses an **object-oriented architecture** where different parts of the game are separated into classes.

Main components include:

### Background System

Handles scrolling background images to simulate forward movement.

### Player System

Controls the dinosaur character including:

* jumping
* falling
* animation frames
* sound effects

### Obstacle System

Spawns cactus obstacles randomly and moves them toward the player.

### Collision System

Detects collisions between the dinosaur and obstacles.

### Score System

Tracks:

* current score
* high score
* sound triggers every 100 points

### Game Controller

Manages the overall game state including:

* starting the game
* ending the game
* restarting
* obstacle spawning

---

# 🔊 Sound Effects

The game includes three sound effects:

| Sound     | Description                                      |
| --------- | ------------------------------------------------ |
| jump.wav  | Played when the dinosaur jumps                   |
| point.wav | Played every 100 score                           |
| die.wav   | Played when the player collides with an obstacle |

---

# 📈 Score System

The score increases as the game loop progresses.

The high score is updated automatically whenever the current score surpasses the previous high score.

---

# 🧩 Classes Used

The project uses the following classes:

| Class     | Purpose                                |
| --------- | -------------------------------------- |
| BG        | Handles scrolling background           |
| Dino      | Controls player movement and animation |
| Cactus    | Obstacle object                        |
| Collision | Collision detection                    |
| Score     | Score and high score system            |
| Game      | Main game controller                   |

---

# 🎯 Learning Goals

This project is useful for learning:

* Python game development
* Pygame fundamentals
* Object-oriented programming
* Game loops
* Collision detection
* Sprite animation
* Sound effects

---

# 🚀 Possible Improvements

Future upgrades could include:

* flying enemies (birds)
* increasing game speed
* particle effects
* day/night cycle
* menu system
* fullscreen mode
* mobile support
* better physics

---

# 📜 License

MIT License

Copyright (c) 2026 Vikrant

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.


---

# ❤️ Credits

Created using **Python and Pygame**.

Inspired by the **Google Chrome Dino Game**.

# 😎 Developed by

Created by Veeral Ruhela

Thank You





