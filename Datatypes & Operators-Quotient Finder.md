## Datatypes & Operators-Quotient Finder in C

## Aim
To write a C program to find the **quotient** of two integer numbers.

## Algorithm
1. Declare variables `a`, `b`, and `quotient`.
2. Read two integers `a` and `b` from the user.
3. Calculate the quotient by dividing `a` by `b` and store the result in the variable `quotient`.
4. Print the values of `a`, `b`, and `quotient` using the `printf` function.
5. Return 0 to indicate successful execution.

## Program
```
#include <stdio.h>
int main() {
    int a, b, quotient;
    printf("Enter the dividend (a): ");
    scanf("%d", &a);
    printf("Enter the divisor (b): ");
    scanf("%d", &b);
    if (b == 0) 
    {
        printf("Error: Division by zero is not allowed.\n");
        return 1; 
    }
    quotient = a / b;
    printf("Dividend (a): %d\n", a);
    printf("Divisor (b): %d\n", b);
    printf("Quotient: %d\n", quotient);

    return 0;
}
```

## Output
![image](https://github.com/user-attachments/assets/45ce3fce-6701-4792-a2a8-918c7717e075)

## Result
C program to find the **quotient** of two integer numbers is written.
    
