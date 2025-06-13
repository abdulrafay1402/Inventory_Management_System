# Inventory Management System 📦

## 📌 Overview
The **Inventory Management System** is a C-based console application that helps businesses efficiently manage their inventory. It includes features like **user authentication, product management, sales tracking, sorting, restocking alerts, and file-based data storage**. This system ensures smooth inventory tracking and stock management, making it an essential tool for small businesses.

## 🚀 Features
- **User Authentication**: Secure login and registration system.
- **Product Management**: Add, update, delete, and search for products.
- **Sales Tracking**: Track and update sold products.
- **Sorting**: Sort products based on name, price, or quantity.
- **Restocking Alerts**: Identifies products that need restocking (quantity < 10).
- **File Handling**: Persistent storage using text files.
- **Interactive UI**: Colored console output for better readability.
- **Error Handling**: Validates user inputs to prevent errors.

## 🛠 Technologies Used
- **Programming Language**: C
- **File Handling**: Text files for data storage
- **Windows Console API**: Colored text output for better UI

## 🔧 Installation & Usage
### 1️⃣ Compilation
Compile the program using GCC:
```bash
gcc C_inventoryManagementSystem.c -o inventory.exe
```

### 2️⃣ Running the Program
Run the compiled executable:
```bash
./inventory.exe
```

### 3️⃣ User Authentication
- **New Users**: Register an account (username & password are stored in `users.txt`).
- **Existing Users**: Login to access their personalized inventory.

### 4️⃣ Features & Functionality
- **Adding a Product**: Input product details (ID, name, price, quantity).
- **Displaying Products**: View all inventory items.
- **Updating Products**: Modify name, price, or quantity.
- **Deleting Products**: Remove items from inventory.
- **Searching for Products**: Retrieve product details by ID.
- **Sorting Inventory**: Arrange items by price, quantity, or name.
- **Tracking Sold Products**: Update stock when items are sold.
- **Restocking Alerts**: Identify low-stock items for replenishment.

## 📸 Sample Test Cases
### 1️⃣ Registering & Logging In
User registers and logs into the system.

### 2️⃣ Adding & Displaying Products
Products are added and displayed in a structured format.

### 3️⃣ Deleting & Updating Products
Selected items are deleted or modified successfully.

### 4️⃣ Searching & Sorting Inventory
Products are searched by ID, and inventory is sorted based on user preference.

### 5️⃣ Tracking Sales & Restocking
Sold products are deducted from stock, and restocking alerts are displayed.

## 🎯 Future Improvements
- Implement a graphical user interface (GUI).
- Add database integration for better scalability.
- Implement multi-user access with different roles (Admin & User).

## 📝 Authors & Collaborators
- **Abdul rafay**  
- **Bisma**  
- **Afshal**  
- **Hussain Bin Inam**  
##📧 Contact:
- [abdulrafay14021997@gmail.com]


