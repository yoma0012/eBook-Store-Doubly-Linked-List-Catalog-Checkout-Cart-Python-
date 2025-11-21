# eBook Store – Doubly Linked List Catalog & Checkout Cart (Python)

This project is a console-based **eBook store system** implemented in Python.  
It uses a **doubly linked list** to manage the book catalog and a **stack-based checkout cart** for simulating basic e-commerce cart operations.

The application allows users to add, search, and remove books from the catalog, as well as add books to a checkout cart, remove from the cart, and view cart details.

---

## 🚀 Features

### 📚 Book Catalog (Doubly Linked List)
- Store books using a custom `BookNode` class
- Maintain a doubly linked list of books
- Add books with:
  - ISBN
  - Title
  - Author
  - Price
- Prevent duplicate ISBN entries
- Search books by:
  - Author
  - Title
  - ISBN
- Remove books from catalog by ISBN
- Display the entire book catalog in order

### 🛒 Checkout Cart (Stack)
- Stack-based `CheckoutCart` implementation
- Add book titles to cart
- Remove (pop) the most recently added book
- Peek at the top item in the cart
- Display current cart size
- Check if the cart is empty

### 🧾 Menu-Driven Console UI
- Text-based menu for all operations:
  1. Add Book to Catalog  
  2. Display Catalog  
  3. Search Books by Author  
  4. Search Books by Title  
  5. Search Book by ISBN  
  6. Remove Book by ISBN  
  7. Add Book to Checkout Cart  
  8. Remove Book from Cart  
  9. Peek Cart  
  10. Display Cart Size  
  11. Exit Program  

---

## 🧰 Technologies & Concepts Used

- **Language:** Python
- **Data Structures:**
  - Doubly Linked List (`BookNode` and catalog list)
  - Stack (for checkout cart)
- **Concepts:**
  - Object-Oriented Programming (OOP)
  - Custom data structures
  - Menu-driven console application
  - Basic input validation

---

## 🔧 How to Run

1. Clone the repository
2. Run 
