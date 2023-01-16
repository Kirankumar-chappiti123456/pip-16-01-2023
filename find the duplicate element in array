#include <stdio.h>
int main()
{
     int num[20],i=0,j=0;
     int len=0;
     printf("enter the length:");
     scanf("%d",&len);
     printf("enter the number:");
     for(i=0;i<len;i++)
     scanf("%d",&num[i]);
     for(i=0;i<len;i++)
     {

         for(j=i+1;j<len;j++)
         {
             if(num[i]==num[j])
             {
                 printf("%d",num[i]);
             }
       }
     }
    
}


another way:
#include<stdio.h>
int main()
{
    int a[10],i=0,j=0,l;
    printf("enter the size of array:");
    scanf("%d",&l);
    printf("enter the array:");
    for(int i=0;i<5;i++)
    {
    scanf("%d",&a[i]);
    }
    for(i=0;i<l;i++)
    {
        for(j=0;j<l;j++)
        {
            if(a[i]==a[j])
            break;
        }

        if(i==j)
        {
            printf("%d",a[i]);
        }
    }
}
