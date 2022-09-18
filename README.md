# projeto-simples-c
projeto(calculadora)
#include <stdio.h>

int main()
{
    int num1 , num2, operacao;
    printf("Digite dois números: ");
    scanf("%d%d", &num1, &num2);
    printf("1 - Adição  2 - Subtração  3 - Multiplicação  4 - Divisão  5 - Resto\n");
    scanf("%d", &operacao);
    switch (operacao)
    {
    
    case 1:
    printf("%d + %d = %d\n", num1, num2, num1 + num2);
    break;
    
    case 2:
    printf("%d - %d = %d\n", num1, num2, num1 - num2);
    break;
    
    case 3:
    printf("%d * %d = %d\n", num1, num2, num1 * num2);
    break;
    
    case 4:
    printf("%d / %d = %d\n", num1, num2, num1 / num2);
    break;
    
    case 5:
    printf("%d % %d = %d", num1, num2, num1 % num2);
    break;
    
    default:
    printf("Opção desconhecida");
    }
    return 0;
}

