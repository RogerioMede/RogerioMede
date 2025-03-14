#include <stdio.h>

int main() {
    int escolha;
    
    printf("### ainda nao decedido ###\n");
    
   
    printf("1. Pergunta e Resposta\n");
    printf("2. Cobra na Caixa!\n");
    printf("3. Gousmas War\n");
    printf("4. Sair\n");
    
    printf("Escolha uma opção (1-4): ");
    scanf("%d", &escolha);
    
    switch (escolha) {
        case 1:
            printf("Você escolheu: Pergunta e Resposta\n");
            break;
        case 2:
            printf("Você escolheu: Cobra na Caixa!\n");
            break;
        case 3:
            printf("Você escolheu: Gousmas War\n");
            break;
        case 4:
            printf("Saindo... Até logo!\n");
            break;
        default:
            printf("Opção inválida! Escolha um número entre 1 e 4.\n");
    }
    
    return 0;
}
