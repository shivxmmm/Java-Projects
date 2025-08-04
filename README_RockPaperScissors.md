
# 🎮 Rock Paper Scissors — Java Swing Edition

A graphical Rock-Paper-Scissors game built with **Java Swing**—a fun and simple desktop application to test your choices against the computer. Designed using Swing components for a smooth UI experience. Perfect for Java learners exploring GUI development!

---

## 🧩 Features

- Intuitive **Java Swing GUI** with buttons for Rock, Paper, and Scissors
- Random computer selection with instant result
- Score tracking for player vs computer
- Replay rounds without restarting the application
- Clean and responsive window layout

---

## 🗂 Project Structure

```text
Java-Projects/
└── RockPaperScissorsSwing/
    ├── src/
    │   └── Main.java          # Game logic & Swing UI code
    ├── out.png                # Screenshot of the app in action
    ├── README.md
    └── LICENSE
```

> ⬆️ Update paths if your project folder structure is different

---

## 💡 Getting Started (Run Locally)

### ✅ Prerequisites

- Java Development Kit (JDK) 8 or above
- Basic understanding of running Java programs

### 💻 Run the Game

1. Clone the repository:
   ```bash
   git clone https://github.com/shivxmmm/Java-Projects.git
   cd Java-Projects/RockPaperScissorsSwing
   ```

2. Compile and run:
   ```bash
   javac src/Main.java
   java -cp src Main
   ```

   *Or if using an IDE like IntelliJ or Eclipse, simply open the `.java` file and press "Run".*

---

## 📸 Screenshot

Here’s what the game looks like on launch:

![Game Screenshot](./RockPaperScissorsSwing/out.png)

---

## 🎯 How to Play

1. Click on **Rock**, **Paper**, or **Scissors**
2. The computer instantly shows its choice
3. The result is displayed (You Win / Lose / Tie)
4. Play again automatically without restarting

---

## 🧠 Technical Overview

- Uses `javax.swing.JFrame` for main window
- Uses `JButton` for player choices and `JLabel` for status
- Random computer move with `java.util.Random`
- Game loop handled via event-driven button listeners

---

## 📈 Possible Enhancements

- Add cumulative score tracking across rounds
- Include options like **Lizard** or **Spock**
- Add a **restart** button
- Improve UI with colors, icons, and responsive layout
- Add sound effects or animations

---

## 📝 License & Author

**License**: Open-source (MIT License recommended)  
**Developer**: Shivam Kakade  
GitHub: [shivxmmm](https://github.com/shivxmmm) • Feel free to reach out!

---

Enjoy playing—and feel free to fork this project, tweak it, and make it your own 💥
