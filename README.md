# EX-NO-6-Pseudo-Random-Number

# AIM: 
Implementation of Pseudorandom Number Generation Using Standard library

# ALGORITHM:
Start the program and import the required libraries.
Seed the random number generator using the current time(i.e) rand(time(0));
Get the number of randon number to generate.
Pass the value for number of iterations and print the numbers.
End the program.

## PROGRAM 
```.py
#include <stdio.h>

#include <stdlib.h>

#include <time.h>

int main()
{
    int n, i;

    // Seed the random number generator
    srand(time(0));

    // Get number of random numbers
    printf("Enter number of random numbers to generate: ");
    scanf("%d", &n);

    printf("Random Numbers are:\n");
    for (i = 0; i < n; i++)
    {
        printf("%d\n", rand());
    }

    return 0;
}

```



# OUTPUT:

<img width="559" height="355" alt="image" src="https://github.com/user-attachments/assets/eff64dca-6c96-4f09-91fe-fa5b24c03178" />


# RESULT:
Thus the program has been successfully implemented and executed using pseudo random number.
