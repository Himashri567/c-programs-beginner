#include<stdio.h>
int main()
{
	int a[3][3],i,j,trace=0;
	printf("Input elements in the matrix:");
	for(i=0;i<3;i++)
	for(j=0;j<3;j++)
	{
		printf("\n element-[%d][%d]:",i,j);
		scanf("%d",&a[i][j]);
	}
	printf("The matrix is:");
	for(i=0;i<3;i++)
	{
		printf("\n");
		for(j=0;j<3;j++)
			printf("%5d",*(*(a+i)+j));
	}
	for(i=0;i<3;i++)
		trace+=a[i][i];
	printf("\nThe sum of the diagonal elements of the matrix is:%d",trace);
	return 0;
}
