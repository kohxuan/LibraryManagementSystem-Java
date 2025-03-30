# 📚 Library Management System
The **Library Management System** is a Java-based application designed to manage library operations, including book management, borrower management, and borrowing records. This project provides a structured approach to handling library data and operations.
<br><br>

### ✨ Features
- **Book Management**: Manage book details such as title, author, genre, and availability.
- **eBook Management**: Handle eBooks with online access links.
- **Borrower Management**: Manage borrower information, including roles and fine transactions.
- **Borrowing Records**: Track borrowing and returning of books, with fine calculations for overdue returns.
- **User Authentication**: Supports login for librarians and borrowers with role-specific functionalities.
- **Graphical User Interface**: Utilizes `JOptionPane` for user interaction and management tasks.
<br>

### 🛠️ Technical Overview
- **Java**: Core programming language used for implementing library operations.
- **Vector**: Utilized for managing collections of books, borrowers, and borrowing records.
- **JOptionPane**: Provides a simple GUI for user interaction.
<br>

### 📁 File Structure
- **Book.java**: Defines the `Book` class with attributes and methods for managing book details and borrowing records.
- **BookFineTransaction.java**: Manages fine transactions with attributes for transaction ID, amount, and payment date.
- **BookSearching.java**: Provides functionality to search for books by title or ID.
- **Borrower.java**: Manages borrower details, including borrowing records and fine calculations.
- **BorrowingRecord.java**: Tracks borrowing and returning of books, including fine calculations for overdue returns.
- **Data.java**: Handles reading and filtering of user and book data from files.
- **Librarian.java**: Manages librarian details and operations.
- **Library.java**: Main program file containing the implementation of library operations and user interaction.
- **User.java**: Base class for user management, including login functionality.
- **eBook.java**: Extends `Book` to include eBook-specific attributes like online access links.
- **Books.txt**: Stores book data for the system.
- **Borrower.txt**: Stores borrower data for the system.
- **Librarian.txt**: Stores librarian data for the system.
- **eBook.txt**: Stores eBook data with access links.
<br>

### 🚀 Getting Started
1. **Compile the Program**: Use a Java compiler to compile the provided `.java` files.
2. **Run the Program**: Execute the compiled program to interact with the library management system.
3. **Manage Library**: Use the application to manage books, eBooks, borrowers, and borrowing records.
<br>
