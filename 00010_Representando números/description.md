Agora é a sua vez de escrever uma função que _decodifique_ um número com três algarismos guardado no tabuleiro, como por exemplo 514:

<gs-board>
  GBB/1.0
    size 3 1
    cell 0 0 Rojo 5
    cell 1 0 Rojo 1
    cell 2 0 Rojo 4
    head 0 0
</gs-board>

Como você pode ver na imagem, cada um dos seus três algarismos aparece em uma célula diferente, e a leitura é feita da esquerda para a direita (ou seja, como lemos normalmente deste lado do mundo). A garra começará sempre na origem.

A ideia é que você use uma **variável** para ir armando o número, somando cada um de seus algarismos. Como experimentou no exercício anterior, em uma designação pode ser usado o valor que a variável já tinha, e dessa forma ir **acumulando** um resultado.

> Escreva a função `numero()`, que retorne o número codificado no tabuleiro. Para ler cada um de seus algarismos do tabuleiro, te damos uma função `algarismo()`, procure na Biblioteca.
