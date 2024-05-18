# C-mod
find mod of 2 int.
#include <stdio.h>
#include <stdlib.h>
int main()
{
   double number;
   printf("Write a number for the value of cube's side: ");
   scanf("%lf", &number);
   double cube;
   cube=number * number * number;
   printf("The volume of cube is %f", cube);
   return 0;
}
// Double cannot be defined as a float again.

#include <stdio.h>
#include <stdlib.h>
int main()
{
   double y=123.45678;
   double x;
   x=y;
   printf("%.5f\n", (double) x);
   return 0;
}
