#include <stdio.h>

int main() {
    int a, b; // Variables for user input

    // Taking input from the user
    printf("Enter first number: ");
    scanf("%d", &a);

    printf("Enter second number: ");
    scanf("%d", &b);

    // Performing arithmetic operations
    printf("\nAddition (a + b): %d\n", a + b);
    printf("Subtraction (a - b): %d\n", a - b);
    printf("Multiplication (a * b): %d\n", a * b);

    // Checking for division by zero before performing division
    if (b != 0) {
        printf("Division (a / b): %d\n", a / b);
        printf("Modulus (a %% b): %d\n", a % b);
    } else {
        printf("Division and modulus not possible (b = 0)\n");
    }

    return 0;
}
