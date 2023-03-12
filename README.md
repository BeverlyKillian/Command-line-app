# Command-line-app
/*multiple line alingement
A program that takes a users input interger and prints out its multuplicatiin table */
#include <stdio.h> //inline comment 
int main() //The program entry point//{// opening curly bracesThe function already begins here
    int num, i;//intializing and declairing a variable called i
    
    printf("Enter a number: ");//displays Enter a number to the users's screen
    scanf("%d", &num);
    
    printf("Multiplication table of %d:\n", num);
    
    for (i = 1; i <= 10; i++) {/*using a for loop statement where there a variable called i is intialized,the i follows a condition that the variable is less than or equal
    to 10 and updates with a post increment of the variable*/
    printf("%d x %d = %d\n", num, i, num*i);
  }
  return 0;
