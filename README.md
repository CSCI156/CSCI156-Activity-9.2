### Writing/Reading from a file part 2

Here is the 9.1 assignment:

1. Write a while loop with an input statement inside the loop. Define a (single) string that stores all of the inputs by appending the current input to any previous inputs. Exit the loop when the user enters q (or Q). After the loop exits write the output to a file. Use f = open(...) to open the file

2. Rewrite your loop to count how many lines the user inputs. Use the count to read in and print out the contents of the file using readlines(). Use the counter from part 1 to determine how many lines to read.


##### Chapter 9 part 2
Redo chapter 9 part 1:

1. Put the while loop that inputs from the keyboard into a procedure. Open the file from the main part of the program using a with statement, call the procedure from inside the with. Pass the file as a parameter to the procedure. Remove the counter from the while loop, you won't need it

2. Put the loop that reads in from the file into a procedure. Open the file in a second with statement, and put your procedure in the with statement using the file as a parameter. Read the contents of the file using a for loop, print the contents of the file in upper case.
