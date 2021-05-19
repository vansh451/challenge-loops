//challenge-loops
#include<stdio.h>
#include<conio.h>

int main()
{
    //initialisation
    int i=0;
    int j=0;
    //condtion
    for(i=1;i<=6;i++){
        for(j=1;j<=i;j++)
        {
            //inner loop body
            printf("01");
        }
        //outer loop body
        printf("\n");
    }
    return 0;
}
