# Library Management System
Course project for Introduction to Database (DS2201) at Umm Al-Qura University. Team of 4.

## Overview
A relational database that manages book borrowing in a university library: students, books, librarians, and borrowing records with due dates and fines.

## Design
- Conceptual design: ERD
- Logical design: relational schema

Relationships:
- One student can have many borrowing records
- One book can have many borrowing records
- One librarian can handle many borrowing records
- Each borrowing record belongs to one student, one book, and one librarian

## Implementation
- Four tables (`Student`, `Book`, `Librarian`, `Borrowing`) with primary keys, foreign keys, and UNIQUE, CHECK, and DEFAULT constraints
- Sample data (5 records per table)
- Queries: basic SELECT, WHERE filtering, COUNT, AVG, a three-table JOIN, and a subquery
- A view (`Borrowing_Summary`) combining student, book, and borrowing details

## My Contribution
Created the ERD and commented the SQL code.

## Files
- `library_management_system.sql`: schema, data, queries, and view
- `erd.png`: entity-relationship diagram
