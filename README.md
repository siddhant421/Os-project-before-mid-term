#include<stdio.h>
#include<string.h>
#include<conio.h>
void main()
{
    char p[10][5],temp[5];
    int i,j,pt[10],waitingtime[10],totlwt=0,prty[10],temp1,n;
    float avgwaitingtime;
    printf("enter no. of processes:");
    scanf("%d",&n);
    for(i=0;i<n;i++)
    {
        printf("enter process%d name:",i+1);
        scanf("%s",&p[i]);
        printf("enter process time:");
        scanf("%d",&pt[i]);
        printf("enter priority:");
        scanf("%d",&pr[i]);
    }
