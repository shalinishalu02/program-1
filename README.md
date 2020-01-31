#include <stdio.h>

int main()
{
   int n,a[10],i,sum=0;
   float avg;
   printf("enter the number:");
   scanf("%d",&n);
   for(i=0;i<=n;i++)
   {
   scanf("%d",&a[i]);
   }
   for(i=0;i<=n;i++)
   {
   sum+=a[i];
   avg=sum/n;
    printf("sum=%d,average=%f",sum,avg);
   }
    return 0 ;
   
}
         
         
         
         output// enter the number :5
         3
         6
         6
         5
         4
         
         sum=24,average=4.000000
