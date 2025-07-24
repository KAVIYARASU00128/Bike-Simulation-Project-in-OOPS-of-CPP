# Bike-Simulation-Project-in-OOPS-of-CPP
#  OOP Concepts in C++ – Vehicle and Bike Simulation

This project demonstrates key **Object-Oriented Programming (OOP)** concepts in C++ through a simple vehicle and bike simulation. It uses encapsulation, inheritance, abstraction, and class composition to model the behavior of a bike with an internal engine.

---

## Features

- **Encapsulation** via a private nested `Engine` class inside `vehicle`
- **Inheritance** where `bike` class inherits from `vehicle`
- **Composition (Has-A)** – A vehicle **has an** engine
- **Abstraction** – Hides engine-level details and exposes simple vehicle controls
- User input support for bike model and color

---

## 🛠️ Code Overview

### `Engine` class (nested inside `vehicle`)
Represents a simplified engine:
- `start()`: Displays "Engine Is Started"
- `accelerate()`: Displays "Engine Is Accelerated"
- `stop()`: Displays "Engine Is Stopped"

### `vehicle` class
Represents a generic vehicle and controls the engine:
- `start()`: Starts the engine
- `accelerate()`: Accelerates the engine
- `brake()`: Stops the engine

### `bike` class
Inherits from `vehicle` and adds:
- `model`: Integer for bike model number
- `colour`: String for bike color
- `show()`: Displays the bike's model and color
- `input()`: Takes user input for model and color

---
   
