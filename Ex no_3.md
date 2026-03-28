Gemini said
DATE: 28-03-2026
AIM:
To write a C program to find the number of years based on principal, rate, and simple interest.

Algorithm
Start the program.

Declare floating-point variables for Principal (P), Rate (R), Simple Interest (SI), and Time/Years (T).

Input the values for Principal, Rate of interest, and the Simple Interest earned.

Calculate the number of years using the formula: T= 
P×R
SI×100
​
 .

Display the calculated value of years.

Stop the program.

Program:
C
#include <stdio.h>
int main() {
    float P, R, SI, T;
    printf("Enter Principal: ");
    scanf("%f", &P);
    printf("Enter Rate of Interest: ");
    scanf("%f", &R);
    printf("Enter Simple Interest: ");
    scanf("%f", &SI);
    T = (SI * 100) / (P * R);
    printf("Number of Years: %.2f", T);
    return 0;
}
Output:
Plaintext
Enter Principal: 5000
Enter Rate of Interest: 5
Enter Simple Interest: 500
Number of Years: 2.00
Result:
Thus the program was executed and the output was verified successfully.
