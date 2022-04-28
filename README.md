# CT-1-ASSIGNMENT


#include<stdio.h>
int main()
{
    int n,m;
    int max,sub,mul,div;
    scanf("%d %d",&n,&m);
    max=n+m;
    sub=n-m;
    mul=n*m;
    div=n/m;
    printf("Addition=%d\nSubtraction=%d\nmultiplication=%d\ndivision=%d",max,sub,mul,div);
    return 0;}
