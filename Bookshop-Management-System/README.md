# 📚 Bookshop Management System

A C++ console application designed to digitize, streamline, and optimize daily business operations for small-to-large scale bookshops. The application transitions manual bookkeeping into an accurate, time-saving digital terminal system.

## 📊 Data Structures & Core Logic
Unlike typical CRUD applications, this system explicitly incorporates core Data Structures and Algorithms (DSA) concepts to handle records sequentially:
* **Stack Implementation (LIFO):** Utilizes a linear Stack data structure to organize book inventories, tracking specific editions and available copies sequentially.
* **Stack Operations:** Implements core low-level operations including `Push()` to add new inventory, `Pop()` to process purchases, and `Top()` / `Empty()` check constraints to manage real-time availability.
* **Performance Metrics:** Optimized tracking operations with localized time complexities aimed at $O(1)$ stack manipulations.

## ⚙️ Application Features
The system compiles a multi-functional management console menu allowing administrators to safely execute business logistics:
1. **Purchase Processing:** Step-by-step transaction workflow to buy inventory.
2. **Global Inventory Audit:** Clear rendering matrices to show all books stored in active memory.
3. **Availability Auditing:** Direct search indexing via unique Book ID Numbers to verify stock metrics.
4. **Data Modification:** Direct structural records modification for updates and deletions.

## 🛠️ Technical Stack
* **Language:** C++
* **Concepts:** Linear Data Structures, Stack Operations (LIFO), Console UI rendering, File Stream Handling (`fstream`)
