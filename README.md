# Printing Machine With C
## Introduction
  * It creates a animated printing of the name or string the user entered in the terminal.

## Running The File
  * Copy the code in main.c to any of the C compiler in your device.
  * Compile the code.
  * Run it.
 
## How It Works
  * The pattern for every letters are predefined in the function named *setArray()*
  * When a string in inserted, an 2-D array is created for all the 7 lines which says where all the symbol should be printed inorder to get the required word.
  * Printing is taken place according to the array that we created earlier.
  * To get the animation *usleep()* function from unistd is used for delaying each printing operation.
  
## Output
  ![This is the output](/Sample_Output.png)
