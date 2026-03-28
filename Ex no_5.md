# EX 5 C program to calculate the total marks, average, and percentage of marks obtained in seven subjects.
## DATE:
## AIM:
To write a C program to calculate the total marks, average, and percentage of marks obtained in seven subjects.

## Algorithm
Start the program.Declare seven variables for subjects ($s1, s2, s3, s4, s5, s6, s7$) and variables for total, average, and percentage.Read the marks obtained in the seven subjects from the user.Calculate the total marks by adding the marks of all seven subjects.Calculate the average and percentage (assuming each subject is out of 100, the percentage is $\frac{\text{Total}}{7}$).Display the total, average, and percentage.Stop the program.

## Program:
```
#include <stdio.h>
int main() {
    float s1, s2, s3, s4, s5, s6, s7, total, average, percentage;
    printf("Enter marks for 7 subjects: \n");
    scanf("%f %f %f %f %f %f %f", &s1, &s2, &s3, &s4, &s5, &s6, &s7);
    total = s1 + s2 + s3 + s4 + s5 + s6 + s7;
    average = total / 7;
    percentage = (total / 700) * 100;
    printf("Total Marks: %.2f\n", total);
    printf("Average Marks: %.2f\n", average);
    printf("Percentage: %.2f%%\n", percentage);
    return 0;
}
```

## Output:

Enter marks for 7 subjects: 
85 90 78 92 88 84 91
Total Marks: 608.00
Average Marks: 86.86
Percentage: 86.86%

## Result:
Thus the program was executed and the output was verified successfully.
