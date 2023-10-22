# CS210

Summary: 
   This is a program that reads from a given text file containing a list of items for a grocer (one line per item). 
   It takes each item and adds it to a map, setting it's value to 1 if it did not already exist in the map, or increasing its value by 1 if it had.
   The user is given the options to print a list of items and their quantity numerically, or through a graph, as well as print the quantity of a specific item.
   
'What did you do particularly well':
   Minimizing the amount of data variables the GrocerStock class was something I was happy with.
   This kept the class succinct, needing fewer setters/getters, only needing functions to manipulate and print out the map.

'Where could you enhance your code?':
   The first area that comes to mind is having the code for the menu being put into its own class, as some of the functionality is repeated in Main.

'What were some difficulties?':
   The main difficulty I had was with trying to make the printed graph look aesthetically pleasing.
   To solve this, I used StackOverflow and some of the C++ documentation to look for padding functionality.

'Transferable skills?':
   This project dealt with reading data from a given file as well as a menu loop. Both are commonly experienced, with the knowledge of file manipulation being particularly helpful.

'How did you make this program maintainable/readable/adaptable':
   Having much of the functionality be inside of the GrocerStock class, as long as it is given the proper data, the class can be moved and used wherever needed.
   The nature of OOP also means that most changes done out and inside the class will likely have minimal impact outside of the changes themselves.
