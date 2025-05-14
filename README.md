📦 Customer Billing System (C Project)This is a Customer Billing System built using the C programming language. It allows users to:

Add new customers
View existing records
Search for a customer by ID
Each customer's bill is calculated based on electricity units consumed, using a tiered pricing system.

✅ Features
Add customer billing information (ID, name, units consumed)

Automatically calculate electricity bill based on units

View all customer records

Search for a customer by ID

Store data using file handling (bills.txt)

📁 File Structure
├── customer.h         // Header file with struct and function declarations
├── customer.c         // Function definitions
├── main.c             // Main application logic and menu
├── bills.txt          // Data file where customer records are stored
├── README.md          // Project description (this file)

💡 Bill Calculation Logic
First 100 units: ₹0.75 per unit

Next 200 units (101-300): ₹1.50 per unit

Next 200 units (301-500): ₹1.85 per unit

Above 500 units: ₹2.50 per unit

▶️ How to Compile and Run
-On Windows (Command Prompt or Terminal)
gcc -o billing_system main.c customer.c
.\billing_system.exe
-On Linux/macOS
gcc -o billing_system main.c customer.c
./billing_system

🔧 Sample Menu
===== Customer Billing System =====
1. Add Customer
2. View All Customers
3. Search Customer by ID
4. Exit
Enter your choice:
