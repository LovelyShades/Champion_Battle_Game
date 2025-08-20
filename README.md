# 🛡️ Champion Battle Game (C)

[![C](https://img.shields.io/badge/Language-C-blue.svg)](https://en.wikipedia.org/wiki/C_(programming_language)) 
[![Platform](https://img.shields.io/badge/Platform-Console-lightgrey.svg)]() 
[![Status](https://img.shields.io/badge/Status-Completed-brightgreen.svg)]()

A console-based **Champion Management and Battle System** written in C.  
Uses **linked lists** to dynamically create, manage, and sort champions by level, with battle logic that accounts for random roles and role advantages.  
Focuses on safe memory management and modular C programming.  

> **Course:** UTSA · CS2124 · Spring 2024  
> **Author:** Alanna Matundan  

---

## ✨ Features
- Dynamic champion creation with **random roles** (Mage, Fighter, Support, Tank)  
- Champions stored in a **level-sorted linked list**  
- Battle simulation system with role-based advantages  
- Winners may gain new champions; losers may lose some  
- Safe **memory allocation, traversal, and cleanup**  

---

## 🧰 Tech Stack
- **Language:** C (C99 standard)  
- **Data Structures:** Linked lists, enums  
- **Build Tool:** GCC / Make  

---

## 🚀 Getting Started
### Prerequisites
Install **GCC** (or another C compiler). Check with:  
```bash
gcc --version

# clone repo
git clone https://github.com/LovelyShades/Chamption_Battle_Game.git
cd Chamption_Battle_Game

#Compile
Using the provided Makefile:
make
Or manually:
gcc -Wall -Wextra -std=c99 -o project3Exe main.c champion.c

#Run
./project3Exe 5

(Example runs the game with 5 champions per player)

📖 Usage
When running the game:

Each player starts with N champions

Champions are randomly assigned a role and level

Battles proceed round by round until one player has no champions left

Example:

----- ROUND 1 -----
Player 1: M7 F5 T6
Player 2: S4 T8 M6
Player 1 is a MAGE and Player 2 is a SUPPORT
Player 1 (MAGE) wins and gains a new champion.
Player 2 (SUPPORT) loses two champions.

🧱 Project Structure
main.c       # game loop & battle logic
champion.c   # champion creation, insertion, removal
champion.h   # struct + function declarations
Makefile     # build instructions
README.md    # documentation

📚 What I Learned
Implemented linked lists in C for dynamic data storage

Designed enum-based roles with random assignment

Practiced memory management (malloc/free)

Built a battle simulation system with conditional logic

Reinforced modular programming principles in C

🛣️ Future Improvements
Add save/load functionality for champion rosters

Improve battle balancing and randomness

Expand champion attributes (HP, Attack, Defense)

Add automated unit tests

📜 License
Educational project — free to fork, adapt, and extend with attribution.
