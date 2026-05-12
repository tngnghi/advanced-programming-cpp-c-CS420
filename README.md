# CS 420 — Advanced Programming in C++ & C

Coursework submissions for **CS 420: Advanced Programming** at San Diego State University, Fall 2025.

This course covered systems-level programming in C and C++, with a focus on writing efficient, low-level code that you can't get away with in higher-level languages.

**Course:** CS 420 — Advanced Programming in C++ & C  
**Institution:** San Diego State University  
**Semester:** Fall 2025  
**Language:** C++ / C

---

## Topics Covered

- **Data structures in C++** — implementing containers from scratch
- **OOP in C++** — classes, inheritance, polymorphism, constructors/destructors
- **Memory management & pointers** — manual allocation, pointer arithmetic, avoiding leaks
- **Low-level C programming** — structs, unions, bitfields, direct memory access

---

## Repository Structure

```
advanced-programming-cpp-c-CS420/
├── hwblackjack/     # Homework: Blackjack card game in C++
├── hwc/             # Homework: Low-level C programming exercises
└── final/           # Final: Data structure implementation (stack-based, with provided headers)
```

---

## Projects & Assignments

### `hwblackjack/` — Blackjack Game
A terminal-based Blackjack card game built in C++. Demonstrates OOP design with classes for cards, decks, hands, and player logic.

### `hwc/` — C Programming Exercises
Low-level C assignments exploring pointers, memory management, structs, and system-level operations.

### `final/` — Data Structure Implementation *(Final Exam)*
A coding exam applying data structure concepts from the course (stack-based, built on provided header files and starter code). Demonstrates working within an existing codebase — reading interfaces, implementing logic, and integrating with given structures.

---

## How to Compile & Run

Most programs use standard `g++` or `gcc`:

```bash
# C++ files
g++ -std=c++17 -o output filename.cpp
./output

# C files
gcc -o output filename.c
./output
```

---

*Part of my CS coursework at SDSU. See my other repositories for personal and group projects.*
