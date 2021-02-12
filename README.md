#include <stdio.h>
#include <stdlib.h>

int main()
{
    int i,j,rows;
    printf("Enter the number of rows: ");
    scanf("%d",&rows);

    for(i=1; i<=rows; i++){
        for(j=1; j<=i; j++){
            if(j%2==1)
            {
                printf("0");
            }
            else{
                printf("1");
            }
        }
        printf("\n");
    }
    getch();
    return 0;
}

When the above code executed, it produces the following results

Enter the number of rows: 8
0
01
010
0101
01010
010101
0101010
01010101
