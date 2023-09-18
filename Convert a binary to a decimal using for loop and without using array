#include <stdio.h>

void main()
{       int n1, n,p=1;
	int dec=0,i=1,j,d;

     printf("\n\n  Convert Binary to Decimal:\n ");
     printf("-------------------------\n");

	printf("Input a binary number :");
	scanf("%d",&n);
	n1=n;
	for (j=n;j>0;j=j/10)
	{  
          d = j % 10;
            if(i==1)
                  p=p*1;
            else
                 p=p*2;

	   dec=dec+(d*p);
	   i++;
	}
        printf("\nThe Binary Number : %d\nThe equivalent Decimal  Number : %d \n\n",n1,dec);
}
