//Sobre o void.   

#include <stdio.h>
int fatorial(int n) {
    // Condição de parad
    if (n == 0)
        return 1;

    // Chamada recursiva
    return n * fatorial(n - 1);
}

int main() {
    int num = 5;
    int resultado = fatorial(num);
    printf("O fatorial de %d é %d\n", num, resultado);
    return 0;
}



// Duvida sobre o codigo 
#include <stdio.h>

int fatorial(int numero)
{
    if (numero == 1)
    {
        return 1;
    }

    return numero * fatorial(numero - 1);
}

void main()
{
    int resultado = fatorial(5);
    printf("%d", resultado);
}
