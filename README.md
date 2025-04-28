#include <iostream>

using namespace std;

int main()
{   int x, y, soma, sub, mult, resto;
    float div=0;
    printf ("\n operações sobre os inteiros");
    printf ("\n digite o 1 valor:");
    scanf ("%d",&x);
    printf ("\n digite o 2 valor:");
    scanf("%d",&y);

     soma = x + y;
    sub = x - y;
    mult = x * y;
    div = x / y;

    resto = x % y;
    printf("\n%d + %d = %d", x,y,soma);
    printf("\n%d - %d = %d", x, y, sub);
    printf ("\n%d * %d = %d", x, y, mult);
    printf("\n%d / %d = %.2f", x, y, div);
    printf("\n%d %% %d = %d", x, y, resto);


    return 0;
}
