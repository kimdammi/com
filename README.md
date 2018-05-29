#include <stdio.h>


int factorial(int n)
{printf("factorial(%d)\n",n);

if (n<=1)
	return 1;
else
	return n*factorial(n-1);
}

int fib(int n)
{

if (n==0)
	return 0;
if(n==1)
	return 1;

	return (fib(n-1)+fib(n-2));
}

int main()
{
	int n;
	printf("정수 입력 : ");
	scanf("%d",&n);
	printf("fib(%d) = %d\n",n,fib(n));

	return 0;

}

