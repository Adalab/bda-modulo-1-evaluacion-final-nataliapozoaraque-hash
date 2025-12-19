# Inventory Management System

Author: Natalia Pozo
Bootcamp: Adalab - Data Analytics (Module 1: Python)

📝 Description

This is the final project for Module 1. Basically, it's a Python system to manage a store's inventory, clients, and sales. The goal was to put into practice everything learned over these weeks: functions, loops, flow control, and data structures (lists and dictionaries), simulating how a real store's logic would work behind the scenes.

✨ Features

The code is organized into three clear parts to make it easy to follow:

1. Data Structures

Here I define the main variables used by the program: inventory (a list of dictionaries), clients, and total_sales.

2. Functions (Store Management)

This is where all the logic lives. I created separate functions for each action:

Product Management:

Add products (validating that the price is a number and normalizing the name).

Update stock (controlling that stock cannot go negative).

Remove products safely.

Visibility & Search:

View the inventory with a readable format (currency, separators).

Search for products regardless of whether you use uppercase or lowercase.

I used .get() to prevent errors if data is missing.

Sales Simulation:

The process_purchase function uses a while loop to act like a cash register: it asks for products, checks stock, adds them to the cart, and prints the final receipt.

Calculations:

Calculate the total accumulated value of the inventory.

3. Test Area

At the end of the script, there is a sequential execution block. It cleans the environment, adds test data, and runs the functions one by one to verify everything works correctly before starting to sell.

🛠️ What I Applied

Data Structures: Handling nested Lists and Dictionaries.

Flow Control: Using for loops to iterate through data and while loops for interactivity.

Error Handling: try-except blocks so the program doesn't crash if the user enters incorrect data.

Best Practices:

Data cleaning (.lower(), .strip()).

Defensive programming (checking types with isinstance).

Modular code (each function does one thing).

📂 Project Structure

inventory_management.ipynb: The main notebook containing all the code.

README.md: This documentation.

🚀 How to Run It

Clone the repository.

Open inventory_management.ipynb in VS Code or Jupyter Notebook.

Run the cells in order to initialize the system.

Go to the "Test Area" section at the bottom to see the functions in action, or uncomment the make_purchase() line to try the interactive purchase yourself.
