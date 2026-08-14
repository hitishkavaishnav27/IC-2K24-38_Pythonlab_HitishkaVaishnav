## Section A – Quick Concept Check

1. `input()` always returns data of type **str**.
2. The function used to check the data type of a variable is **type()**.
3. A string can be converted to an integer using **int()** and to a float using **float()**.
4. `**` is the operator for **exponentiation**, and `//` is the operator for **floor division**.
5. `%` is called the **modulus** operator. It gives the **remainder**.
6. A single-line comment in Python starts with the symbol **#**.
7. A variable name cannot start with a number.

## Section B – Predict the Output

1. 13 — Right
2. 5 — Right
3. True — Right
4. <class 'float'> — Right
5. yth — Right
6. Hi    There
   Bye — Right

## Section C – Programs

1. Variable and Identifier Practice

Aim: To declare variables and display their values and data types.
Logic: Different variables are created for name, age, height, and student status. The type() function is used to display their data types.
Sample Input / Output:
```text
Name: Hitishka Type: <class 'str'>
Age: 19 Type: <class 'int'>
Height: 5.6 Type: <class 'float'>
Student: True Type: <class 'bool'>

2. Greeting Program
Aim: To take the user's name, age, and city as input and display them in one sentence.
Logic: The program takes the user's name, age, and city using input(). An f-string is used to combine all three values into one sentence.
Sample Input / Output:
Enter your name: Hitishka
Enter your age: 19
Enter your city: Indore
My name is Hitishka, I am 19 years old, and I live in Indore.

3. Arithmetic Operations
Aim: To perform basic arithmetic operations on two numbers.
Logic: Two numbers are taken as input and converted into numbers using float(). The program calculates their sum, difference, product, quotient, and remainder.
Sample Input / Output: 
Enter first number: 10
Enter second number: 3
Sum: 13.0
Difference: 7.0
Product: 30.0
Quotient: 3.3333333333333335
Remainder: 1.0

4. Celsius to Fahrenheit
Aim: To convert a temperature from Celsius to Fahrenheit.
Logic: The temperature in Celsius is taken as input and converted into a number. The formula F = (C × 9/5) + 32 is used to calculate the Fahrenheit value.
Sample Input / Output:
Enter temperature in Celsius: 25
Temperature in Fahrenheit: 77.0

5. String Manipulation
Aim: To perform different operations on a full name.
Logic: The program takes a full name as input. It converts the name to uppercase and lowercase, reverses the name, and calculates its length.
Sample Input / Output:
Enter your full name: Hitishka Vaishnav
Uppercase: HITISHKA VAISHNAV
Lowercase: hitishka vaishnav
Reversed: navhsiaV aksih tiH
Length: 17

6. Escape Sequence Practice
Aim: To print a simple receipt using escape sequences.
Logic: The \t escape sequence is used to create spacing between the item name and price. The \n escape sequence is used to print information on separate lines.
Sample Input / Output:
Item        Price
Pen         10 rupees
Notebook    50 rupees
Pencil      5  rupees
Total       65 rupees
