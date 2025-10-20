# Program-5B
C module 5
EX NO-5)B)a program for factorial of n Numbers using recursion
DATE:20/10/25
NAME:JADE ADRINA J
REF NO:25017000
AIM:TO write a program for factorial of n Numbers using recursion
ALGORITHM:
1) Take a number as input from the user.2) Define a recursive function factorial(n) return n * factorial(n - 1).3) Call the function factorial(n) and display the result.
PROGRAM:
```
#include <stdio.h>
unsigned long long factorial(int num) {
    if (num == 0 || num == 1)
        return 1;
    else
        return num * factorial(num - 1);
}

int main() {
    int  number;
    scanf("%d", &number);

        if (number < 0) {
            printf("Factorial is not defined for negative numbers.\n");
        } else {
            printf("Factorial of %d is %llu\n", number, factorial(number));
        }
    

    return 0;
}
```
OUTPUT:
<img width="1067" height="296" alt="Screenshot 2025-10-20 083640" src="https://github.com/user-attachments/assets/50da23a9-edb8-4e23-b3b0-3aca92c043c8" />
RESULT:
thus,a  program for factorial of n Numbers using recursion has been executed successfully.
