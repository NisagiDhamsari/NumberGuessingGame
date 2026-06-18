# NumberGuessingGame
Group project implementing a Number Guessing Game in MIPS Assembly Language with modular design, GitHub collaboration, and QtSpim.

# 🎮 Number Guessing Game in MIPS Assembly

A console-based **Number Guessing Game** implemented in **MIPS Assembly Language** using **QtSpim**.

This project is developed as part of the **CSCI 12532 – Computer Architecture and Design** course offered by the **Department of Computer Systems Engineering, Faculty of Computing and Technology, University of Kelaniya**.

---

## 📖 Project Overview

The Number Guessing Game generates a random number within a predefined range. The player repeatedly enters guesses until the correct number is found.

After each guess, the program provides feedback:

- 📈 Too High
- 📉 Too Low
- 🎉 Correct Guess

The game also counts the number of attempts and allows the player to play multiple rounds.

---

## ✨ Features

- Random number generation
- User input handling
- Guess validation
- Too High / Too Low hints
- Attempt counter
- Winning message
- Play Again option
- Clean modular assembly code
- Well-documented source code

---

## 🛠 Technologies Used

- **MIPS Assembly Language**
- **QtSpim Simulator**
- **Git**
- **GitHub**

---

## 📂 Project Structure

```
Number-Guessing-Game-MIPS/
│
├── README.md
├── LICENSE
├── .gitignore
│
├── docs/
│   ├── Flowchart.png
│   ├── ProjectProposal.pdf
│   ├── Testing.md
│   └── UserGuide.md
│
├── src/
│   ├── main.asm
│   ├── game.asm
│   ├── random.asm
│   ├── input.asm
│   ├── compare.asm
│   ├── ui.asm
│   ├── replay.asm
│   └── utils.asm
│
├── include/
│   ├── constants.asm
│   ├── macros.asm
│   └── strings.asm
│
└── screenshots/
    ├── gameplay.png
    └── output.png
```

---

## 🔄 Program Flow

```
Start
   │
   ▼
Display Welcome Message
   │
   ▼
Generate Random Number
   │
   ▼
Attempts = 0
   │
   ▼
Get User Guess
   │
   ▼
Attempts++
   │
   ▼
Is Guess Correct?
 ┌───────────────┐
 │      Yes      │
 └──────┬────────┘
        ▼
 Display Congratulations
        │
 Display Attempts
        │
 Play Again?
   │
Yes▼          ▼No
Restart      Exit

If Guess < Number
      │
      ▼
   Too Low
      │
      ▼
    Repeat

If Guess > Number
      │
      ▼
   Too High
      │
      ▼
    Repeat
```

---

## 👥 Team Members

| Member | Responsibility |
|---------|----------------|
| Member 1 | Main Program & Game Loop |
| Member 2 | Random Number Generator |
| Member 3 | User Input & Validation |
| Member 4 | Guess Comparison Logic |
| Member 5 | User Interface & Messages |
| Member 6 | Replay System & Testing |
| Member 7 | Documentation, Integration & GitHub Management |

---

## 🌿 Git Workflow

Each team member works on a separate feature branch.

Example branches:

```
main
develop

feature/main-loop
feature/random-generator
feature/user-input
feature/guess-logic
feature/ui
feature/replay
feature/documentation
```

Development process:

1. Pull latest changes from `develop`
2. Create or switch to your feature branch
3. Implement your assigned task
4. Commit changes with meaningful commit messages
5. Push to GitHub
6. Create a Pull Request to `develop`
7. Review and merge after approval

---

## 💻 Installation

### Requirements

- QtSpim
- Git
- GitHub Account
- Visual Studio Code (recommended)

---

### Clone the Repository

```bash
git clone https://github.com/your-organization/Number-Guessing-Game-MIPS.git
```

---

### Open the Project

1. Open Visual Studio Code.
2. Open the project folder.
3. Launch QtSpim.
4. Load `src/main.asm`.
5. Assemble and Run.

---

## 📝 Coding Guidelines

- Use meaningful labels.
- Comment every procedure.
- Avoid duplicated code.
- Keep procedures modular.
- Use constants whenever possible.
- Follow consistent indentation.

---

## ✅ Testing

The project will be tested for:

- Correct random number generation
- Correct comparison logic
- Invalid input handling
- Replay functionality
- Attempt counting
- Program stability


