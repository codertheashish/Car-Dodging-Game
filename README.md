# 🚗 Car Dodging Game

A fast and addictive **Car Dodging Game** built using **Python Pygame**.
Control your car, dodge enemy cars, score points, and survive as long as possible!
Difficulty increases automatically as obstacle speed rises with score.

This project includes:

🎮 Smooth Left–Right Controls
🚗 3 Random Enemy Cars
⚡ Auto Speed Increase Every 5 Points
🏆 Score System
💥 Collision Detection + Game Over Screen
⛔ ESC to Quit Anytime
🔄 Press R to Restart

---

## 🚀 Game Features

### 🚗 Player Car Movement

* Smooth left/right arrow control
* Car positioned at bottom for visibility

### 🚘 Enemy Cars (Obstacles)

* 3 cars spawn randomly
* Fall from top to bottom
* Respawn off-screen with new random X position

### ⚡ Dynamic Difficulty

* Score increases when obstacle passes
* Each **5 points = enemy speed increases**

### 💥 Collision System

* Collision with enemy car → **GAME OVER**
* Game Over Screen:

  * Shows score
  * Press **R** to Restart
  * Press **ESC** to Exit

---

## 🎮 Controls

| Key           | Action       |
| ------------- | ------------ |
| ⬅ Left Arrow  | Move Left    |
| ➡ Right Arrow | Move Right   |
| R             | Restart Game |
| ESC           | Quit Game    |

---

## 🛠 Tech Stack

**Python 3.x**
**Pygame**
**Random Module**

---

## 📦 Installation

### **1️⃣Install Python (if not installed)**

### **2️⃣ Install Pygame**

```bash
pip install pygame
```

### **3️⃣ Clone the project**

```bash
https://github.com/codertheashish/Car_dodging_game
```

### **4️⃣ Run the game**

```bash
python car_dodging.py
```

---

## ▶ How It Works (Game Logic)

* Player car moves left/right
* Enemy cars fall downward
* When enemy goes off-screen → respawn at random top position
* Score += 1 for each respawn
* Every 5 points → speed increases
* Collision triggers Game Over screen
* Press R to restart instantly

---

## 📁 Output

Game window includes:

* Blue background
* Yellow player car
* Red enemy cars
* Live score on top-left
* Smooth animation at 60 FPS

---

## 🌟 Future Improvements

* Add road lanes
* Add background sound effects
* Add high-score saving
* Add car skins & themes
* Add difficulty modes

---

## 👨‍💻 Author

**Ashish Kumar Prajapati**

---
