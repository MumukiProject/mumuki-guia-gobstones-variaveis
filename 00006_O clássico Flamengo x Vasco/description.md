É isso aí, o jogo acabou. Façamos agora algo sério.

Vamos usar uma célula do tabuleiro para modelar o resultado de uma partida entre [Vasco](https://pt.wikipedia.org/wiki/Club_de_Regatas_Vasco_da_Gama) e [Flamengo](https://pt.wikipedia.org/wiki/Clube_de_Regatas_do_Flamengo): as pedras negras serão os gols do primeiro e as vermelhas serão os gols do segundo.

Por exemplo, assim veríamos uma partida em que Vasco fez 3 gols e Flamengo 1:

<gs-board>
  GBB/1.0
    size 2 1
    cell 0 0 Rojo 1 Negro 3
    head 0 0
</gs-board>

> Seu trabalho será escrever a função `quemGanhou()`, que devolva a cor da equipe vencedora.

Para reduzir um pouco seu trabalho (e se por acaso o futebol não está entre as suas preferências) escrevemos duas funções na Biblioteca; use-as em sua solução.