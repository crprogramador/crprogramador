#include <stdio.h>
#include <locale.h>
int main() {
    int c = 1;
    int n = 0;
    setlocale (LC_CTYPE "Portuguese");
    while (c <= 100) {
        n = n + 1;
        printf("Vou me portar melhor nas aulas, estar com atenção, fazer os trabalhos pedidos, não jogar durante as aulas, e deixar a sala como a encontrei. (Mensagem Nº %d)\n", n);
        c++;
    }

    return 0;
}
