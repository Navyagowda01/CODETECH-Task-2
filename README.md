Name: Navya G 
Company: CODETECH IT SOLUTUONS
ID:CT6WDS2456
Domain:Python Programming
Duration:November to January 2025
Mentor:Muzammil

![WhatsApp Image 2025-01-08 at 7 23 42 PM](https://github.com/user-attachments/assets/74901155-9ac7-40d0-902d-49cb518bfb00)


Overview of the project
Objectives:
The objective of this project is to create a Library Management System that allows users to perform various operations related to library items such as adding, checking out, returning, and searching for items (Books, Magazines, DVDs). It aims to:
 * Manage library items effectively.
 * Track whether an item is checked out or available.
 * Keep track of due dates and fines for overdue items.
 * Allow users to search for items by title, author, or category.
 * Provide a user-friendly interface for library management.

Key Activities:
 1. Defining the LibraryItem Class:
   Create the LibraryItem class with properties like title, author, category, item_type, is_checked_out, due_date, and fine.
    Implement methods for:
      * Checkout: To check out an item, calculate due date, and update status.
      * Return: To return an item and calculate late fees (if applicable).
      * Check for Overdue: To check if an item is overdue.
        
2. Defining the Library Class:
    Create the Library class to manage a collection of LibraryItem objects.
    Implement methods for:
      * Add item: Add new items to the library collection.
      * Checkout item: Handle item checkout by title.
      * Return item: Handle the return process of an item.
      * Search items: Search items based on different criteria (title, author, category).
      * Display items: Show the status of found items, such as availability or if they are checked out.
        
3. Implementing the User Interface:
    Create an interactive menu system that allows users to:
     * Add new items (book, magazine, DVD).
     * Checkout and return items.
     * Search for items based on title, author, or category.
     * Exit the system.
       
4. Handling User Input:
    * Ensure proper validation of user input (e.g., ensuring correct item type).
    * Manage operations for checking out and returning items, including overdue fine calculations.
      
5. Displaying Results:
    * Provide feedback and status updates on actions performed (e.g., successful checkout, overdue fines, item status).
      
6. Managing Due Dates and Fines:
   * Implement logic to calculate overdue fines based on the number of days an item is overdue, assuming a fine of $1 per day.

Technology Used:
  1. Programming Language: Python
      * Python is used due to its simplicity, readability, and robust support for object-oriented programming, making it ideal for building this library management system.
  2. Libraries/Modules:
      * datetime: Used for handling dates (to track due dates and overdue periods).
  3. Core Concepts:
      * Object-Oriented Programming (OOP): The use of classes (LibraryItem and Library) and objects helps organize and manage the library system efficiently.
        Inheritance, encapsulation, and method definition are key aspects of the design.
      * User Input Handling: The program prompts users for input and ensures correct processing based on choices.
      * Conditionals and Loops: Used for decision-making (e.g., checking if an item is overdue) and for creating an interactive menu system.
      * Error Handling: While not implemented explicitly in the code, error handling could be added to ensure robust input validation and exceptions (e.g., invalid item types).
    
        
This project demonstrates the implementation of a functional Library Management System with a focus on managing library items, tracking their status, and ensuring accurate fine calculations.





  



