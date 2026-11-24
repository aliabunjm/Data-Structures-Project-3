# Stack and Queue Implementation in C++

A C++ implementation of **Stack and Queue Data Structures** using a custom Doubly Linked List.

## Overview

This project demonstrates how Stack and Queue data structures can be implemented using a custom Doubly Linked List.

It includes two main data structures:

### 1. Queue (FIFO)
First In, First Out.

Elements are inserted at the back and removed from the front.

### 2. Stack (LIFO)
Last In, First Out.

The Stack is implemented by inheriting from the custom Queue class and overriding the `push()` operation to insert elements at the beginning.

## Features

### Queue Operations
- `push()` — Add an element.
- `pop()` — Remove the front element.
- `front()` — Get the first element.
- `back()` — Get the last element.
- `Size()` — Get the number of elements.
- `IsEmpty()` — Check whether the queue is empty.

### Stack Operations
- `push()` — Add an element to the top.
- `pop()` — Remove the top element.
- `Top()` — Get the top element.
- `Bottom()` — Get the bottom element.

### Additional Operations
- Print elements.
- Get an item by index.
- Update an item.
- Reverse the structure.
- Insert after a specific index.
- Insert at the front or back.
- Clear all elements.

## Project Structure

- `main.cpp` — Demonstrates Stack operations.
- `clsMyStack.cpp` — Contains the Stack implementation.
- `clsMyQueue.cpp` — Contains the Queue implementation.
- `clsDblLinkedList.cpp` — Contains the underlying Doubly Linked List implementation.

## Technologies

- C++
- Object-Oriented Programming
- Class Inheritance
- Templates
- Pointers
- Dynamic Memory Allocation
- Data Structures

## How to Run

Compile using g++:

```bash
g++ main.cpp -o main
```

Run on Windows:

```powershell
.\main.exe
```

## Learning Objectives

- Understanding FIFO and LIFO principles.
- Implementing Stack and Queue from scratch.
- Using inheritance in C++.
- Reusing existing data structures.
- Understanding how multiple data structures work together.

---

**Author:** Ali Abunjm

**GitHub:** [@aliabunjm](https://github.com/aliabunjm)
