## Nested Loop:Triangular Pattern Printer in C
## Aim
To write a C program that prints a triangular pattern of $ symbols using nested loops based on a user-defined value n.

## Algorithm
Declare variables n, i, and j.

Read the value of n from the user.

Use a for loop to iterate i from n to 1.

Inside the outer loop, use another for loop to iterate j from 1 to i and print "$".

After each inner loop, print a newline character (\n) to move to the next line.

## Program
```
#include <stdio.h>
int main() {
    int n, i, j;
    printf("Enter the number of rows: ");
    scanf("%d", &n);
    for (i = n; i >= 1; i--)
    {
        for (j = 1; j <= i; j++) {
            printf("$");
        }
        printf("\n");
    }

    return 0;
}
```
## Output
<img width="549" height="319" alt="image" src="https://github.com/user-attachments/assets/7bef140e-56bb-4d20-9538-7e8184bfb47f" />

## Result
C program that prints a triangular pattern of $ symbols using nested loops based on a user-defined value n is written.
