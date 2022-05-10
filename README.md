#include <stdlib.h>
#include <stdio.h>
#define row 4
#define colume 4


void main()
{
	int ro, co, smaller;
	int mtrx[row][colume] = { {2,2,2,3},{2,2,2,2} ,{2,2,2,9} ,{2,2,2,2} };

	for (ro = 0; ro < colume; ro++)
	{
		for (co = 0; co < row; co++)
		{
			if ((ro * 3 == co) || (co * 3 == ro))
			{
				printf("%d is 3 times bigger then %d \n", ro, co);


			}
		}
	}


}
