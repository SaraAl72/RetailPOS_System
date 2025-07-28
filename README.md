# RetailPOS_System

A C++ based Point-of-Sale (POS) system for managing product inventory in a convenience store setting. This project was created for an academic course (CSC 2110 - Summer 2025) and demonstrates object-oriented programming concepts such as inheritance, polymorphism, and file I/O.

## Features

- Load and manage inventory from a file
- Categorize products (e.g., Soda, Chocolate, Tobacco, LotteryTickets)
- Search products by name, category, or price range
- Add and remove inventory items
- Sell products and calculate total cost
- Handle errors and edge cases (e.g., selling out-of-stock products)
- Apply taxes using inheritance and polymorphism

## Technologies Used

- C++
- File I/O
- Inheritance & Polymorphism
- Exception handling
- Object-oriented design

## Product Categories

- **Tobacco** - Includes special tax
- **LotteryTickets** - Includes both city and county taxes

## File Structure

- `main.cpp`: Menu interface and main driver
- `Product.h/cpp`: Base class for products
- `Tobacco.h/cpp`: Derived class with special tax logic
- `LotteryTickets.h/cpp`: Derived class with dual tax logic
- `Inventory.h/cpp`: Manages the product list and operations
- `Inventory.txt`: Sample inventory file

## How to Run

1. Open the project in a C++ IDE (Visual Studio recommended)
2. Make sure all `.cpp` and `.h` files are included
3. Build and run `main.cpp`
4. Follow the on-screen menu to test each feature

## Example Menu

```
1. Search Inventory
2. Sell Products
3. Add New Inventory
4. Remove Inventory
5. Exit
```

Author: Sara Al-Hachami  
Course:CSC 2110 – Programming Project 3  
Term: Winter 2025
