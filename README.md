# Exercicio6

#include <stdio.h>
#include <stdlib.h>

int main()
{
    system("color 0b");
    int i, n[10];
    float m;

    for (i=0; i<=9; i++)
    {
        printf("Digite um numero: ");
        scanf("%d", &n[i]);
    }

    for (i=0; i<=9; i++)
    {
        m=n[i];
        printf("A metade de %d e: %.2f\n",n[i],m/2);
    }

    return 0;
}
