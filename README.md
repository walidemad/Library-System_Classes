# Library System - Classes
Refactor the Library System using JavaScript Classes based on the previous implementation that used Functional Object constructors.  
This task involves using the concept of classes to create objects with a similar structure and functionality as the previously implemented functional constructor objects.   
The goal is to create a more efficient, modular, and scalable system by utilizing the features of classes.

##  Instructions:
Here's of what the Library System should have using classes: 

- The `Library` class should have a "name" and "books" properties.

- The `Library` class should have the following methods:  
  `addBook()`, `removeBook()`, `checkInBook()`, `checkOutBook()`, `getBookById()`.

- The `Patron` class should store the patron's "name" and "id".

- The `Book` class should store the book's "title", "author", "id", it should also have a "status" property to keep track of whether the book is checked out or not.

- The `BookStatus` class should store if the book is "checkedOut" (`boolean` and the default is `false`) and the patron (default is `null`)

## Bouns Task
Create a new method within the `Library` class called `getCheckedOutBooks()`.  
This method should return an array of objects that include the "bookTitle" and "patronName" for every book that is currently checked out.