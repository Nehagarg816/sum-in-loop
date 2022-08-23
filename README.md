# sum-in-loop
This is a program for addition of required number of times using loop.
#include<stdio.h>
#include<conio.h>
void main()
{
	int n,sum=0;
	do
	{
		printf("Enter a number:");
		scanf("%d",&n);
		sum+=n;
	}
	while(n!=0);
	printf("Sum is %d",sum);
}




Output:
Enter a number:5
Enter a number:6
Enter a number:7
Enter a number:0
sum is 18
