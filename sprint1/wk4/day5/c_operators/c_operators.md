# Arithmetic Operators in C
https://www.tutorialspoint.com/cprogramming/c_arithmetic_operators.htm

The following table shows all the arithmetic operators supported by the C language. Assume variable A holds 10 and variable B holds 20, then −

```
Operator	Description	                                Example
+	        Adds two operands.	                        A + B = 30
−	        Subtracts second operand from the first.	A − B = -10
*	        Multiplies both operands.	                A * B = 200
/	        Divides numerator by de-numerator.	        B / A = 2
%	        Modulus Operator and remainder of after an integer division.	B % A = 0
++	        Increment operator increases the integer value by one.	A++ = 11
--	        Decrement operator decreases the integer value by one.	A-- = 9
```
### Example
Try the following example to understand all the arithmetic operators available in C −
```
#include <stdio.h>

main() {

   int a = 21;
   int b = 10;
   int c ;

   c = a + b;
   printf("Line 1 - Value of c is %d\n", c );
	
   c = a - b;
   printf("Line 2 - Value of c is %d\n", c );
	
   c = a * b;
   printf("Line 3 - Value of c is %d\n", c );
	
   c = a / b;
   printf("Line 4 - Value of c is %d\n", c );
	
   c = a % b;
   printf("Line 5 - Value of c is %d\n", c );
	
   c = a++; 
   printf("Line 6 - Value of c is %d\n", c );
	
   c = a--; 
   printf("Line 7 - Value of c is %d\n", c );
}
```
When you compile and execute the above program, it produces the following result −
```
Line 1 - Value of c is 31
Line 2 - Value of c is 11
Line 3 - Value of c is 210
Line 4 - Value of c is 2
Line 5 - Value of c is 1
Line 6 - Value of c is 21
Line 7 - Value of c is 22
```