# Practice
#include<stdio.h>
int main()
{
	char name[40];
	float cash;
	printf("Please enter the name and cash:");
	scanf_s("%s", name, 20);
	scanf_s("%f", &cash);
	printf("The %s family just may be $%.2f richer!\n", name, cash);
	return 0;
}
