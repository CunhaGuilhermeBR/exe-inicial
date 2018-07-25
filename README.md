# exe-inicial
#include <stdio.h>
#include <stdlib.h>
#include <locale.h>
#define MAX 100
int main()
{

    int i, b;
    int v[6] ; 
    setlocale(LC_ALL, "Portuguese");
     for(i=0; i<=5; i++){
            scanf("%d", &v[i]);
            printf("\nvalor:%d ", v[i]);
     }
     
    
    return 0;
}
