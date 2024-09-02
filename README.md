# Customer Banking System

## Project Overview
This project allows users to calculate the interest they'll earn on savings and CD accounts. By inputting information on account balance, APR, and length of months in each account, you'll be given an estimated number on how much interest you'll and what your updated balance would become with the addition of the earned interest.

## Installation Instructions
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/ezwang8/python-challenge-1.git
   ```
2. **Navigate to the Project Directory:**
   ```bash
   cd python-challenge-1
   ```
3. **Run the Python Script:**
   Run the script, in your system's installed Python application, with:
   ```bash
   python menu.py
   ```

## Usage Instructions
- **Start the Program:**
  You'll be given a menu to select from 4 categories. Snacks, Meals, Drinks, and Desserts.
  
- **Navigating the Menu:**
  Type a number that represents the menu category you'd like to choose.
  
- **Placing an Order:**
  - Type the item's number to select it.
  - Type the amount of that item you'd like to buy.
  
- **Continue Ordering or Complete Order:**
  - You'll be given 2 options after completing your order. Press 'Y' to make another order or 'N' to finish ordering.
  
- **Receipt:**
  A receipt will be given to you. It show each item you ordered, the item's price, the quantity of that item you've purchased, and the total cost of all of your order(s).

## Works Cited

- **GeeksforGeeks - Convert String to Integer in Python**  
  **Link**: [GeeksforGeeks: Convert String to Integer in Python](https://www.geeksforgeeks.org/convert-string-to-integer-in-python/)  
  **Concepts Used**: This website talks about converting strings into integers.
  
  **Instances**:
  - **Problem 3**: Converting the menu_selection to an integer.
  - **Problem 4**: Converting the quantity to an integer after checking if it's a number.

- **GeeksforGeeks - Conditional Statements in Python**  
  **Link**: [GeeksforGeeks: Conditional Statements in Python](https://www.geeksforgeeks.org/conditional-statements-in-python/)  
  **Concepts Used**: Explains the basic applications of if/else statements, and what would happen in either of those cases.
  
  **Instances**:
  - **Problem 4**: Setting the default quantity to 1 if the customer didn't put a valid number.

- **Codefather - Add Item to List in Python**  
  **Link**: [Codefather: Add Item to List in Python](https://codefather.tech/blog/add-item-to-list-python/)  
  **Concepts Used**: Explains how to append multiple items to a list.
  
  **Instances**:
  - **Problem 4**: Appending the customer's order to the order list.

- **Python Documentation - Formatted String Literals**  
  **Link**: [Python Documentation: Formatted String Literals](https://docs.python.org/3/tutorial/inputoutput.html#formatted-string-literals)  
  **Concepts Used**: Explains how f-strings work and how to use them for formatting.
  
  **Instances**:
  - **Problem 5**: Formatting the item price and total price in the receipt.
  - **Problem 8**: Formatting the price in price_spaces.
  - **Problem 10**: Formatting the order details.
  - **Problem 11**: Formatting the total cost of the order.
