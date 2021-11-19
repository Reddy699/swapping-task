# swapping-task
By rayannagari bhargavi
#include<stdio.h>
main()
{
int a=10;
int b=15;
printf("before swap a=%d b=%d",a,b);
a+=b;
b-=a;
a-=b;
printf("\nafter swap a=%d b=%d",a,b);
return 0;
}
