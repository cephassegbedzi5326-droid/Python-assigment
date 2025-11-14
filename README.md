# Python-assigment
This repository contains my python programming assignments.
Project Overview

This project is a Python program designed to simulate a simple shopping checkout system. The program allows a user to input the quantities of various grocery items they wish to purchase, and then automatically calculates:

The cost of each item

The subtotal

A discount (if applicable)

The final total

A neatly formatted receipt

The program uses loops, user input, dictionaries, dictionary methods, string formatting, and basic arithmetic operations.

Features
1. Item Price Dictionary

A dictionary named Items_prices stores item names and their prices:

Items_prices = {"Bread": 25.00, "Milk": 18.00, "Eggs": 2.50, "Sugar": 5.00}

2. User Input for Quantities

A loop is used to ask the user how many of each item they want to buy.
The answers are stored in another dictionary called quantities.

3. Use of Dictionary Methods

The program uses the .items() method to loop through both item names and prices at the same time:

for item, price in Items_prices.items():


This makes the code cleaner and demonstrates knowledge of dictionary methods.

4. Subtotal Calculation

The program multiplies each item’s price by the quantity entered and adds the result to the running subtotal.

5. Discount Logic

A 10% discount is automatically applied if the subtotal exceeds 100 GHS.

6. Final Total

The final amount is calculated by subtracting the discount from the subtotal.

7. Formatted Receipt

The output includes a professional receipt showing:

Each item purchased

Quantity

Item total cost

Subtotal

Discount

Final amount to pay

String formatting (f"{value:.2f}") ensures prices always show two decimal places.

Example Output
----- RECEIPT ------
Bread (x2): GHS 50.00
Milk (x1): GHS 18.00
Eggs (x6): GHS 15.00
Sugar (x0): GHS 0.00
-------------------
Subtotal: GHS 83.00
Discount: GHS 0.00
Total: GHS 83.00

Concepts Demonstrated

This project demonstrates:

 Loops (for loop)
 User input handling (input())
 Converting strings to numbers (int)
 Dictionaries for storing prices and quantities
 Dictionary methods (.items())
 Arithmetic operations
 Conditional statements (if)
 Formatted printing (f-strings)
 Multi-step calculation logic
 Clean and structured output formatting

How to Run the Program

Save the Python script as receipt.py or any filename you prefer.

Run the script using:

python receipt.py


Enter the quantity for each item when asked.

The receipt will be printed automatically.
