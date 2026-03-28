DATE: 28-03-2026
AIM:
To write a program to check whether the attendance is PRESENT using a simple if statement.

Algorithm
Start the program.

Declare an integer variable (e.g., status) to represent attendance.

Read the input value from the user (e.g., 1 for PRESENT).

Use a simple if statement to check if the input matches the condition for being present.

Display the message "PRESENT" if the condition is true.

Stop the program.

Program:
C
#include <stdio.h>
int main() {
    int status;
    printf("Enter attendance status (1 for Present): ");
    scanf("%d", &status);
    if (status == 1) {
        printf("PRESENT\n");
    }
    return 0;
}
Output:
Plaintext
Enter attendance status (1 for Present): 1
PRESENT
Result:
Thus the program was executed and the output was verified successfully.
