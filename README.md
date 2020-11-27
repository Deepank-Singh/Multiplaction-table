# Multiplaction-table-C-programm
User can input any number and get a multiplication table of it. 

#include<stdio.h>
int main()
{
    int a, i, k;
    printf("Enter a number of which you want mutiplication table: \n");
    scanf("%d", &a);
    printf("Multiplaction table of %d : \n", a);
    for ( i = 1; i <= 10; i++)
    {
        /* code */
        k = a*i;
        printf("%d X %d = %d\n", a, i, k);
    }
    
    

    return 0;
}
