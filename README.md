
# 🚌 Bus & Train Booking System (C++)

A simple **console-based booking system** built using **C++**, designed to simulate basic ticket management for buses or trains.

This version uses **manual memory management** (no STL containers like `<vector>`), making it easy to understand for beginners learning **object-oriented programming (OOP)** and **dynamic allocation** in C++.

---

## 🚀 Features

✅ View all available routes (buses or trains)  
✅ View the seating layout for any selected vehicle  
✅ Book seats for passengers  
✅ Prevents double-booking of seats  
✅ Simple, beginner-friendly code — no complex libraries used  

---

## 🧩 Class Overview

| Class | Description |
|--------|--------------|
| **`Seat`** | Represents a single seat with booking status and passenger name. |
| **`Bus`** | Represents one vehicle (bus/train), containing seats and booking logic. |
| **`BookingSystem`** | Manages all vehicles and provides a main menu for user interaction. |

---

## 🛠️ Requirements

- A C++ compiler (e.g. `g++`, `clang++`, or any IDE like Code::Blocks or Dev-C++).  
- Runs on Windows, Linux, or macOS.  
- No external dependencies.

---

## 💻 Compilation & Execution

### Using Terminal / Command Prompt

```bash
# Compile
g++ booking_system.cpp -o booking_system

# Run
./booking_system
````

### Using Code::Blocks / Dev-C++

1. Create a new console project.
2. Replace the default `main.cpp` with this file’s code.
3. Build and Run the project.

---

## 🧠 How It Works

1. The program starts with **three sample routes**:

   * `B-01`: New York → Boston (20 seats)
   * `B-02`: Chicago → Dallas (30 seats)
   * `T-10`: San Francisco → LA (Train, 50 seats)

2. From the main menu, you can:

   * **View Available Routes**
   * **View Seating Map**
   * **Book a Ticket**
   * **Exit**

3. The system validates inputs, prevents double bookings, and displays updated seating charts after each booking.

---

## 🪄 Example Run

```
===== Bus & Train Booking System =====
1. View Available Routes
2. View Seating Map
3. Book a Ticket
4. Exit
======================================
Enter your choice (1-4): 1

--- Available Routes ---
Vehicle No.    Route
------------------------------------
B-01           New York to Boston
B-02           Chicago to Dallas
T-10           San Francisco to LA (Train)
------------------------------------

Press Enter to return to the main menu...
```

---

## ⚙️ Code Highlights

* No use of `<vector>`, `<iomanip>`, or `<limits>`.
* Dynamic memory allocation via `new` and `delete`.
* Clean OOP structure with destructors to free memory.
* Input validation and basic UI formatting for clarity.

---

## 🧾 License

This project is provided for **educational use**.
You are free to modify, extend, and experiment with it for learning purposes.


```
