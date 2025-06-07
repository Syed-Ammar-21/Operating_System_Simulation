# 🖥️ Operating System Simulation

A Linux terminal-based Operating System simulator developed in **C++** that demonstrates core OS concepts like **process scheduling**, **dynamic memory allocation**, **file management**, and **basic task execution**.

---

## 🔧 Features

- 🧠 **Simulated Multitasking**: Basic task management with process state transitions (Ready, Running, Waiting).
- 💾 **Dynamic Memory Allocation**: Simulates memory requests and releases with runtime memory handling.
- 🗂️ **File Operations**: Basic utilities to create, delete, rename, and edit files like a notepad.
- 🕹️ **Mini-Games & Tools**: Includes simple interactive applications such as:
  - Tic Tac Toe
  - Notepad
  - Calendar
  - Quote Generator
  - Hangman

---

## 🧰 Tech Stack

- **Programming Language**: C++
- **Platform**: Linux Terminal
- **Concepts Used**:
  - Process and Memory Management
  - Modular Programming
  - File I/O
  - Terminal UI

---

## 📂 Folder Structure

📁 Operating_System_Simulation
├── os.cpp
├── memory.cpp / .h
├── process.cpp / .h
├── file_operations.cpp / .h
├── games/
│   ├── tictactoe.cpp
│   ├── hangman.cpp
├── tools/
│   ├── calendar.cpp
│   ├── notepad.cpp
│   ├── quotes.cpp
└── README.md

---

 ## 🚀 How to Run
  - Go to the repository page and look for the **Clone** or **Code** button.
  - Copy the HTTPS URL.
  - Open Terminal **(Mac/Linux: Use Terminal = Ubuntu/ Windows: Use Git Bash (installed with Git).**
  - cd /path/to/your/folder (where u want to put the repository).
  - Run the git clone command with copied **HTTP URL.**
  - After repo is cloned, compile the project by checking **COMPILATION.txt** file for main file, as well as for other applications.
  - Main file for this project is **os.cpp**. So first compile **(g++ -pthread -o mainprog os.cpp -lcurses)**, where **mainprog** can be any name of your choice.
  - Finally after compiling, execute the project using your name choice. For this it was mainprog, so, **(./mainprog).**
 
 
