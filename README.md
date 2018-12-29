# Hello
repository
hi
#include <stdio.h>
 
main() {
   float x,y;
   char sign='+';
   while (sign != '0') {
      printf("Знак: ");
      scanf("%c%*c", &sign);
      if (sign == '0') { break; }
      
