# Library Management System Database

## Description
This project is a relational database designed using MySQL for managing a library.  
It tracks books, authors, members, and borrowings, allowing the library to manage its collection and lending operations efficiently.  

The database demonstrates primary keys, foreign keys, unique constraints, and relationships including:
- One-to-Many (Members → Borrowings, Books → Borrowings)
- Many-to-Many (Books ↔️ Authors via BookAuthors table)

---

## How to Set Up / Run

1. Install MySQL on your system.  
2. Open MySQL Workbench (or any MySQL client).  
3. Create a new database (optional, included in the SQL file):  
```sql
CREATE DATABASE LibraryDB;
USE LibraryDB;
