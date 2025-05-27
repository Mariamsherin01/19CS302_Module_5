# EX 23 C program to read and print an employee's detail using structure
## AIM:
To write a C program to read and print an employee's detail using structure



## Algorithm
1. Define a structure with fields for employee details (e.g., empID, name, salary).
2. Declare a variable of the structure type.
3. Read employee details from user input and store them in the structure variable.
4. Print the stored employee details.
5. End the program.


## Program:
```
/*
C program to read and print an employee's detail using structure
Developed by: Mariam Sherin
RegisterNumber:  212222060143
#include<stdio.h>
struct emp
{
   char n[50];
   int id;
   float salary;
}e;
int main()
{
    
    scanf("%s",e.n);
    scanf("%d",&e.id);
    scanf("%f",&e.salary);
    printf("Entered detail is:");
    printf("\nName: %s",e.n);
    printf("\nId: %d",e.id);
    printf("\nSalary: %.2f",e.salary);
}
*/
```

## Output:

![image](https://github.com/user-attachments/assets/7c55b455-f178-4405-879a-f6f2b286d940)


## Result:
Thus the program was executed and the output was verified successfully.
