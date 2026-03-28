# EX 4 C program to read the age of a person and determine whether he is eligible for marriage (eligible if age ≥ 21).
## DATE:
## AIM:
To write a C program to read the age of a person and determine whether he is eligible for marriage (eligible if age ≥ 21).

## Algorithm
Start the program.

Declare an integer variable age to store the person's age.

Read the age from the user.

Compare the age using an if statement: if age >= 21, print "Eligible for marriage".

Else, print "Not eligible for marriage".

Stop the program.

## Program:
```
#include <stdio.h>
int main() {
    int age;
    printf("Enter the age: ");
    scanf("%d", &age);
    if (age >= 21) {
        printf("Eligible for marriage\n");
    } else {
        printf("Not eligible for marriage\n");
    }
    return 0;
}
```

## Output:

Enter the age: 25
Eligible for marriage

## Result:
Thus the program was executed and the output was verified successfully.
