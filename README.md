231페이지, 연습문제 8번


#define _CRT_SECURE_NO_WARNINGS
#include <stdio.h>

int main()
{
	int a = 1;
	int Sum = 0;

	do
	{
		Sum += a;
		a++;
	} 
	while (a <= 10);

		printf("%d", Sum);
	
}

------------------------------------------
231페이지 for문, if문, continue를 사용 하여 1부터 100지의 수 중  홀수만 출력하는 프로그램


#include <stdio.h>

int main()
{
	int a;

	for (a = 1; a <= 100; a++)
	{
		if (a % 2 == 0)
		{
			continue;
		}
		printf("%d", a);
	}
	return 0;
}
