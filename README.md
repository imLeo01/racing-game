# 🏁 Python Racing Game

A simple 2D top-down **racing game** built using **Pygame**. The player races against a computer-controlled car on a predefined track. The game includes levels, collisions, lap timing, and basic AI behavior.

---

## 🎮 Features

- Player-controlled car using keyboard inputs
- AI-controlled car that follows a set racing path
- Lap timer and speed display
- Level progression (up to 10 levels)
- Win/lose conditions
- Realistic turning and velocity logic
- Collision detection with track borders and finish line
- Visual effects with rotating cars and masked collisions

---

## 🛠️ Requirements

- Python 3.7+
- [Pygame](https://www.pygame.org/) (`pip install pygame`)

---

## 📦 Installation

1. Clone or download this repository:
    ```bash
    git clone https://github.com/your-username/pygame-racing-game.git
    cd pygame-racing-game
    ```

2. Install dependencies:
    ```bash
    pip install pygame
    ```

3. Run the game:
    ```bash
    python main.py
    ```

---

## 🎮 Controls

| Key | Action           |
|-----|------------------|
| W   | Accelerate       |
| S   | Brake/Reverse    |
| A   | Turn Left        |
| D   | Turn Right       |

---

## 🗂️ Project Structure

```plaintext
pygame-racing-game/
├── imgs/
│   ├── grass.jpg
│   ├── track.png
│   ├── track-border.png
│   ├── finish.png
│   ├── red-car.png
│   └── green-car.png
├── main.py
├── utils.py
└── README.md
