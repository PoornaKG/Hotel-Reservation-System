# Hotel-Reservation-System
A console-based Hotel Reservation System developed using Java (JDBC) and MySQL. This project allows users to manage hotel room reservations efficiently through a simple menu-driven interface.

📌 Project Overview

The Hotel Reservation System is designed to manage hotel room bookings efficiently through a simple menu-driven console interface.
It allows users to:
Book rooms
View reservation details
Update guest information
Delete reservations
Retrieve room numbers using reservation details

This project demonstrates strong understanding of Core Java, JDBC connectivity, SQL operations, and exception handling.

🚀 Features

✅ Reserve a Room

✅ View All Reservations

✅ Get Room Number using Reservation ID & Guest Name

✅ Update Existing Reservation

✅ Delete Reservation

✅ Graceful Exit with loading animation

🛠️ Technologies Used

Java (Core Java)
JDBC (Java Database Connectivity)
MySQL
SQL
Object-Oriented Programming (OOP)

🗄️ Database Schema

Database Name: hotel_db
Table Name: reservations

Column Name	Data Type	Description
reservation_id	INT (Primary Key, Auto Increment)	Unique reservation ID
guest_name	VARCHAR	Guest Name
room_number	INT	Room Number
contact_number	VARCHAR	Contact Details
reservation_date	TIMESTAMP	Date & Time of Reservation

⚙️ How to Run the Project
1️⃣ Setup Database

Create the database and table in MySQL:

CREATE DATABASE hotel_db;
USE hotel_db;

CREATE TABLE reservations (
    reservation_id INT PRIMARY KEY AUTO_INCREMENT,
    guest_name VARCHAR(100),
    room_number INT,
    contact_number VARCHAR(15),
    reservation_date TIMESTAMP DEFAULT CURRENT_TIMESTAMP
);

2️⃣ Update Credentials

Update your MySQL username and password in the Java file:

private static final String username = "root";
private static final String password = "your_password";

3️⃣ Compile and Run
javac HotelReservationSystem.java
java HotelReservationSystem

📷 Sample Menu
HOTEL MANAGEMENT SYSTEM
1. Reserve a room
2. View Reservations
3. Get Room Number
4. Update Reservations
5. Delete Reservations
0. Exit

📚 Concepts Demonstrated

JDBC Driver Loading
Establishing Database Connection
Executing SQL Queries
CRUD Operations (Create, Read, Update, Delete)
Exception Handling
Menu-Driven Application Design
