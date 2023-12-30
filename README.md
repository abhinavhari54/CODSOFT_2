# CODSOFT_2
# ATM Interface
# Description:

The ATM Interface project is a simple banking system developed in Java using the NetBeans IDE 20. It emulates the functionality of an Automated Teller Machine (ATM) by providing users with options to perform common banking transactions. The project consists of two main classes: BankAccount and ATM.

# BankAccount Class:

The BankAccount class represents an individual bank account with a private balance attribute.
It includes a constructor to initialize the account with an initial balance.
Public methods getBalance, deposit, and withdraw allow users to check their balance, deposit funds, and withdraw funds, respectively.
Input validation is applied to ensure that deposit and withdrawal amounts are valid.

# ATM Class:

The ATM class acts as an interface for users to interact with their bank account.
It takes a BankAccount object as a parameter during instantiation, linking the ATM to a specific user account.
The class provides a menu of options through the displayOptions method, including cash withdrawal, cash deposit, balance inquiry, and exiting the system.
Methods such as withdraw, deposit, and checkBalance are responsible for handling user inputs and performing the corresponding actions.
The start method initiates an interactive session, continuously prompting the user for their choice until they decide to exit.

# Main Class (AtmMachine):

The AtmMachine class contains the main method, serving as the entry point for the application.
It creates an instance of the BankAccount class with an initial balance of 1000 and passes it to the ATM constructor.
The ATM session is then started using the start method of the ATM class.

# Development Environment:

The project is developed using the Java programming language.
NetBeans IDE 20 is utilized as the integrated development environment for coding, debugging, and managing the project.

# Usage:

Users can run the program to simulate an ATM session, selecting options to withdraw cash, deposit funds, check their balance, or exit the system.
The project demonstrates fundamental principles of object-oriented programming, encapsulation, and user interaction in a console-based application.
