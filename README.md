#  Hotel Management System – DBMS Mini Project

A relational database management system designed to manage hotel operations including customers, rooms, reservations, employees, payments, food orders, and hotel administration.

This project was developed as part of the **Database Management Systems Laboratory** and focuses on database design, relational modeling, SQL querying, functional dependencies, and normalization.

---

## 📌 Project Overview

The Hotel Management System provides a structured database for managing the core operations of a hotel.

The system models relationships between:

- Hotels
- Rooms
- Customers
- Stays / Reservations
- Employees
- Administrators
- Attendants
- Room Types
- Payments
- Food Orders

The database was designed using an **Entity-Relationship (ER) model** and converted into a relational schema with appropriate keys and relationships.

---

## 🎯 Objectives

- Design a structured relational database for hotel management.
- Model relationships between hotel entities using an ER diagram.
- Maintain data consistency using primary and foreign keys.
- Store and manage customer, room, reservation, employee, payment, and food-order information.
- Perform SQL-based analysis using joins and aggregate queries.
- Apply normalization to minimize redundancy and improve data integrity.
- Analyze functional dependencies and determine the highest normal form of relations.

---

## 🗂️ Database Entities

The database consists of the following major entities:

| Entity | Purpose |
|--------|---------|
| `Hotel` | Stores hotel details and location |
| `Room` | Maintains room information, type, location, and status |
| `Customer` | Stores customer personal and contact information |
| `Stay` | Records reservations, check-in/check-out, and stay details |
| `Room_Type` | Stores room categories and corresponding amounts |
| `Employee` | Maintains employee information and salary |
| `Admin` | Stores administrator credentials |
| `Attendant` | Maintains attendant information and service details |
| `Order` | Records customer food orders |
| `Food` | Stores food requirements associated with orders |
| `Payment` | Maintains payment details for customers |

The project documentation contains the ER diagram showing the relationships among these entities.

---

## 🏗️ Database Design

### ER Diagram

The system was first modeled using an Entity-Relationship diagram to represent entities, attributes, and relationships.

The major relationships include:

- Hotel → Rooms
- Hotel → Employees
- Customer → Stay
- Customer → Payment
- Customer → Food Orders
- Room → Stay
- Employee → Attendance
- Stay → Room Type
- Customer → Orders
- Orders → Food
  <img width="1870" height="1043" alt="image" src="https://github.com/user-attachments/assets/f9e129d4-5704-4617-b63d-674cca1b6769" />

---

## 🔗 Relational Schema

The ER model was transformed into a relational schema containing relations such as:
<img width="1921" height="1082" alt="image" src="https://github.com/user-attachments/assets/3a7ab87a-94b5-4978-be7e-0bc7eee43177" />

```text
Hotel
Room
Customer
Stay
Room_Type
Employee
Admin
Attendant
Order
Food
Payment


