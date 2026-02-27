#include <stdio.h>

int main() {
    int numero;

    // Solicitar número al usuario
    printf("Ingrese un numero entero: ");
    scanf("%d", &numero);

    // Validar si es PAR o IMPAR
    if (numero % 2 == 0) {
        printf("El numero es PAR.\n");
    } else {
        printf("El numero es IMPAR.\n");
    }

    // Validar si es POSITIVO, NEGATIVO o CERO
    if (numero > 0) {
        printf("El numero es POSITIVO.\n");
    } else if (numero < 0) {
        printf("El numero es NEGATIVO.\n");
    } else {
        printf("El numero es CERO.\n");
    }

    return 0;
}
