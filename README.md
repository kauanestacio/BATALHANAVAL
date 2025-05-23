Funcionamento: 

O programa simula o posicionamento de dois navios em um tabuleiro de Batalha Naval. Ele utiliza uma matriz 10x10 para representar o tabuleiro, onde:

0 representa água.

3 representa uma parte de um navio.

O programa posiciona dois navios:

Navio Horizontal: Posicionado na linha 2, começando na coluna 3.

Navio Vertical: Posicionado na linha 5, começando na coluna 6.
;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;

Definição do Tabuleiro:

O tabuleiro é representado por uma matriz 10x10 de inteiros, inicializada com 0, indicando que todas as posições estão vazias (água).

Posicionamento dos Navios:

O código posiciona dois navios de tamanho 3:

Um navio horizontalmente, começando na linha 2 e coluna 3.

Outro navio verticalmente, começando na linha 5 e coluna 6.

Cada posição ocupada por um navio é marcada com o número 3 na matriz.

Exibição do Tabuleiro:

O tabuleiro é impresso no console, onde:

~ representa água.

O representa uma parte do navio.

;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;

printf("Tabuleiro de Batalha Naval:\n");: Exibe um título indicando que o tabuleiro será mostrado a seguir.

for: Dois loops aninhados percorrem todas as posições da matriz tabuleiro.

if e else if: Condicionais que verificam o valor de cada posição:

Se for 0, imprime ~ (representando água).

Se for 3, imprime O (representando uma parte do navio).

printf("\n");: Após cada linha do tabuleiro, imprime uma nova linha para formatar a saída.




