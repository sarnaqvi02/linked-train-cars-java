# Linked Train Cars (Java)

## Overview
This project implements a **singly linked list** in Java to model a train composed of individual train cars. Each car is represented as a node in the list, and cars are linked together using references. The project includes a graphical interface that allows users to insert and remove train cars at specific positions.

The focus of this assignment is the **data structure implementation**, specifically pointer manipulation, traversal, and edge-case handling in a linked list.

---

## Project Structure
src/
  singly/
    Driver.java
    TrainCar.java
    LinkedTrainCars.java

---

## Data Structures Used
- Singly linked list
- Custom node class (`TrainCar`)

---

## Key Classes

### `TrainCar`
Represents a single node in the linked list.
- Stores the name of the train car
- Contains a reference to the next car in the list

### `LinkedTrainCars`
Implements the linked list logic.
- Maintains a reference to the front of the list
- Supports insertion and removal at arbitrary positions
- Provides traversal and size functionality

### `Driver`
Provides a graphical user interface for testing the linked list.
- Allows users to add and remove cars using buttons and input controls
- Visually renders the linked list as a train

---

## Features
- Insert a train car at a specific index
- Remove a train car at a specific index
- Dynamically update and display the number of cars
- Visual representation of the linked list structure

---

## How to Run

### Compile
```bash
javac src/singly/*.java

---

## What I Learned
How to implement a singly linked list from scratch
Managing references and pointer manipulation in Java
Handling edge cases such as empty lists and out-of-bounds indices
Designing code to work with an existing interface and GUI

---

## Notes
Driver.java was provided as part of the course assignment and was not modified.
