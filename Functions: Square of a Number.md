## Functions: Square of a Number using Function in C
## Aim
To write a C program that finds the square of a number using a function without arguments and without a return type.

## Algorithm
Define a function square without parameters.

Inside the square function, declare variables n and b.

Read an integer n from the user and calculate the square by multiplying n with itself.

Print the square value using printf with two decimal places.

In the main function, call the square function.

Return 0 to indicate successful execution.

## Program
```
#include <stdio.h>
void square() 
{
    int n;
    float b;
    printf("Enter an integer: ");
    scanf("%d", &n);
    b = n * n;
    printf("Square of %d is %.2f\n", n, b);
}

int main() 
{
    square();
    return 0;
}
```

## Output
<img width="541" height="186" alt="image" src="https://github.com/user-attachments/assets/7f012870-ce70-4b40-849e-a18f2a4f2e75" />


## Result
C program that finds the square of a number using a function without arguments and without a return type is written.
