
Youtube Link: https://youtu.be/-37nDUgEGsQ


///////////////////////
Author: Haroun Kassouri 
Student number: C21508813
Date started: 03/04/2023
Date finished: 07/04/2023
///////////////////////


Program description:
This program has a real life function and will work as a recipe finder.
The user will enter an ingredient i.e a word and it will check the textfile list
which is a number of textfiles with recipes inside and return a list of files with that word inside.
It will also return the number of times the specific word is located within the file.

The user can also enter two words seperated by && and it will search for a recipe i.e textfile
that contains both of these words.

This way i have completed the assignment while also creating a real life application that someone can use.
For example if someone has an ingredient or some food. They can type it into the recipe finder and it will provide them
with recipes that contain that food.

Classes description:
Control class
Screen class
Screen2 class

The control class calls screen class. The screen classes does all the above. Creates the jframe,jpanel and all the buttons and textboxes inside.
This class does all the work including all the functionality, such as searching for the word in the text files, reading the textfiles, taking in input and everything else the code does
When user clicks submit screen calls on screen 2 and this screen just takes in the text result and prints it out in a new jframe.

Note:
There are some pieces of code i got online. I will be placing it all below here just so you know.
I did implement the lines of code that i found online in my own way. I
did not just copy and paste. 

1. The for each loop - I found this loop online and implemented it in the program
2. I got the error message part from here, online JOptionPane.showMessageDialog(this,"Please enter a word to search.", "Error", JOptionPane.ERROR_MESSAGE
3. This piece of code i did not write but used in my program in order to make my code work, String[] words = word.split("\\s*&&\\s*");


If i had more item i was gonna add an option to allow users to view the textfile that they choose.

