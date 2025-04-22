Loan Calculator Project Description

This project is a graphical loan calculator application built with Python using the Tkinter library. The application provides a user-friendly interface for calculating loan payments based on user inputs.

Features
- Calculate monthly and total loan payments
- Input fields for:
  - Loan amount
  - Interest rate (annual percentage)
  - Loan term (in years)
- Automatic calculation with a single button click
- Clear display of results in the same window

Technical Implementation
The application is implemented as a Python class `LoanCalculator` which:
- Creates a Tkinter window with appropriate labels and entry fields
- Handles user input via StringVar objects
- Performs financial calculations using standard loan formulas
- Updates the display with calculated monthly and total payments
- Formats currency values properly with 2 decimal places

The calculator uses the standard mortgage/loan formula to compute monthly payments based on principal, interest rate, and loan term.

Usage
Users simply enter their loan details (amount, interest rate, and term), click the "Calculate" button, and instantly see their monthly payment obligation and the total amount they will pay over the life of the loan.

This tool can help users make informed financial decisions by quickly estimating loan payments for different scenarios.
