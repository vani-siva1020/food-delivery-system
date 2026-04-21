🍔 Food Delivery System (Java Console Application)
📌 Overview

This is a simple Food Delivery System developed using Java.
It is a console-based application that allows users to:

Create an account
Login securely
Browse food menu
Place orders
View transaction history
Track delivery status

This project demonstrates basic concepts of Object-Oriented Programming (OOP) and Java collections.

🚀 Features
👤 User Account Creation & Login Authentication
🍽️ Food Menu with Categories (Veg, Non-Veg, Beverage, Dessert)
❌ Availability Check for Food Items
🛒 Order Placement System
💰 Automatic Bill Calculation
📜 Transaction History Tracking
🚚 Delivery Status Update
🔐 Simple Approval System for High-Value Orders
🛠️ Technologies Used
Java
OOP Concepts (Classes, Objects, Constructors)
Collections Framework (ArrayList)
Scanner (User Input Handling)
🧩 Project Structure
Food Delivery System
│
├── Customer Class   → Stores user details
├── Food Class       → Stores food item details
├── Order Class      → Handles order and total calculation
├── Delivery Class   → Tracks delivery status
└── Main Class       → Controls program flow
⚙️ How It Works
User creates an account with ID, name, and password
User logs into the system
Menu is displayed with available food items
User selects items to add to order
System calculates total amount
If total > 5000 → Approval required
Order is processed and delivery status is shown
Transaction history is displayed
📸 Sample Output
Login Successful!

--- MENU ---
1. Paneer (Veg) - 200
2. Chicken (Non-Veg) - 300
3. Juice (Beverage) - 100
4. IceCream (Dessert) - 150 [Not Available]

Added!
Added!
Item not available!

Total Amount: 600
Order Approved!
Delivery Status: Dispatched
🎯 Learning Outcomes
Understanding of Java OOP concepts
Working with lists and collections
Handling user input
Building menu-driven applications
Implementing basic real-world logic
🔮 Future Enhancements
Multiple user accounts
Admin panel
Database integration (MySQL)
GUI using JavaFX / Swing
Online payment integration
Real-time order tracking
📌 Conclusion

This project is a beginner-friendly implementation of a real-world food ordering system, useful for learning Java fundamentals and improving logical thinking.
OUTPUT: 
--- MAIN MENU ---
1. Create Account
2. Login
3. Exit
Enter choice: 1

Enter ID: 101
Enter Name: Shri
Set Password: 1234
Account Created!

--- MAIN MENU ---
1. Create Account
2. Login
3. Exit
Enter choice: 2

Enter ID: 101
Enter Password: 1234
Login Successful!

--- MENU ---
1. Paneer (Veg) - 200
2. Chicken (Non-Veg) - 300
3. Juice (Beverage) - 100
4. IceCream (Dessert) - 150 [Not Available]
5. Finish Order
Choose item: 1
Added!

--- MENU ---
Choose item: 2
Added!

--- MENU ---
Choose item: 4
Item not available!

--- MENU ---
Choose item: 3
Added!

--- MENU ---
Choose item: 5

Total Amount: 600
Order Approved!

Delivery Status: Dispatched

Transaction History:
Added: Paneer
Added: Chicken
Added: Juice

--- MAIN MENU ---
1. Create Account
2. Login
3. Exit
Enter choice: 3

Exit...
