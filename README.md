# Snake Game – Data Structures & Algorithms Project

## 📌 Project Overview
This project is a **Snake Game** implemented in **Java** as part of the **Data Structures and Algorithms** course.  
The main objective of this project is to apply fundamental data structures and algorithmic concepts in a practical and interactive application.

The game simulates the classic Snake gameplay where the snake grows longer after eating food and the game ends when the snake collides with the wall or itself.

---

## 🎯 Project Objectives
- Apply core data structures in a real-world application
- Understand how algorithms control game logic and movement
- Practice object-oriented programming in Java
- Design a simple but complete game system
- Improve problem-solving and logical thinking skills

---

## 🧩 Project Structure
```
Snake-Game/
│
├── Board.java # Game board rendering and repainting
├── Game.java # Main class – initializes the game window
├── GameLogic.java # Core game loop and collision handling
├── FoodObj.java # Food object generation and positioning
├── Direction.java # Enum defining snake movement directions
├── EndMenu.java # Game over menu and restart options
└── README.md # Project documentation
```

---

## 🧠 Data Structures Used
| Data Structure | Purpose |
|---|---|
| Array / ArrayList | Store snake body segments |
| Enum | Represent movement directions |
| Object references | Manage game entities (snake, food, board) |

---

## ⚙️ Algorithms Implemented
- Continuous game loop using a timer
- Collision detection (wall & self-collision)
- Random food generation
- Direction-based movement algorithm
- Score updating logic

---

## 🛠️ Technologies Used
- **Java (JDK 8+)**
- **Java Swing**
- **AWT Graphics**
- **Object-Oriented Programming (OOP)**

---

## 🎮 Controls
| Key | Action |
|---|---|
| Arrow Up | Move Up |
| Arrow Down | Move Down |
| Arrow Left | Move Left |
| Arrow Right | Move Right |

---

## ▶️ How to Run the Game

### 1️⃣ Prerequisites
- Java JDK 8 or higher
- Java IDE (IntelliJ IDEA, NetBeans, Eclipse, or VS Code)

### 2️⃣ Compile the project
```bash
javac *.java
```

### 3️⃣ Run the game
```bash
java Game
```

## 🖼️ Game Flow
- Game window is initialized
- Snake starts moving automatically
- Player controls snake direction using keyboard
- Snake grows after eating food
- Game ends if collision occurs
- End menu allows restart or exit

## 📚 Learning Outcomes
- Practical understanding of data structures
- Improved algorithmic thinking
- Experience with Java Swing GUI
- Applying theory into a functional application
- Understanding event-driven programming

## 🚀 Future Improvements
- Add pause/resume functionality
- Save and display high scores
- Increase difficulty dynamically
- Improve graphics and animations
- Add sound effects

## 📄 License
This project is developed for educational purposes as part of the
Data Structures & Algorithms course.
