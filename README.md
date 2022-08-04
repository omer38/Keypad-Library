# Keypad-Library
This is an Micropython library for using different keypads with Raspberry Pi Pico.

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
