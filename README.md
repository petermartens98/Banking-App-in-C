# Banking-App-in-C
This code is a simple banking app that allows users to deposit, withdraw, and check their account balance. 
It uses a struct to store the user's account number and balance. The program prompts the user to enter 
an account number and initial balance, and then displays a menu with options for depositing money, withdrawing money,
checking the account balance, and quitting the program.

The program uses three helper functions to format and parse monetary values and to handle the deposit and withdrawal functionality.
 The format_money function takes a float amount and returns a string formatted as a money value. The parse_money function takes a 
 string input and a pointer to a float amount and sets the amount to the parsed value of the input. The deposit and withdraw functions
  prompt the user for an amount to deposit or withdraw, parse it using the parse_money function, and add or subtract the amount from the user's balance.

The program uses a do-while loop to repeatedly display the menu and execute the corresponding function based on the user's input.
 The loop continues indefinitely until the user chooses the option to quit the program. 
 The program uses standard input and output functions, including scanf, printf, and fgets.

##Sample Output:
![image](https://user-images.githubusercontent.com/87671757/221430183-4cb37989-fbac-4d2e-a2f1-4fcd594f3798.png)
