#include <stdio.h>
#include <stdlib.h>
int main()
{
int base, i=1, multiplicacion=1, potencia;

printf("\nIngrese la base\n");
scanf("%d",&base);
printf("\ningrese la potencia\n");
scanf("%d",&potencia);
for(i=1;i<=potencia;i++)
{
multiplicacion= multiplicacion*base;
}
printf("\n\tEl resultado es:%d", multiplicacion);
system("pause");
return 0;
}
