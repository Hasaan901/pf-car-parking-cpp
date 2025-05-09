# PF Car Parking Project (C++)

This project is a basic multi-story car parking system developed in C++. It simulates real-world parking management, handling car entries, floor assignments, and overflow situations using fundamental data structures.

## 🚗 Features
- **Dynamic Array**: To store car parking details by floor and position.
- **Stack**: Each floor is implemented using a stack to mimic LIFO parking.
- **Queue**: Entry management is handled via a circular queue.
- **Linked List**: Used for managing an overflow waitlist when floors and queue are full.

## 🧠 Key Concepts
- Dynamic memory allocation
- Object-oriented programming (classes)
- Structs
- Stack, Queue, Linked List implementations
- Modular design with reusable components

## 📂 Project Structure
- `CarDetails` struct
- `ParkingDetails` class for tracking positions
- `EntryQueue` for incoming cars
- `OverflowWaitlist` for overflow management
- `Floor` class representing parking floors

## 🛠 How to Compile
You can compile using any C++ compiler:
```bash
g++ -o car_parking main.cpp
./car_parking
