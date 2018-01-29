Vamos começar com um problema: temos uma célula com uma certa quantidade de pedras verdes e queremos que elas sejam copiadas na célula mais próxima ao Norte. Obviamente, não sabemos de antemão quantas pedras haverá e além disso queremos escrever um procedimento que sirva para qualquer caso.

Vamos tentar pensar na estratégia que seguiríamos:

1. Nos movemos ao Norte, que é onde devem ser colocadas as pedras.
2. Uma vez que estamos na posição Norte, colocamos a mesma quantidade de pedras que havia na célula inicial... mas, como fazemos para saber isso se já nos movemos e a garra pode olhar apenas para a célula atual? :fearful:
3. Bom, recordando que as funções **não tem efeito real** sobre o tabuleiro, poderíamos armar uma função que volte para o Sul e nos diga quantas pedras há.
4. Com esse dado podemos fazer um velho e querido `ColocarN` e terminar nossa tarefa.

Como não queremos que você quebre a cabeça com isso (por enquanto :smirk:), te daremos o código Gobstones que implementa nossa estratégia para que você teste:

``` gobstones
procedure CopiarVerdesAoNorte() {
  Mover(Norte)
  ColocarN(pedrasVerdesAoSul(), Verde)
}

function pedrasVerdesAoSul() {
  Mover(Sul)
  return (nroPedras(Verde))
}
```

> Escreva esta primeira versão no editor e veja como cumpre com o objetivo.