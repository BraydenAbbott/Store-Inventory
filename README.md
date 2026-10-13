# Store Inventory Management System (CLI)

##  Project Overview
A robust Command-Line Interface (CLI) tool designed to manage product stock levels, pricing, and unique identifiers. This application demonstrates core software engineering principles including Object-Oriented Design and persistent data state management.

## Technical Competencies
*   **Language:** Python 3
*   **Core Concepts:** Object-Oriented Programming (OOP), Inheritance, Data Structures (Dictionaries).
*   **Stability:** Error Exception Handling (`try/except` blocks).

##  Key Features
*   **Object-Oriented Architecture:** Utilized a custom `Product` class to encapsulate attributes (ID, Price, Quantity) for modular data handling.
*   **Robust Input Validation:** Engineered `try/except` logic to intercept invalid user inputs (e.g., non-numeric characters) and prevent runtime crashes.
*   **Dynamic CRUD Operations:** Implements logic to Add, View, and Remove products from the active inventory dictionary in real-time.
*   **Persistent Command Loop:** Designed a `while` loop structure to maintain the application state until the user explicitly terminates the session.

##  Optimization & Problem Solving
*   **Input Sanitization:** Addressed potential `ValueError` crashes by wrapping integer conversion inputs in exception handlers.
*   **Data Integrity:** Implemented logic to ensure product IDs are unique keys within the inventory dictionary to prevent data overwrites.
