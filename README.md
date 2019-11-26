# Aaron_LKB
#include<stdio.h>
int main()
{
	int max_value(int array[][4]);
	int a[3][4]={{1,3,5,7},{2,4,6,8},{79,89,86,78}};
	printf("最大的元素%d\n",max_value(a));
	return 0;
}
int max_value(int array[][4]) 
	int i,j,max=array[0][0];
	for(i=0;i<3;i++)
	for(j=0;j<4;j++)
	if(array[i][j]>max)max=array[i][j];
	return (max);
	
}
