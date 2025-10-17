# Stephen

Regular User:

Username: John Doe
Password: pass123

Admin User:

Username: Admin
Password: admin123

This project is a simple Library Management System built using Java.
It allows users to log in, view available books, borrow, and return them.
All data is stored in plain text files, ensuring information is preserved even after the program closes.

📂 Files Used
File Name	Purpose
users.txt	Stores user details (ID, Name, Password, Role)
books.txt	Contains book information (ID, Title, Author, Availability)
transactions.txt	Logs all book borrow and return transactions
🧱 Classes Overview

Person – Base class containing common attributes (id, name)

User – Inherits from Person; includes password, role, and borrowed books

Book – Represents a single book’s details

Transaction – Tracks borrowing and returning of books

LibrarySystem – Main controller that handles login, menus, and file operations

🧠 Key Features

🔐 Login system with a 3-attempt limit

📖 Borrow and return books easily

📚 View all books in the library

🛠️ Admin mode for managing users, books, and transactions

💾 Automatic data saving to text files
