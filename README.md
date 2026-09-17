# 19AI304-Fundamentals-of-C-Programming-2025-Odd-M1
# Module 1 
# Ex.No:1
1. Write a C program to read the student percentage and print the grade he/she got?
2. marks>=70 print A+ GRADE
3. 60>= marks <70 print A GRADE
4. 50>= marks <60 print B GRADE
5. 40>= marks <50 print C GRADE
6. marks<40 print F GRADE

# Aim:
To write a C program to read a student's percentage and print the corresponding grade using conditional statements.

# Algorithm:
1. Start the program.
2. Declare a variable marks to store the student's percentage.
3. Read the student's percentage from the user.
4. Check the percentage:
5. If marks >= 70, print A+ GRADE.
6. Else if marks >= 60, print A GRADE.
7. Else if marks >= 50, print B GRADE.
8. Else if marks >= 40, print C GRADE.
9. Else, print F GRADE.
10. Stop the program.

# Program:
```
#include <stdio.h>
int main()  
{
    int a;
    scanf("%d",&a);
    if (a>=70)
        printf("A+ GRADE");
    else if (a>=60)
        printf("A GRADE");
    else if (a>=50)
        printf("B GRADE");
    else if (a>=40)
        printf("C GRADE");
    else 
        printf("F GRADE");
    return 0;
}
```

# Output:
<img width="947" height="462" alt="image" src="https://github.com/user-attachments/assets/c9dd24bb-cd4d-4249-b067-9930c3b07e00" />



# Result: 
Thus, the C program was successfully executed to read the student's percentage and print the corresponding grade based on the given percentage.


# Ex.No:2
Write a C program to check whether the given number is  even number and greater than 50 or not using nested if.

# Aim:
 To write a C program using nested if to check whether the given number is an even number and greater than 50.
 
# Algorithm:
1. Start the program.
2. Declare an integer variable num.
3. Read the number from the user.
4. Check whether num is greater than 50 using if.
5. If it is greater than 50, check whether num is even using num % 2 == 0.
6. If both conditions are true, print "Number is even and greater than 50".
7. Otherwise, print the appropriate message.
8. Stop the program.

# Program:
```
#include <stdio.h>
int main()
{
    int a;
    scanf("%d",&a);
    if (a % 2 == 0)
    {
        printf("The number is even\n");
        if (a >= 50)
        {
            printf("The number is greater than  or equal to 50");
        }
        else
        {
            printf("The number less than 50");
        }
    }
    else
    {
        printf("The number is NOT an even number");
    }
    return 0;
}
```
# Output:
<img width="943" height="332" alt="image" src="https://github.com/user-attachments/assets/c8f26772-bbb3-49a9-b581-c1dfb2524b5c" />

# Result: 
Thus, the C program was successfully executed using nested if to check whether the given number is even and greater than 50.


# 19AI304-Fundamentals-of-C-Programming-2025-Odd
# IAPR-1- Module 1 - FoC
# Ex.No:3
  Build a C program to demonstrate the use of different data types such as int, float, double, and char, and display their values using printf().
# Date : 22/04/2026
# Aim:
  To build a C program that declares variables of various data types—integer, float, double, and character—initializes them, and prints their values on the screen.
# Algorithm:
### Step 1:
  Start
### Step 2: 
  Include the standard input-output library: #include<stdio.h>.
### Step 3: 
  Inside main(), declare and initialize variables of types int, float, double, and char.
### Step 4: 
   Display their values using printf().
### Step 5:    
   Stop
# Program:
```
#include<stdio.h>

int main()
{
    int a = 10;
    float b = 5.5f;
    double c = 25.6789;
    char d = 'A';

    printf("Integer value = %d\n", a);
    printf("Float value = %.2f\n", b);
    printf("Double value = %.4lf\n", c);
    printf("Character value = %c\n", d);

    return 0;
}
```
# Output:
```
Integer value = 10
Float value = 5.50
Double value = 25.6789
Character value = A
```
# Result: 

# 19AI304-Fundamentals-of-C-Programming-2025-Odd
# IAPR-1- Module 1 - FoC
# Ex.No:4
  Build a C program to perform arithmetic and bitwise operations on two integers entered by the user. The program should display: Arithmetic operations: addition, subtraction, multiplication, division, and remainder. Bitwise operations: AND, OR, XOR, left shift, right shift, and NOT.
