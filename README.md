#include <stdio.h>

int main()
{ 
    int a, b;
 printf(" a: ");
 scanf_s("%d", &a);
 printf(" b: ");
 scanf_s("%d", &b);
 if((a==b)||(-a==-b))
 {
     printf("equal numbers");
     return 0;
 }
 else
 printf("unequal numbers");

    return 0;
}
