# calculator-using-Tkinter

+ The code provided is a simple calculator program implemented using Python's tkinter module. It allows the user to input numerical values and perform basic arithmetic operations such as addition, subtraction, multiplication, and division.

  - The program can be broken down into the following steps:
   1. Import the tkinter module and create an empty string variable called 'expression' that will store the user's input.
   2. Define a function called 'input_number' that takes in two parameters - 'number' and 'equation' - and updates the 'expression' variable by concatenating the input number to it. It also updates the 'equation' variable to display the current expression.
   3. Define a function called 'clear_input_field' that takes in the 'equation' parameter and resets the 'expression' variable to an empty string. It also updates the 'equation' variable to display a placeholder message.
   4. Define a function called 'evaluate' that takes in the 'equation' parameter and attempts to evaluate the current 'expression' variable using the 'eval' function. If the evaluation is successful, it updates the 'equation' variable with the result and resets the 'expression' variable to an empty string. If the evaluation fails, it updates the 'equation' variable to display an error message and resets the 'expression' variable to an empty string.
   5. Define the 'main' function that creates the tkinter window, sets its title and dimensions, and instantiates a 'StringVar' variable called 'equation' that will be used to display the user's input and output.
   6. Create an input field widget using the 'Entry' function and assign it to the 'input_field' variable. Set its textvariable to 'equation' and place it on the GUI using the 'grid' function.
   7. Set the initial value of the 'equation' variable to a placeholder message.
   8. Create 10 number buttons (from 0 to 9) using the 'Button' function and assign them to variables named '_0', '_1', '_2', ..., '_9'. Set their text to the corresponding number and their command to call the 'input_number' function with the appropriate number and 'equation' parameters. Place them on the GUI using the 'grid' function.
   9. Create four operation buttons for addition, subtraction, multiplication, and division. Set their text to '+', '-', '*', and '/', respectively, and their command to call the 'input_number' function with the appropriate operation symbol and 'equation' parameters. Place them on the GUI using the 'grid' function.
   10. Create an 'equal' button with text '=' and command to call the 'evaluate' function with the 'equation' parameter. Place it on the GUI using the 'grid' function.
   11. Create a 'clear' button with text 'Clear' and command to call the 'clear_input_field' function with the 'equation' parameter. Place it on the GUI using the 'grid' function.
   12. Call the 'mainloop' function to display the GUI and start the program.
