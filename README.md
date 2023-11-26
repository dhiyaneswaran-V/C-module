# C Library Management System

This C program implements a simple library management system that allows users to add books, view added books, issue books, view issued books, return books, and exit the system.

## Table of Contents

1. [Overview](#overview)
2. [Usage](#usage)
3. [Functionality](#functionality)
   - [1. Add Book](#1-add-book)
   - [2. View Added Books](#2-view-added-books)
   - [3. Issue Book](#3-issue-book)
   - [4. View Issued Books](#4-view-issued-books)
   - [5. Return Book](#5-return-book)
   - [6. Exit](#6-exit)

## Overview

The program uses a structure `book` to represent each book in the library, storing information such as the book's name, issuer, number, and status. Users can perform various operations related to book management through a menu-driven interface.

## Usage

1. Compile the program using a C compiler.
2. Run the compiled executable.
3. Follow the on-screen instructions to navigate through the menu and perform operations.

## Functionality

### 1. Add Book

- Users can add a new book to the library.
- Enter the name of the book, and the program assigns a unique number to it.
- The book is initially marked as available.

### 2. View Added Books

- Displays a list of all added books with their respective numbers, names, issuers, and availability status.

### 3. Issue Book

- Users can issue a book by entering the book's name.
- If the book is available, users must provide the name of the person issuing the book.
- The book's status is changed to "not available."

### 4. View Issued Books

- Displays a list of issued books with their numbers, names, and issuers.

### 5. Return Book

- Users can return a book by entering the book's number.
- The book's issuer is set to an empty string, and the book's status is changed to "available."

### 6. Exit

- Terminates the program.

Feel free to explore and modify the code to suit your specific requirements. This program serves as a basic foundation for a library management system and can be extended to include more features.
