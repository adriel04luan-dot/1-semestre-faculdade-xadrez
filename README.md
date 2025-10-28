#include <stdio.h>

int main() {
    // ==============================================================
    // Simulação de movimentos de peças de xadrez
    // Peças: Torre, Bispo e Rainha
    // Estruturas utilizadas:
    // - Torre: for
    // - Bispo: while
    // - Rainha: do-while
    // ==============================================================

    // ==============================================================
    // Movimento da Torre — 5 casas para a direita
    // ==============================================================
    int casasTorre = 5; // Número de casas a serem percorridas
    for (int i = 1; i <= casasTorre; i++) {
        printf("Direita\n");
    }

    // ==============================================================
    // Movimento do Bispo — 5 casas na diagonal para cima e à direita
    // ==============================================================
    int casasBispo = 5; // Número de casas a serem percorridas
    int contador = 1;
    while (contador <= casasBispo) {
        // Para diagonal: imprimir a combinação de duas direções
        printf("Cima Direita\n");
        contador++;
    }

    // ==============================================================
    // Movimento da Rainha — 8 casas para a esquerda
    // ==============================================================
    int casasRainha = 8; // Número de casas a serem percorridas
    int passo = 1;
    do {
        printf("Esquerda\n");
        passo++;
    } while (passo <= casasRainha);

    // ==============================================================
    // Fim do programa
    // ==============================================================

    return 0;
}
