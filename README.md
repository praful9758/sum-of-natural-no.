# sum-of-natural-no.
#include<stdio.h>
main()
{
int i,n,sum=0;
printf("enter the limit:");
scanf("%d",&n);
for(i=n;i>0;i--)
{
  sum=sum+i;  
}
printf("sum of first %d natural numbers is %d",n,sum);
}
