# Basics
##Code 1
1. Start
2. Declare variables: char op (operator), float num1 (first operand), float num2 (second operand)
3. Output: "Enter operator: +, -, *, /: "
4. Input: Read the operator from the user and store it in the variable op
5. Output: "Enter two operands: "
6. Input: Read the two operands (num1 and num2) from the user
7. Use a switch statement based on the value of op:
   a. If op is '+', calculate and output: num1 + num2
   b. If op is '-', calculate and output: num1 - num2
   c. If op is '*', calculate and output: num1 * num2
   d. If op is '/', calculate and output: num1 / num2
   e. If op is none of the above, output an error message
8. End
The program starts and declares the necessary variables.
The user is prompted to enter an operator (+, -, *, or /).
The program reads the operator from the user and stores it in the variable op.
The user is prompted to enter two operands.
The program reads the two operands (num1 and num2) from the user.
The program uses a switch statement to perform the appropriate arithmetic operation based on the operator provided by the user.
It then outputs the result of the operation or an error message if the operator is not recognized.
The program ends after processing the input and performing the desired operation.

##Code 2
1. Start
2. Declare variables: int n (original number), reversed_number = 0 (to store the reversed number), remainder
3. Output: "Enter an integer: "
4. Input: Read the value of n from the user
5. Use a while loop with the condition n != 0 to reverse the number:
   a. Calculate the remainder of n divided by 10 and store it in the variable remainder: remainder = n % 10
   b. Multiply reversed_number by 10 and add the remainder: reversed_number = reversed_number * 10 + remainder
   c. Update n by removing its last digit: n = n / 10
   d. Repeat steps a-c until n becomes 0
6. Output: "Reversed Number = reversed_number"
7. End
The program starts and declares necessary variables.
The user is prompted to enter an integer (variable n).
The program enters a while loop that continues until n becomes 0.
In each iteration of the loop, the program calculates the last digit of n using the modulus operator (%), stores it in remainder.
It then updates the reversed_number by multiplying it by 10 and adding the remainder. The last digit of n becomes the first digit of reversed_number.
After processing all the digits of the original number, the loop ends, and the program outputs the reversed_number.
The program ends after reversing and outputting the number.
