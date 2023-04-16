//133페이지, 세 자리 자연수의 각 자리 수 구하기

#define _CRT_SECURE_NO_WARNINGS
#include <Stdio.h>

int main()
{
	int a, r1, r2, r3;

	printf("세 자리 정수를 입력하세요.\r\n");
	scanf("%d", &a);


	r1 = a / 100;
	r2 = a % 100 / 10;
	r3 = a % 10;

	printf("%d, %d, %d", r1, r2, r3);
}


------------------------------------------------
//136페이지, 3의 배수 판별하기

#define _CRT_SECURE_NO_WARNINGS
#include <Stdio.h>

int main()
{
	int a;

	printf("정수를 입력하세요.\r\n");
	scanf("%d", &a);

	printf("%d", a % 3 == 0);
}


-------------------------------------
//149페이지, 세 번째 비트값 구하기

#define _CRT_SECURE_NO_WARNINGS
#include <Stdio.h>

int main()
{
	int a;

	printf("정수를 입력하세요.\r\n");
	scanf("%d", &a);

	printf("세 번째 비트:%d", a & 0b100 >> 2);
}


-----------------------------------------------
153페이지, 입력받은 수보다 큰 다음 짝수 구하기

#define _CRT_SECURE_NO_WARNINGS
#include <Stdio.h>

int main()
{
	int a;

	printf("정수를 입력하세요.\r\n");
	scanf("%d", &a);

	a += a % 2 == 0 ? 2 : 1;

	printf("다음 짝수 : %d", a);
}


--------------------------------------
159페이지, 가우스 함수

#define _CRT_SECURE_NO_WARNINGS
#include <Stdio.h>

int Gaus(double x)
{
	int g = (int)x;
	g = x - g < 0 ? g - 1 : g;
	return g;
}


int main()
{
	double d;
    printf("정수를 입력하세요.\r\n");
	
	scanf("%lf", &d);
    printf("Gaus : %d", Gaus(d));
}


-----------------------
160페이지 실전예제, 두 수의 대소 관계 파악하기

#define _CRT_SECURE_NO_WARNINGS
#include <Stdio.h>

int compare(int x, int y)
{
	int r = x - y < 0 ? -1 : x == y ? 0 : 1;
	return r;
}


int main()
{
	int x, y;
    printf("두 정수를 공백으로 구분하여 입력하세요.\r\n");
	
	scanf("%d %d", &x, &y);

	int c = compare(x, y);
	printf(c < 0 ? "%d < %d" : c == 0 ? "%d = %d" : "%d > %d", x, y);

}
