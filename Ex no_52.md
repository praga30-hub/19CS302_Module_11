## Task

# Write a function int max_of_four(int a, int b, int c, int d) which reads four arguments and returns the greatest of them.

## Note

There is not built in max function in C. Code that will be reused is often put in a separate function, e.g. int max(x, y) that returns the greater of the two values.

## Input Format

Input will contain four integers - a,b,c,d , one on each line.

## Output Format

Print the greatest of the four integers.
Note: I/O will be automatically handled.

AIM:

To write a program to calculate maximum function.

ALGORITHM:

1. Start.
2. Define a variables.
3. Write a program to calculate maximum function.
4. Read the value using scanf.
5. Ask the user to make an input.
6. Print out the answer.
7. End.

PROGRAM:

```
#include<stdio.h>
int max(int x,int y)
{
    return x>y ? x:y;
}
int max_of_four(int a,int b,int c,int d)
{
    int large=max(max(a,b),max(c,d));
    return large;
}
int main()
{
    int a,b,c,d;
    scanf("%d %d %d %d",&a,&b,&c,&d);
    int large=max_of_four(a,b,c,d);
    printf("%d",large);
    return 0;
}
```
OUTPUT:

![image](https://github.com/user-attachments/assets/91818bf0-2d0c-4422-acbe-6b336fc12f64)

RESULT:


Thus, the program is executed and verified successfully.
