# ✈️ Airline Management System

An Object-Oriented Programming (OOP) application designed to simulate real-world airline operations, client bookings, and flight management workflows. This system focuses heavily on data encapsulation, structural hierarchies, and relationship mapping between system entities.

## 📐 System Architecture & OOP Design
The system is structured using clear class responsibilities to handle flight booking life cycles seamlessly:
* **User/Passenger Records:** Tracks core registration details including name, contact info, gender, and date of birth.
* **Flight Logistics (`Flights detail`):** Manages dynamic flight schedules, departure dates, pricing strategies, and real-time seat availability configurations.
* **Ticketing & Reservation (`tickets` & `seats`):** Handles seat layout allocation metrics (`isempty()`, `isfull()`) linked to unique ticket tracking booking numbers.
* **Transaction Processing (`payment`):** Simulates secure server-side billing interactions via online payment portals and NetBanking integrations.

## 🛠️ Tech Stack & Core Concepts
* **Paradigm:** Object-Oriented Programming (OOP)
* **Core Concepts:** Inheritance structures, encapsulation boundaries, class-to-class interactions, and state validation.
* **Database Management (IICT Component):** Structured relationships handled via relational database schemas (`.accdb`) to persist entity tracking information.
