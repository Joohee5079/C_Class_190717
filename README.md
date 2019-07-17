# C_Class_190717
윤년 



#include <stdio.h>
void main()
{
	int i;
		for (i = 1; i <= 2019; i++)
		{
			if (i % 4 == 0 && i % 100 != 0 || i % 400 == 0)printf("%d\n", i);
			//if (i % 400 == 0)printf("%d\n", i);
		}
}
