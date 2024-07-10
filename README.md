Importing Libraries: We import the Scanner class for input handling.

Main Class and Methods:

We define the SimpleBankingApplication class.
We declare a static variable balance to keep track of the account balance.
Main Method:

We create a Scanner object for user input.
We use a while loop to display the menu and handle user choices until the user decides to exit.
Switch Case for Menu Options:

Check Balance: Calls the checkBalance() method to display the current balance.
Deposit: Calls the deposit() method to add funds to the balance.
Withdraw: Calls the withdraw() method to subtract funds from the balance.
Exit: Sets the exit flag to true to terminate the loop and exit the application.
Methods:

checkBalance(): Displays the current balance.
deposit(Scanner scanner): Prompts the user to enter a deposit amount and updates the balance if the amount is valid.
withdraw(Scanner scanner): Prompts the user to enter a withdrawal amount and updates the balance if the amount is valid and there are sufficient funds.
