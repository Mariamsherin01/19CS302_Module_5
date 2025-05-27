# EX 25 C program to check whether a given character is a vowel or consonant using pointer
## AIM:
To write a C program to check whether a given character is a vowel or consonant using pointer

## Algorithm
1. Declare a char variable and a pointer pointing to it.
2. Assign the character 'I' to the variable using the pointer.
3. Check if the character is a vowel (a, e, i, o, u in both cases).
4. Print "vowel" if it is a vowel; otherwise, print "consonant".
 

## Program:
```
/*
C program to check whether a given character is a vowel or consonant using pointer
Developed by: Mariam Sherin
RegisterNumber: 212222060143
#include<stdio.h>
int main()
{
    char ch;
    char *p=&ch;
    scanf("%c",&ch);
    if(*p=='a'||*p=='e'||*p=='I'||*p=='o'||*p=='u')
    printf("%c is Vowel.",ch);
    else
    printf("%c is consonant.",ch);
}
*/
```

## Output:

![image](https://github.com/user-attachments/assets/f8b59e29-c77f-41db-8fb3-486df3437af7)


## Result:
Thus the program was executed and the output was verified successfully.
