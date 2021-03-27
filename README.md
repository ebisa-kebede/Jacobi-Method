# Jacobi-Method
This class provides a simple implementation of the Jacobi method for solving  * systems of linear equations.
How to use:   The program reads an augmented matrix from standard input,   
for example:  

3    

 5 -2  3 -1   
-3  9  1  2    
 2 -1 -7  3   

Means

 5X1 - 2X2 + 3X3 = -1
 
-3X1 + 9X2 + 1X3 =  2

 2X1 - 1X2 - 7X3 =  3



The number in the first line is the number of equations and number of variables. You can put this values in a file   and then execute the program as follows:    
$ java Jacobi &lt; equations.txt   If the matrix isn't diagonally dominant the program tries   to convert it(if possible) by rearranging the rows. */
