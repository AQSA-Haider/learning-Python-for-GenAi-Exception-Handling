Here I am practicing various Exception Handling methods:
## Task-6.1
# Safe Division utility
 Writing the program that:
 ~Takes two input from user-1.numerator,2.Dinominator.
 ~Uses try and except to handle:
 1.ValueError-if input is not a number.
 2.ZeroDivisionError-if denominator=0.
 3.no Error -prints the result.
 $.finally-prints "operation completed".
##  Task-6.2
# Bill Calculator with Error Handling
 given a list of all prices.
 Writing code that :
 iterates over the list
 tries to add onli valid numbers (positive numericals) prices to the 'total'.
 Handles:
 ~TypeError:if value is not a number.
 ~Custom Exceptionusing raise ValueError(Negetive price not allowed)
 prints the running total.
 Expected Behaviour was:
 Skips invalid items but continues processing.
## Task-6.3
# Custom Exception : Age validator
 A function check_age(age) has been created that:
 Raise a custom ValueError("age must be between 1 and 120)if age is out of range .
 Taking age input from the user as user_age
 using try-except the custom error message has been printed. 
 ## Task-6.4
# File Reader with Exception Handling
 Asking the user for a file name
 Trying to open and read the file
 Handle:
 ~FileNotFoundError
 ~PermissionError
 if successful prints first three line of the file
 Use finally to print:"file operation completed"
## Task-6.5
# Mini Project: Safe Shopping Cart
 Creating a program that has a cart list - cart[]
 runs a loop asking user to enter the price of the item .
 the loop stops when the user enters 'q'.
 Inside the loop:
 ~convert the input into float
 ~Handles ValueError if user enters invalid value.
 ~Raise custom exception if price is negetive.
 at the end:
 prints :1.Total items 2.Total bill.
 ## Task Completed!!!
