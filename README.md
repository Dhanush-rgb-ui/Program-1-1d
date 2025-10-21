# Module-1 Day-4 SEB
## AIM:
To write a C Program for analysis of people of certain age groups who are eligible for getting a suitable college admission if their condition and norms get satisfied using nested if statement. Assume eligible age is 18 - 25. Total marks >=180.
## For example:
<img width="401" height="115" alt="image" src="https://github.com/user-attachments/assets/ea63558d-e59f-4665-88dd-9831d66d6869" />

## Program:
```c
#include <stdio.h>
int main()
{
    int a,b;
    scanf("%d %d",&a,&b);
    if (a>=18 && a<=25){
        if(b>=180){
            printf("He/She is eligible for college admission");
        }
        else {
            printf("His/Her age is above the upper age limit for college admission or his/her total marks is less than 180.");
        }
    }
    else{
        printf("Not eligible for college admission");
    }
    return 0;
    }
```
## Result:
<img width="1368" height="112" alt="image" src="https://github.com/user-attachments/assets/a8401e25-164f-4a63-afd6-97dc6bacf6b1" />
