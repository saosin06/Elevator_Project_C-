# Elevator_Project_C++
Group Members: Nicholas Costello, Ryan Farzenah, and Tenz Kunga 
# 🛗 Elevator Simulation (C++ Console App)

##  Overview

This is a basic elevator simulation written in C++. It models a single elevator system within a building of 5–20 floors. The program accepts floor requests from the user, simulates the elevator moving between floors, and displays real-time status updates, including floor level, direction, and door status.

This project demonstrates:
- Object-oriented programming
- Use of standard C++ libraries (`queue`, `thread`, `chrono`)
- Console-based simulation and user interaction

---

##  Features

- Accepts user input for floor requests (e.g., 0–9)
- Elevator automatically moves to the requested floor
- Simulated movement delay for realism
- Displays elevator status: current floor, direction, and door state
- Rejects invalid input
- Allows user to type `'exit'` to end the simulation

---

##  Requirements

- C++ compiler (e.g., `g++`)
- C++11 or newer
- Terminal or console access

---

## 🔧 How to Compile & Run

### Compile:
```bash
g++ elevator.cpp -o elevator -std=c++11
