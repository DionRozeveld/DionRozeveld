#include<stdio.h>
#include<cs50.h>
int main(void)
int a[] = {23, 45, 2, 13, 0};
int main (void)
{
  for (int k = 0; k < 5 - 1; k++)
  for(int i = 0; i < 5 - 1; i++)
  if (a[i] > a[i + 1])
  {
    int aTemp;
    aTemp = a[i];
    a[i] = a[i + 1];
    a[i + 1] = aTemp;
   }
   for (int j = 0; j < 5; j++)
   printf("%i", a[j]);
   printf("\n")
   }
