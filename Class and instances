#include<stdio.h>
int main()
{
	int initialAge,age,t,i,a[10],j;
	scanf("%d",&t);
	for(i=0;i<t;i++)
	{
		scanf("%d",&initialAge);
		a[i]=initialAge;
	}

	for(i=0;i<t;i++)
	{
		if(a[i]<0)
		{
			printf("\nAge is not valid, setting age to 0.");
			age=0;
		}
		else
		{
			
			age=a[i];
		}
		for(j=0;j<2;j++)
		{
			if(age<13)
			{
				printf("\nYou are young.");
			}
			else if(age<18)
			{
				printf("\nYou are a teenager.");
			}
			else
			{
				printf("\nYou are old.");
			}
			age=age+3;
			
		}
		printf("\n");
		
	}
	
}
