# perfect
/******************************************************************************

                            Online C Compiler.
                Code, Compile, Run and Debug C program online.
Write your code in this editor and press "Run" button to compile and execute it.

*******************************************************************************/

#include <stdio.h>
#include<stdlib.h>
int main( int argc,char* argv[])
{
    int a,i,num,sum=0;
    num=atoi(argv[1]);
    for(a=1;a<num;a++)
    {
        if(num%a==0)
        sum=sum+a;
    }
    if(num==sum)
    {
    printf("%d is perfect no");
    }
    else
    {
    printf("%d is not perfect number");
    }
    return 0;
}



