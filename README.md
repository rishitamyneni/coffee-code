# coffee-code
#include<stdio.h>
int main()
{
 int x,p;
 scanf("%d %d",&x,&p);
 int sum=x,a;
 while(x!=1)
 {
  a=(x*p)/100;
  x=x-a;
  sum+=x;
  }
  printf("%d\n",sum);
  return 0;
  }
  
