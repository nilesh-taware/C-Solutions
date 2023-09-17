#include <stdio.h>
 
int main()
{
  int i, a = 1, count; 
  

  while(a <= 100)
  {
    count = 0;
    i = 2;
    while(i <= a/2)
    {
      if(a%i == 0)
      {
        count++;
	break;
      }
      i++;	
    }	
    if(count == 0 && a != 1 )
    {
	printf(" %d ", a);
    }
    a++; 
  }
  return 0;
}
