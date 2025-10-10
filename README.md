#include <stdio.h>
int main()
{
    int a, b; // Variables for user input
// Taking input from the user
    printf("Enter first number: ");
    scanf("%d", &a);
    printf("Enter second number: ");
    scanf("%d", &b);
// Performing relational operations
    printf("\nRelational Operator Results:\n");
    if (a == b)
        printf("a is equal to b\n");
    else
        printf("a is not equal to b\n");
    if (a != b)
        printf("a is not equal to b\n");

    if (a > b)
        printf("a is greater than b\n");

    if (a < b)
        printf("a is less than b\n");
    if (a >= b)
        printf("a is greater than or equal to b\n");

    if (a <= b)
        printf("a is less than or equal to b\n");


}
