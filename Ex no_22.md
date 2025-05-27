# EX 22 C program to count total number of even elements in an array using calloc().
## AIM:
To write a C program to count total number of even elements in an array using calloc().

## Algorithm
1. Declare variables for array size, count, and pointer for the array.
2. Use calloc() to dynamically allocate memory for the array.
3. Read the array elements from user input.
4. Iterate through the array and increment count for each even element.
5. Print the total count of even elements and free the allocated memory.


## Program:
```
/*
C program to count total number of even elements in an array using calloc().
Developed by: Mariam Sherin
RegisterNumber: 212222060143
#include<stdio.h>
#include<stdlib.h>
int main()
{
    int c=0;
    int*p=(int*)malloc(5*sizeof(int));
    p[0]=3;
    p[1]=5;
    p[2]=32;
    p[3]=21;
    p[4]=20;
    for(int i=0;i<5;i++)
    {
        if(*(p+i)%2==0)
        {
            c++;
        }
    }
    printf("Total even elements: %d",c);
}
*/
```

## Output:

![image](https://github.com/user-attachments/assets/a0c35e3b-4b3a-4808-bdc8-d345ef752e87)


## Result:
Thus the program was executed and the output was verified successfully.
