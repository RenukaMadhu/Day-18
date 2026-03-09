# Day-18
Largest of Three Numbers – Explanation
This C program finds the largest number among three numbers entered by the user.
First, the program includes the header file stdio.h, which is required for input and output functions like printf() and scanf().
Inside the main() function, three integer variables a, b, and c are declared to store the numbers entered by the user.
The program then asks the user to enter three numbers using the printf() function. The scanf() function reads the values entered by the user and stores them in the variables a, b, and c.
Next, the program uses if–else if–else conditions to compare the three numbers:
It first checks if a is greater than or equal to both b and c. If this condition is true, a is the largest number.
If the first condition is false, it checks whether b is greater than or equal to both a and c. If true, b is the largest number.
If none of the above conditions are true, then c must be the largest number.
Finally, the program prints the largest number using the printf() function and ends with return 0;, which indicates successful execution of the program.
This program demonstrates the use of conditional statements (if, else if, else) to compare values and determine the largest number among three inputs.
