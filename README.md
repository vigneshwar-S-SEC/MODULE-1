# MODULE-1
# EXP NO:1 C PROGRAM TO FIND THE ASCII VALUE OF A GIVEN CHARACTER
## AIM:
To write a C program to find and display the ASCII value of a given character.
## Algorithm:
1. Start
2. Declare a character variable ch.
3. Get a character input from the user using scanf().
4. Print the ASCII value of the entered character using print().
5. Stop the program.

## PROGRAM:
```
#include <stdio.h>
int main()
{
    char ch;
    scanf("%c", &ch);
    printf("ASCII value of %c is %d", ch, ch);
}
```
## Output:
![alt text](EX_NO1.png)
## RESULT:
Thus, the program to find the ASCII value of a given character was executed and verified successfully.



# EXP NO:2 C PROGRAM TO COMPARE TWO NUMBERS USING NESTED IF-ELSE

## Aim:

Write a C program to read two whole numbers and figure out if they are the same or which one is bigger, using if-else statements.

## Algorithm:

1. Start.

2. Get two numbers (A and B) from the user.

3. Check if A equals B. If yes, say they are equal.

4. If not equal, print that fact. Then, check:

    - If B is bigger than A, say B is larger.

    - Otherwise, say A is larger.

5. Stop.

## Program:
```
#include <stdio.h>
int main(){
    int a,b;
    scanf("%d %d",&a,&b);
    if (a == b)
      printf("A is equal to B");
    else
    {
      printf("A is not equal to B");

      if (b>a)
       printf("\nB is larger than A");
      else
       printf("\nA is larger than B"); }
return 0;
}
```

## Output:
![alt text](EX_NO2.png)
## Result:
The program to compare two numbers and find the largest using nested if-else was completed successfully.

# EXP NO:3 C PROGRAM TO FIND THE AREA OF A RECTANGLE

## Aim:
To write a C program that calculates the area of a rectangle by taking its length and breadth as input using floating-point numbers.

## Algorithm:
1. Start.

2. Declare three floating-point variables: a (for length), b (for breadth), and A (for area).

3. Get the length (a) and breadth (b) from the user.

4. Calculate the area using the formula: 
    \[
         $$A = a \times b$$
    \]


5. Display the calculated area (A), formatted to show two decimal places.

6. Stop.

## Program:
```
#include <stdio.h>
int main(){
    float a,b,A;
    scanf("%f %f",&a,&b);
    A = a * b;
    printf("Area of rectangle=%.2f sq.units",A);
    return 0;
}
```

## Output:
![alt text](EX_NO3.png)
## Result:

The C program to calculate the area of a rectangle using floating-point numbers was executed and verified successfully.