# M6-D1
AIM:
write a C program to calculate the area of a triangle using pointer
PROGRAM:
```
#include <stdio.h>
int main()
{
    float a,b,*p,*q,area;
    scanf("%f %f",&a,&b);
    p=&a;
    q=&b;
    area=((*p)*(*q))/2;
    printf("area of the triangle with base %.6f and height%.6f=%.6f",*p,*q,area);
    return 0;
}
```
OUTPUT:
<img width="1235" height="323" alt="image" src="https://github.com/user-attachments/assets/2c49c9e4-62a0-4631-a7f4-64a8b9c7d8f9" />
REUSLT:
Thus the code run successfully!
