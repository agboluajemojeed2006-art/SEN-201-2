# 📚 Student Gradebook System (No-Import)

A lightweight, command-line interface (CLI) application for managing student grades. This project demonstrates **Layered Architecture** and **File I/O** in Python without relying on external libraries.

## 🏗️ Architecture Design

This application follows a strict **Separation of Concerns** using three distinct layers:

1.  **Model Layer (StudentModel):**
    * Defines the data structure for a student (Name and Grade).
    * Handles data serialization.
2.  **Storage Layer (TextFileRepository):**
    * Manages distinct interactions with the file system (database.txt).
    * Handles appending data, reading lines, and clearing the database.
3.  **Interface Layer (ConsoleUI):**
    * The Frontend of the application.
    * Handles user input, menu display, and printing results.

---

## 🚀 How to Run This Code

### Prerequisites
* Python 3.x installed.

### Steps

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/agboluajemojeed2006-art/SEN-201-2.git
    ```

2.  **Navigate to the project directory:**
    ```bash
    cd SEN-201
    ```

3.  **Run the script:**
    ```bash
    python main.py
    ```

---

## 👤 Author
* AGBOLUAJE MOJEED **
* **Course:** SEN 201 CYBER SECURITY
* **Institution:** Caleb University
* **GitHub:** https://github.com/agboluajemojeed2006-art
*

