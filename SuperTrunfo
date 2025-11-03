#include <stdio.h>

int main(){
   
    char estado;
    char codigo[5];
    char cidade[20];
    int populacao;
    float area;
    float pib;
    int pontost;
    float densidade;
    float pibpc;
    float superpoder;

    char estado2;
    char codigo2[5];
    char cidade2[20];
    int populacao2;
    float area2;
    float pib2;
    int pontost2;
    float densidade2;
    float pibpc2;
    float superpoder2;

    
    printf("Desafio super trunfo\n");

    // Entrada da primeira carta
    printf("Carta 1\n");
    printf("Digite uma letra de A a H: \n");
    scanf(" %c", &estado); // o espaço antes do formato ignora espaços e quebra de linha

    printf("Digite a letra que escolheu mais um número de 01 a 04: \n");
    scanf("%s", codigo);

    printf("Digite a cidade: \n");
    scanf("%s", cidade);

    printf("Digite sua população: \n");
    scanf("%d", &populacao);

    printf("Digite a área\n");
    scanf("%f", &area);

    printf("Digite seu PIB\n");
    scanf("%f", &pib);

    printf("Digite a quantidade de seus pontos turísticos: ");
    scanf("%d", &pontost);

    densidade = populacao / area;

    pibpc = pib / populacao;

    superpoder = populacao + area + pib + pontost + ( 1 / densidade) + pibpc;


    // Entrada de segunda carta
    printf("\nCarta 2\n");
    printf("Digite uma letra de A a H: \n");
    scanf(" %c", &estado2); 

    printf("Digite a letra que escolheu mais um número de 01 a 04: \n");
    scanf("%s", codigo2);

    printf("Digite a cidade: \n");
    scanf("%s", cidade2);

    printf("Digite sua população: \n");
    scanf("%d", &populacao2);

    printf("Digite a área\n");
    scanf("%f", &area2);

    printf("Digite seu PIB\n");
    scanf("%f", &pib2);

    printf("Digite a quantidade de seus pontos turísticos: ");
    scanf("%d", &pontost2);

    densidade2 = populacao2 / area2;

    pibpc2 = pib2 / populacao2;

    superpoder2 = populacao2 + area2 + pib2 + pontost2 + ( 1 / densidade2) + pibpc2;


    printf("Primeira carta => Seu estado é: %c - Seu código: %s - Sua cidade: %s - Sua população: %d - Área: %.2f - PIB: %.2f - Pontos turísticos: %d - Densidade populacional: %f - PIB per capita: %f - Super poder: %.2f\n", estado, codigo, cidade, populacao, area, pib, pontost, densidade, pibpc, superpoder);
    printf("Segunda carta => Seu estado é: %c - Seu código: %s - Sua cidade: %s - Sua população: %d - Área: %.2f - PIB: %.2f - Pontos turísticos: %d - Densidade populacional: %f - PIB per capita: %f - Super poder: %.2f\n", estado2, codigo2, cidade2, populacao2, area2, pib2, pontost2, densidade2, pibpc2, superpoder2);
   
    printf("\nComparação das cartas\n");

    printf("\nPopulação: %d venceu (%d)\n", (populacao > populacao2 ? 1 : 2), (populacao > populacao2 ? 1 : 0));
    printf("Área: %d venceu (%d)\n", (area > area2 ? 1 : 2), (area > area2 ? 1 : 0));
    printf("PIB: %d venceu (%d)\n", (pib > pib2 ? 1 : 2), (pib > pib2 ? 1 : 0));
    printf("Pontos turísticos: %d venceu (%d)\n", (pontost > pontost2 ? 1 : 2), (pontost > pontost2 ? 1 : 0));
    printf("Densidade populacional: %d venceu (%d)\n", (densidade < densidade2 ? 1 : 2), (densidade < densidade2 ? 1 : 0));
    printf("PIB per capita: %d venceu (%d)\n", (pibpc > pibpc2 ? 1 : 2), (pibpc > pibpc2 ? 1 : 0));
    printf("Super poder: %d venceu (%d)\n", (superpoder > superpoder2 ? 1 : 2), (superpoder > superpoder2 ? 1 : 0));

    return 0;

}
