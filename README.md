# Gym_Management_System-2.0
This is a renewed version of my original gym management system. It has utilized structures and header files and some new functions are added.

## void addorder(order(*orderarr),equipment1(*equiparr),branch1(*brancharr), int row,int* arraycounter) :
•	Used to add new orders
•	Uses arrays of all the databases to find info relating to branch and equipment
•	Calculates total order price by using the entered quantity and price stored in the equipment array.

## void vieworder(order(*orderarr), equipment1(*equiparr), branch1(*brancharr), int row,int* arraycounter) :
•	Used to view all orders placed.
•	Uses arrays of all the databases to display all orders contained
•	Uses indexes stored within the order array to locate relevant information from the branch and equipment arrays.

## void storedata(type(*arr), string file) :
•	Used to store data from array into file when returning to main menu.
•	Overloaded function to support all structure.

## void loaddata(type(*arr), string file) :
•	Used to load data from file to array when program is run.
•	Overloaded to support all structures.

