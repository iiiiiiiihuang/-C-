# -C-
一定要坚持（搞钱搞钱搞钱！！！）
选择语句
#define _CRT_SECURE_NO_WARNINGS 1
#include<stdio.h>
int main()
{
	int age = 29;
	if (age < 18)
		printf("未成年\n");
	//else if(18<=age<28)//不能这样，这是错的
	else if (age >= 18 && age < 30)//正确的
		printf("青年\n");
	else if (age >= 30 && age < 60)
		printf("中年\n");
	else
		printf("老年\n");
	return 0;
}
