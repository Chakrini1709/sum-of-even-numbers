This Python program calculates the sum of all even numbers between 1 and a given positive integer n. It uses an optimized approach by recognizing that even numbers form an arithmetic series, which allows us to compute the sum efficiently.

Features:
The program works for any positive integer n.
Handles edge cases where n is less than 2, as there are no even numbers less than 2.
Efficient computation by using the formula for the sum of an arithmetic series, which avoids looping through all the numbers.
How It Works:
The program asks for user input to enter a positive integer n.
It checks if n is greater than or equal to 2, since there are no even numbers below 2.
The program calculates the largest even number less than or equal to n and computes how many even numbers are present.
Using the arithmetic series sum formula, the program computes the sum of even numbers and returns the result.
Example:
For an input n = 10:

The even numbers between 1 and 10 are: 2, 4, 6, 8, 10.
The sum of these numbers is: 30.
