#include<stdio.h>
int main(){
	int i;
	int sum;
	for(sum=0,i=0;i<=10;i++,i++)//如果想求奇数累加则将i=0改为i=1
	{
		sum=sum+i;
	}
	printf("%d\n",sum);
	return 0;
}
