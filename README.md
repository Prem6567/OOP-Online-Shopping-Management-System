🛒 OOP Online Shopping Management System

📌 Project Overview

The Online Shopping Management System is a console-based Java application developed using Object-Oriented Programming (OOP) principles. It allows users to browse products, add items to a shopping cart, calculate the total price, validate product stock, and complete the checkout process.

This project demonstrates the practical implementation of Java programming concepts and basic e-commerce functionality.

🎯 Features

- Product Listing: Display available products with their prices and stock.
- Shopping Cart: Add products and specify quantities.
- Price Calculation: Automatically calculate the total cost of products.
- Stock Validation: Prevent purchases exceeding available inventory.
- Order Checkout: Confirm orders and update product stock.
- Input Validation: Handle invalid menu choices and incorrect inputs.
- Product Categories: Organize products into Electronics and Clothing.
- Interactive Menu: Navigate the system through a simple console interface.

🛠️ Technologies Used

- Programming Language: Java
- Core Concepts: Object-Oriented Programming
- Data Structures: ArrayList
- Input Handling: Scanner
- Application Type: Console-Based Application

🧠 OOP Concepts Implemented

1. Encapsulation

Uses private fields and public getter methods to control access to product information.

2. Inheritance

The "Electronics" and "Clothing" classes inherit properties and methods from the "Product" class.

3. Abstraction

The abstract "Product" class defines a common structure for different product categories.

4. Polymorphism

The "getCategory()" method is overridden in the "Electronics" and "Clothing" classes to provide category-specific behavior.

📂 Project Structure

OOP-Online-Shopping-Management-System/
│
├── Main.java
└── README.md

▶️ How to Run the Project

Step 1: Install Java

Install the Java Development Kit (JDK) on your computer.

Step 2: Download the Project

Clone the repository or download the source code from GitHub.

Step 3: Compile the Program

Open a terminal in the project directory and run:

javac Main.java

Step 4: Execute the Program

java Main

🛍️ Sample Products

Product ID| Product Name| Category| Price (INR)
101| Laptop| Electronics| 55,000.00
102| Headphones| Electronics| 1,500.00
103| T-Shirt| Clothing| 499.00
104| Jeans| Clothing| 999.00

Product prices and inventory are predefined for demonstration purposes.

📋 Available Operations

1. View All Products
2. Add Product to Cart
3. View Shopping Cart
4. Checkout
5. Exit

🎓 Learning Outcomes

By developing this project, learners can gain practical experience with:

- Java classes and objects
- Constructors and access modifiers
- Abstract classes and method overriding
- Inheritance and polymorphism
- ArrayList collections
- Loops and conditional statements
- User input validation
- Basic inventory and shopping cart logic

🔮 Future Improvements

The project can be extended with:

- User registration and login
- Product search and filtering
- Multiple payment methods
- Order history and tracking
- Database integration using JDBC
- Graphical user interface
- Discounts, coupons, and tax calculation

👨‍💻 Author

prem

📄 License

This project is intended for educational and portfolio purposes. Add an appropriate open-source license if you intend to distribute it under specific reuse terms.

---

Note: This is a learning project that demonstrates basic online shopping functionality. It does not include real payment processing, user authentication, or database persistence.
