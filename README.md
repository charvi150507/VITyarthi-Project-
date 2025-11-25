# VITyarthi-Project-
Project title 
Stationary Shop inventory. 

This project enables store owners or staff to effortlessly add new products, update inventory, verify prices or product availability, delete items, and access the full inventory—entirely through an easy, menu-based interface. This project demonstrates key Python concepts such as loops,. 


📌 Overview

This project is a simple Python-based inventory management system designed for a stationery store.
It allows the user to perform essential operations such as adding new items, checking availability, retrieving prices, updating stock, removing items, listing all items, and clearing the inventory.

The system is menu-driven, runs in the terminal, and uses a dictionary to store item details like name, price, and stock..

⭐ Features

➕ Add New Stationery Items (ID, name, price, stock)

🔍 Check Availability of an item using its ID

💰 Retrieve Item Price

📦 Update Stock (increase or decrease quantity)

❌ Remove Items from the inventory

📋 View Complete Inventory

🧹 Clear Entire Inventory

🔄 Looping Menu until user chooses to exit

Key Features
The system provides a full suite of basic retail inventory operations, structured around a simple menu:

* Item Creation and Maintenance (CRUD):

  Add a NEW item (Option 1): Allows entry of a unique ID, name, price, and initial stock.

  UPDATE the stock level (Option 4): Manages inventory changes by increasing stock (for deliveries) or safely decreasing stock (for sales), with validation to prevent stock from going   below zero.

  REMOVE an item (Option 5): Permanently deletes a specific product entry by its ID.

* Information and Reporting:

  Check AVAILABILITY (Option 2): Provides status updates based on stock levels (e.g., "Plenty in stock," "Running low," or "SOLD OUT").

  Check PRICE (Option 3): Retrieves and displays the price for a specified Item ID.

  VIEW all items (Option 6): Displays a neatly formatted table summarizing all products currently in the inventory.

* Safety and Usability:

  Input Validation: Uses try-except blocks to handle non-numeric or inappropriate input gracefully, preventing program crashes.

  CLEAR the entire inventory (Option 7): A high-risk operation requiring explicit text confirmation ('YES') to proceed.

* EXIT the system (Option 0): Terminates the program cleanly.


1. Python 3

The entire project is implemented using Python, chosen for its simplicity and readability.
Python provides:

Easy handling of user input

Built-in data structures like dictionaries

Dynamic typing for flexible data handling

Simple control flow (loops, conditionals)

2. Python Dictionaries

The inventory is stored using a nested dictionary structure:
Dictionaries are ideal because they allow:

Fast data lookup using item IDs

Easy updates to fields like price or stock

Clear key–value organization

3. Terminal / Command Line Interface (CLI)

Users interact with the program through a simple text-based menu displayed in the terminal.
The CLI approach ensures:

No external libraries needed

Smooth input/output flow

Easy testing and debugging

4. Basic Control Flow & Logic

The project uses:

while loops for repeating the menu

if-elif decision blocks for operations

Input validation through conditional checks
These form the core logic of the inventory system.

5. Optional Tools / Environment

(Not strictly required, but commonly used during development)

VS Code / PyCharm for writing and editing code

Python Interpreter / IDLE for running and testing

Git / GitHub if the project is version-controlled
🚀 Steps to Install & Run the Project

Install Python 3.x on your system.

Download or copy the project code into a file named inventory.py.

Open a terminal or command prompt.

Navigate to the folder where the file is saved.

Run the program using:

python inventory.py

Follow the on-screen menu to perform different operations.

🧪 Instructions for Testing

You can try the following cases to ensure everything works:

✔️ Test Case 1: Add New Item

Enter new ID: 110

Name: Marker

Price: 20

Stock: 50
Expected: Item appears in updated inventory.

✔️ Test Case 2: Check Availability

Input ID: 101
Expected: Shows "notebook" as available.

✔️ Test Case 3: Update Stock

Choose “Increase stock”

ID: 102

Add quantity: 10
Expected: New stock = 50

✔️ Test Case 4: Remove Item

Remove ID: 105
Expected: Item removed successfully.

✔️ Test Case 5: Clear Entire Inventory

Choose option 7
Expected: Inventory becomes {}

🖼️ Screenshots (Optional)

You can add screenshots like:

Program startup screen

Menu display

Sample output after operations

Screenshots 

<img width="774" height="152" alt="image" src="https://github.com/user-attachments/assets/bd991f8c-6f20-4a81-9e9b-940d9c99f1c9" />

<img width="896" height="164" alt="image" src="https://github.com/user-attachments/assets/a5bccc1f-7b64-4e45-8327-6d0873144ed1" />
<img width="216" height="79" alt="image" src="https://github.com/user-attachments/assets/257dfe04-7d3b-4db3-b409-7864d0d7bb11" />
<img width="221" height="73" alt="image" src="https://github.com/user-attachments/assets/86258340-1097-42aa-ab0f-1601a60565de" />
<img width="239" height="136" alt="image" src="https://github.com/user-attachments/assets/0a7aacf0-bc77-4d95-8e9b-85e7d1230b0f" />
<img width="897" height="132" alt="image" src="https://github.com/user-attachments/assets/1a25bef1-fa1f-4810-89a9-1b95b171e966" />
<img width="308" height="152" alt="image" src="https://github.com/user-attachments/assets/0580be22-b06d-4a75-bf04-a17e112e0a3e" />
<img width="226" height="75" alt="image" src="https://github.com/user-attachments/assets/052b9fa8-f426-423e-9849-7c2b7ec3aa84" />








