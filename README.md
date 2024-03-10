# c-language
# strcture og c programming and Excution
#include<stdio.h>
 int main(){
 printf(“Hello world”);
 return 0;
 }

 # 1.preprocessor directives
 #include

 # 2.Libaries
 #include

 # 3.Comments
 //This is a single-line comment
 /*
 This is a
 multi-line comment
 */

 # 4.Main function
 int main() {
 // Code goes here
 return 0;
 }

 # 5.Variables & Data types
 int a; // Declaration of an integer variable
 float b = 3.14; // Declaration and initialization of a floating-point variable

 # 6.Statements & Preprocessors
 int sum = a + 5; // Expression
 if (sum > 10) {
 // Statement
 printf("Sum is greater than 10.\n");
 }

 # 7.Input & Output Operations
 int main() {
 int userInput;
 printf("Enter a number: ");
 scanf("%d", &userInput);
 printf("You entered: %d\n", userInput);
 return 0;
 }

 # 8.Return Statements
 int main() {
 // Code
 return 0; // Indicates successful terminationS
 }

 # 9.Special Symbols and Operators
 int a = 5, b = 3, result;
 result = a + b; // Addition
 result = a - b; // Subtraction
 result = a * b; // Multiplication
 result = a / b; // Division
 result = a % b; // Modulus (remainder)

 # EXAMPLE
 #include <stdio.h>

int main() {
    // Declare variables and initialize them with predefined values
    int num1 = 5;
    int num2 = 7;
    int sum;

    // Calculate the sum
    sum = num1 + num2;

    // Display the result
    printf("The sum of %d and %d is: %d\n", num1, num2, sum);

    // Indicate successful completion
    return 0;
}
