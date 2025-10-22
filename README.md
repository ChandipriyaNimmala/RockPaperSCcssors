# ✊🖐✌ Rock Paper Scissors Game (C Program)

This repository contains a simple and fun **Rock Paper Scissors** game implemented in **C language**. It’s an interactive console-based project where the player competes against the computer by choosing between **Stone**, **Paper**, and **Scissor**.

---

## 🕹️ Game Overview

The player enters their choice:
- `s` → **Stone**
- `p` → **Paper**
- `z` → **Scissor**

The computer randomly selects one of the three options using the `rand()` function, and the program determines the winner based on traditional game rules:

- Stone beats Scissor  
- Scissor beats Paper  
- Paper beats Stone  

---

## 💡 Features

- Interactive and easy-to-play console interface  
- Randomized computer moves using `rand()` and `srand()`  
- Displays both player and computer choices  
- Announces result as **Win**, **Lose**, or **Draw**  
- Beginner-friendly logic using simple `if-else` statements  

---

## ⚙️ Technologies Used

- **Language:** C  
- **Libraries:** `stdio.h`, `stdlib.h`, `time.h`, `math.h`  
- **Concepts:** Random number generation, conditional logic, user input  

---

## 🚀 How to Run

1. Save the file as `rock_paper_scissors.c`  
2. Compile the code using GCC:
   ```bash
   gcc rock_paper_scissors.c -o rps
