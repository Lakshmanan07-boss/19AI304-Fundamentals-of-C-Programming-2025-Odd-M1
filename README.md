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


# Ex.No:3
  Write a C program to swap (For ex: a=200,b=300 into a=300,b=200) two values without using a third variable.
# Aim:
  To write a C program to swap two values without using a third variable..
# Algorithm:
1. Start the program.
2. Declare two integer variables a and b.
3. Read the values of a and b.
4. Swap the values using arithmetic operations:
5. a = a + b
6. b = a - b
7. a = a - b
8. Display the values of a and b after swapping.
9. Stop the program.

# Program:
```
#include <stdio.h>
int main()
{
    int a,b;
    scanf("%d %d",&a,&b);
    printf("Numbers before swapping: %d %d\n",a,b);
    a=a+b;
    b=a-b;
    a=a-b;
    printf("Numbers after swapping: %d %d",a,b);
    return 0;
}
```
# Output:
<img width="942" height="337" alt="image" src="https://github.com/user-attachments/assets/bb819d8f-3038-42cd-a7ae-c596fa81492a" />

# Result: 
Thus, the C program was successfully executed to swap two values without using a third variable.

# Ex.No:4
  Write a C Program to check a number is positive or negative using switch case.
# Aim:
  Write a C Program to check a number is positive or negative using switch case.
# Algorithm:
1. Start the program.
2. Declare an integer variable num.
3. Read the number from the user.
4. Use switch with the result of (num > 0) - (num < 0).
5. If the result is 1, print Positive Number.
6. If the result is -1, print Negative Number.
7. If the result is 0, print Zero.
8. Stop the program.

# Program:
```
#include <stdio.h>
int main()
{
    int a;
    scanf("%d",&a);
    if (a>0)
        printf("%d is positive.",a);
    else if (a<0)
        printf("%d is negative.",a);
    else
        printf("%d is neither positive nor negative.",a);
    return 0;
}
```
# Output:
<img width="932" height="218" alt="image" src="https://github.com/user-attachments/assets/2e81b67b-456b-4069-b0d5-6ea4752a1a47" />


# Result: 
Thus, the C program was successfully executed to check whether the given number is positive, negative, or zero using switch case.


# Ex.No:5
  Write a C program to calculate a bike’s average consumption to cover 10000km with 150.5 liter fuel.
# Aim:
  To write a C program to calculate a bike's average fuel consumption for covering a distance of 10,000 km using 150.5 liters of fuel.
# Algorithm:
1. Start the program.
2. Declare variables for distance, fuel, and average.
3. Assign distance = 10000 km and fuel = 150.5 litres.
4. Calculate average consumption using average = distance / fuel.
5. Display the average consumption.
6. Stop the program.

# Program:
```
#include <stdio.h>
int main()
{
    float a=10000,b=150.5,c;
    c=a/b;
    printf("Average consumption(km/lt):%.2f",c);
    return 0;
    
}
```
# Output:
<img width="906" height="143" alt="image" src="https://github.com/user-attachments/assets/c088c045-a857-4eaa-9025-9dce4f8f0d0e" />

# Result: 
Thus, the C program was successfully executed, and the bike's average fuel consumption is 66.45 km/litre.

