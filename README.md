# Customer Banking System

## Project Overview
This program is tasked to calculate users' interest earned on their Savings and CD accounts. By inputting information on account balance, APR, and length of months in each account, you'll be given an estimated number on how much interest you'll earn and how much your balance will be updated with the interest.

## Installation Instructions
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/ezwang8/customer_banking.git
   ```
2. **Check to make sure Python is installed on your system.**
   Open your system's terminal and type the following command:

   ```bash
   python --version
   ```

   Depending on the system, use instead:

   ```bash
   python3 --version
   ```

   The command will display `Python 3.x.x` if Python 3.x is installed. If not, you can download it in the website: [python.org](https://www.python.org/downloads/).

3. **Navigate to the Project Directory:**
   ```bash
   cd customer_banking
   ```
4. **Run the Python Script:**
   Run the script, in your system's installed Python application, with:
   ```bash
   python customer_banking.py
   ```

## File Roles

- **`customer_banking.py`**: The main script that runs the program. It handles user input, calls the appropriate functions from the other files, and displays the final output to the user.

- **`savings_account.py`**: Defines the `create_savings_account` function. It's used to calculate the interest earned on the Savings account and updates the account balance.

- **`cd_account.py`**: Defines the `create_cd_account` function. It performs similar calculations from the `savings_account.py`, but for the CD account.

- **`Account.py`**: Contains the `Account` class. It's a foundation for the Savings and CD accounts by defining methods to set and retrieve balances and interest.

**Note**: `customer_banking.py` can only run if the other three dependency files are present. All four files must be in the same folder/directory for the program to work. Follow the steps in the **Installation Instructions** to ensure that `customer_banking.py` runs successfully.

## Usage Instructions
- **Start On Savings Account:**
  The program starts with the Savings account. You'll be asked to input your current Savings account balance.
  
- **Savings APR and Months:**
  To finish calculating the Savings' interest rate, you'll also be asked to input the Savings account's APR and length of months.
  
- **Savings Interest Calculated:**
  The program will use the Savings account information to calculate the interest it'll earn and what your updated balance will become.
  
- **Continue On CD Account:**
  The program continues with the CD account. You'll be asked to input your current CD account balance.

- **CD's APR and Months:**
  To finish calculating the CD interest rate, you'll also be asked to input the CD account's APR and length of months.
  
- **CD Interest Calculated:**
  The program finishes by using the CD account information to calculate the interest it'll earn and what your updated balance will become.

## Output Values

After running the program and inputting your values, the following key output values will be displayed for your Savings and CD accounts:

- **Interest Earned**: The amount of interest your account had accumulated. A higher initial acccount balance, APR (Annual Percentage Rate), and length of time (in months) would earn you more interest.

- **Updated Balance**: Your account's new balance after being added by the interest earned. It shows how much money your account earned after the calculated interest is applied.

## Example
```
What is your savings account balance? 1000
What is the APR for the savings account? 5
What is the length of months for the savings account? 12

Savings Account: Interest Earned: $50.00
Savings Account: Updated Balance: $1050.00

------------------------------------------------

What is your initial CD account balance? 1000
What is the APR for the CD account? 5
What is the length of months for your CD? 12

CD Account: Interest Earned: $50.00
CD Account: Updated Balance: $1050.00
```
