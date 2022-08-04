# Keypad-Library
This is an Micropython library for using different keypads with Raspberry Pi Pico.

Written By Ömer Tuğrul, 04.08.2022 

# Documentation
This library contains two different classes.

* Keypad Class :
    * __init__(row_size, column_size, pin_list, keys):
    
          row_size: row number of the keypad. 
          column_size : write the column number of the keypad.  
          pin_list: write all the pins that will be used in a list. 
          keys: write all keys in nested format. 
     
    * print_key_pressed() : This function prints the button that pressed on the keypad.
   
    * hex_integer_key_pressed(): This function returns the integer value of the button that pressed.
    
* Calculator Class :
   Their initializations are same.
   * __init__(row_size, column_size, pin_list, keys):
    
          row_size: row number of the keypad. 
          column_size : write the column number of the keypad.  
          pin_list: write all the pins that will be used in a list. 
          keys: write all keys in nested format. 
          
   * hex_integer_key_pressed(): This function returns the integer value of the button that pressed.
   
   * press_until_square(): This function returns the integer value of the number that has been pressed until square button on keypad.
   * calculate(): This function initializes a calculator and wants two input number from the user. Then it does the operation according to the given values.
                  In my keypad, A is summation, B is subtraction, C is multiplication, D is division operation.
