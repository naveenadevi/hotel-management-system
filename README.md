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

Below are snapshots of the Hotel Management System application, showcasing the implemented database-driven functionalities and user interface.
<img width="1920" height="1080" alt="Screenshot 2024-06-06 203624" src="https://github.com/user-attachments/assets/5d0f190f-f740-4df1-8e2a-0bf177552a17" />
<img width="1681" height="525" alt="Screenshot 2024-06-06 203640" src="https://github.com/user-attachments/assets/b78f4a67-b7b6-48e1-b9db-3952fda1c7b3" />
<img width="733" height="363" alt="Screenshot 2024-06-06 203652" src="https://github.com/user-attachments/assets/36b1c748-2434-46f8-9450-0adfe84469ee" />
<img width="1903" height="1012" alt="Screenshot 2024-06-06 203720" src="https://github.com/user-attachments/assets/3bc6b442-4c5b-44dd-8e81-81d662f256f6" />
<img width="1043" height="701" alt="Screenshot 2024-06-06 203744" src="https://github.com/user-attachments/assets/495c7ebb-e50b-4b10-babb-65fda1373655" />
<img width="1047" height="674" alt="Screenshot 2024-06-06 203807" src="https://github.com/user-attachments/assets/2d4a48a1-3504-436e-ae81-239bcc58ef1c" />
<img width="1356" height="729" alt="Screenshot 2024-06-06 203838" src="https://github.com/user-attachments/assets/dd064666-35d2-40de-8da2-8a977692b8cf" />
<img width="1231" height="732" alt="Screenshot 2024-06-06 203855" src="https://github.com/user-attachments/assets/3230efd6-e4a5-4055-bf91-5e8c45bb3d3d" />
<img width="951" height="344" alt="Screenshot 2024-06-06 203920" src="https://github.com/user-attachments/assets/758b1713-58ae-4a84-85f1-8d467c3d0280" />
<img width="1167" height="613" alt="Screenshot 2024-06-06 203937" src="https://github.com/user-attachments/assets/31e42569-d996-4b58-8ea0-6f3fca9bdbbb" />
<img width="1182" height="526" alt="Screenshot 2024-06-06 203959" src="https://github.com/user-attachments/assets/abe77927-b1a1-4e2e-97b0-027ae424e0a1" />
<img width="1097" height="730" alt="Screenshot 2024-06-06 204022" src="https://github.com/user-attachments/assets/ede40ba8-abcc-4c41-bf1c-c80db4702c6f" />
<img width="1235" height="536" alt="Screenshot 2024-06-06 204038" src="https://github.com/user-attachments/assets/ffc01599-f956-43d3-923d-8fc8dce315c5" />


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


