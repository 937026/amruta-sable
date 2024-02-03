#include<stdio.h>
#include<time.h>
#include<stdlib.h>
int main()
{
    int bt[20],p[20],wt[20],tat[20],i,j,n,total=0,totalT=0,pos,temp;
    float avg_wt,avg_tat;
    time_t t;
    printf("Enter number of process:");
    scanf("%d",&n);
    printf("Enter arrival time of processes :- ");
    for(i=0; i<n; i++) {
        printf("A%d  :- ",i+1);
        scanf("%d",&p[i]);
    }
    srand((unsigned) time(&t));
    printf("\nEnter Burst Time: \n");