# Date : 22/04/2026
# Aim:
  To build a C program that takes two integers as input and demonstrates the arithmetic and bitwise operations, displaying the results of each operation.
# Algorithm:
### Step 1:
  Start
### Step 2: 
  Include the standard input-output library: #include<stdio.h>.
### Step 3: 
  Declare two integer variables a and b.
### Step 4: 
   Prompt the user to enter two integers and read the input using scanf().
### Step 5:    
   Perform arithmetic operations on a and b:
   #### Sum (a + b)
   #### Difference (a - b)
   #### Product (a * b)
   #### Quotient (a / b)
   #### Remainder (a % b)
### Step 6: 
  Perform bitwise operations on a and b:
  #### AND (a &amp; b)
  #### OR (a | b)
  #### XOR (a ^ b)
  #### Left shift (a << b)
  #### Right shift (a >> b)
  #### Bitwise NOT of a (~a) and b (~b)
### Step 7:   
  Display the results of all operations using printf().
### Step 8:   
  Stop
# Program:
```
#include<stdio.h>

int main()
{
    int a, b;

    printf("Enter two integers: ");
    scanf("%d %d", &a, &b);

    // Arithmetic operations
    printf("\nArithmetic Operations\n");
    printf("Addition = %d\n", a + b);
    printf("Subtraction = %d\n", a - b);
    printf("Multiplication = %d\n", a * b);
    printf("Division = %d\n", a / b);
    printf("Remainder = %d\n", a % b);

    // Bitwise operations
    printf("\nBitwise Operations\n");
    printf("AND = %d\n", a & b);
    printf("OR = %d\n", a | b);
    printf("XOR = %d\n", a ^ b);
    printf("Left Shift = %d\n", a << b);
    printf("Right Shift = %d\n", a >> b);
    printf("Bitwise NOT of a = %d\n", ~a);
    printf("Bitwise NOT of b = %d\n", ~b);

    return 0;
}
```
# Output:
```
Enter two integers: 10 5

Arithmetic Operations
Addition = 15
Subtraction = 5
Multiplication = 50
Division = 2
Remainder = 0

Bitwise Operations
AND = 0
OR = 15
XOR = 15
Left Shift = 320
Right Shift = 0
Bitwise NOT of a = -11
Bitwise NOT of b = -6
```
# Result: 
Thus, the program was implemented and executed successfully, and the required output was obtained.


# 19AI304-Fundamentals-of-C-Programming-2025-Odd
# IAPR-1- Module 1 - FoC
# Ex.No:5
  Develop a C program to check whether a given character is a vowel, consonant, digit, or special symbol using the ternary operator.
# Date : 22/04/2026
# Aim:
  To develop and implement a C program that classifies a character as a vowel, consonant, digit, or special symbol using the ternary operator.
# Algorithm:
### Step 1:
  Start
### Step 2: 
  Include the standard input-output library: #include<stdio.h>.
### Step 3: 
  Input a character ch from the user.
### Step 4: 
   Check if ch is a digit ('0' to '9').
   
   If true → Print "Digit" → Go to Step 8.
   
   If false → Go to Step 5.
   
### Step 5:    
   Check if ch is an alphabet letter ('A' - 'Z' or 'a' – 'z').
   
   If true → Go to Step 6.
   
   If false → Go to Step 7.
   
### Step 6: 
   Check if ch is a vowel (a, e, i, o, u or A, E, I, O, U).
   
   If true → Print "Vowel" → Go to Step 8.
   
   If false → Print "Consonant" → Go to Step 8.
   
### Step 7:   
   Print "Special Symbol".
### Step 8:   
  Stop
# Program:
```
#include<stdio.h>

int main()
{
    char ch;

    printf("Enter a character: ");
    scanf("%c", &ch);

    (ch >= '0' && ch <= '9') ?
        printf("Digit") :

        ((ch >= 'A' && ch <= 'Z') || (ch >= 'a' && ch <= 'z')) ?

            ((ch == 'A' || ch == 'E' || ch == 'I' || ch == 'O' || ch == 'U' ||
              ch == 'a' || ch == 'e' || ch == 'i' || ch == 'o' || ch == 'u') ?

                printf("Vowel") :
                printf("Consonant"))

        : printf("Special Symbol");

    return 0;
}
```
# Output:
```
Enter a character: A
Vowel
```
# Result: 
Thus, the program was implemented and executed successfully, and the required output was obtained.


