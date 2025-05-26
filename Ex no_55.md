# EX 55 C program to find a square of number using function with arguments without return type.
## AIM:
To write a C program to find a square of number using function with arguments without return type.

## Algorithm
1. Start.
2. Define a variables.
3. Write a program to square of the given number.
4. Read the value using scanf.
5. Ask the user to make an input.
6. Print out the answer.
7. End
   

## Program:
```c
#include <stdio.h>
int square(int num) {
 return num * num;
}
int main() {
 int number, result;
 scanf("%d", &number);
 result = square(number); // Function call
 printf("Square of %d is %d\n", number, result);
}

```

## Output:

![image](https://github.com/user-attachments/assets/27ebff1c-0475-408c-bf35-aeb099ec6ce9)


## Result:
Thus the program was executed and the output was verified successfully.
