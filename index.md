#include<stdio.h>
int main()
{
     int number[7]={11,12,13,14,15,16,17};
     int ans[7];
     int add,all=0;
     float avg;
     for(add=0;add<8;add++)
{     
     all+=number[add];
}    
avg=all/7;
printf("the sum is%d",all);
printf("\nAverage is%f",avg);
printf("\nVeriance For Each Number");
for(add=0;add<7;add++)
{
     ans[6]=(number[add]-avg)*(number[add]-avg);
     printf("\n %d", ans[add]);
}
return 0;
}
 
