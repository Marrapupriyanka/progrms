# progrms#include<stdio.h>
int main()
{
int a[100][100];
	int i,j,r,c,sum; 
	printf("Enter how many rows \n");
	scanf("%d",&r);
	printf("Enter how many cols \n");
	scanf("%d",&c);
	printf("Enter elements into array \n");
	for(i=0;i<r;i++)
	{
		for(j=0;j<c;j++)
		{
			scanf("%d",&a[i][j]);
		}
	}
		for(i=0;i<r;i++)
	{
		sum=0;int m;
		scanf("%d",&m);

		for(j=0;j<c;j++) 
		{
			sum=sum+a[m-1][j]	;
		}
		printf(" %d row sum= %d \n",m,sum);
		break;		
}
	}
