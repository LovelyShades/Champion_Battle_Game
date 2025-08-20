# 🛡️ Champion Battle Game (C)
[![C](https://img.shields.io/badge/Language-C-blue.svg)](https://en.wikipedia.org/wiki/C_(programming_language)) [![Platform](https://img.shields.io/badge/Platform-Console-lightgrey.svg)]() [![Status](https://img.shields.io/badge/Status-Completed-brightgreen.svg)]()

A **C-based Champion Management and Battle System** utilizing **linked lists** to create, manage, and sort dynamically generated champions. Implements random role assignment, level-based sorting, and memory-efficient operations, including list traversal, insertion, and cleanup.

> **Course:** UTSA · CS2124 · Spring 2024  
> **Author:** Alanna Matundan  

## ✨ Features
- Dynamic champion creation with **random roles** (Mage, Fighter, Support, Tank)  
- Champions stored in **level-sorted linked lists**  
- Battle simulation system with role advantages  
- Winners may gain new champions, losers may lose some  
- Safe **memory allocation, traversal, and cleanup**  

## 🧰 Tech Stack
- **Language:** C (C99 standard)  
- **Data Structures:** Linked lists, enums  
- **Build Tool:** GCC / Make  

## 🚀 Getting Started
### Prerequisites
Install GCC (or another C compiler).  
Check with:  
gcc --version


### Compile
make

or manually:  
gcc -Wall -Wextra -std=c99 -o project3Exe main.c champion.c


### Run
./project3Exe 5


*(Example runs the game with 5 champions per player)*  

## 📖 Usage
When running the game:
- Each player starts with **N champions**
- Champions are randomly assigned a role and level
- Battles proceed round by round until one player has no champions left

### Example
----- ROUND 1 -----
Player 1: M7 F5 T6
Player 2: S4 T8 M6
Player 1 is a MAGE and Player 2 is a SUPPORT
Player 1 (MAGE) wins and gains a new champion.
Player 2 (SUPPORT) loses two champions.


## 🧱 Project Structure
main.c # game loop & battle logic
champion.c # champion creation, insertion, removal
champion.h # struct + function declarations
Makefile # build instructions
README.md # documentation


## 📚 What I Learned
- Implemented **linked lists** in C for dynamic storage  
- Designed **enum-based roles** with random assignment  
- Practiced **memory management** (malloc, free)  
- Built a **battle simulation** with conditional logic  
- Reinforced **modular programming** in C  

## 🛣️ Future Improvements
- Add file save/load for champion rosters  
- Improve battle balancing and randomness  
- Expand champion attributes (HP, Attack, Defense)  
- Add unit tests  

## 📜 License
Educational project. Free to fork & adapt with attribution.
