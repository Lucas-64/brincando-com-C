#include <stdio.h>
#include <stdlib.h>

int main()
{
    int mary, john, result,cont, i;
    printf("Enter the number of moves: \n");
    scanf("%d", &i);
    
    
    for(cont = 0; cont != i; cont++){
       result = rand() % 2;
       printf("%d ", result);
       if(result == 1){
           printf("Mary winner!! \n");
           mary++;
       }else{
           printf("John winner!! \n");
           john++;
       }
    }
    
    printf("Mary has won %d times and John has won %d times", mary, john);

    return 0;
}
