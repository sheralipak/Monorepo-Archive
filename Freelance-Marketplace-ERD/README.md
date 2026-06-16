# 📊 Freelance Marketplace Database Architecture & ERD

A system engineering and database design project mapping out a multi-entity relational database architecture for a full-scale Freelance Marketplace. The design focuses heavily on database normalization, data-type validation, and structural access permissions between users.

## 📐 Relational Database Schema & Entities
The architecture models complete user lifecycle workflows by mapping relationships between primary business operational entities:

* **User Registration System (`register`):** Centralizes core demographic data and authorization fields including User Name, Email, Password hashing triggers, Cell Number, Address, Gender, and User Type assignment.
* **Client Management (`CLIENT`):** Represents users seeking talent, tracking distinct parameters like Unique Client ID and Client Name.
* **Freelancer Profiles (`FREELANCER`):** Represents independent developers/creators, logging Unique Freelancer ID fields, Worked Projects counts, and specialized Profile Quality Ratings.
* **Project Lifecycles (`PROJECTS`):** Binds clients and freelancers through primary keys (`ProjectID`, `ClientID`, `FreelancerID`), mapping Project Categories, Subcategories, Budgets, Durations, and Developer Work Statuses.
* **Financial Ledger (`PAYMENT`):** Handles transaction states, linking specific project IDs to financial variables like Client Payment Status and Payment Receipt Status.

## ⚙️ Data Flow & Relationship Mapping
* **Client Actions:** A Client **adds** a new project template and **hires** a qualified Freelancer.
* **Freelancer Actions:** A Freelancer **works** on active assignments and **receives** monetary milestones.
* **Security Relevance (SOC/Access Controls):** Demonstrates knowledge of relational access controls, data boundaries, and mandatory authentication field storage logic.

## 🛠️ Technical Focus
* Database Modeling & Normalization
* Entity-Relationship Diagramming (ERD)
* Relational Schema Constraints (Primary Keys, Foreign Keys)
