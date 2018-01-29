Embora dissemos de maneira explícita, com certeza você já se deu conta: as variáveis também são **expressões**, e portanto podem ser usadas nos mesmos lugares que todas as que já conhecia:

* como **argumentos** de funções ou procedimentos;
* em um `repeat`, indicando quantas iterações haverá;
* em um `if` ou `while`, como parte da condição;
* e como valor de retorno de uma função.

E claro, también podem ser usadas em uma **designação**, ou seja que podemos designar um valor a uma variável usando uma variável! :fearful:

Vejamos alguns exemplos disso que está parecendo algo complicado:

``` gobstones
algo := 25
quantoVale := algo * 2
```

Nada muito novo, `algo` denota `25` e isso multiplicado por `2` vale `50`.

``` gobstones
quantoVale := Norte
quantoVale := oposto(quantoVale)
```

Opa, aqui tem  que pensar um pouco mais. :frowning:
<br>
Ao avaliar `oposto(quantoVale)`, a variável `quantoVale` já tinha o valor `Norte` e portanto toda a expressão denotará `Sul`; isso será o que finalmente será recordado sob a etiqueta `quantoVale`.

``` gobstones
algo := 10
quantoVale := 5
quantoVale := (algo * quantoVale) + quantoVale
```

E aqui o que acontece?

> Este último caso deixamos para você, pense e escreva no editor o valor ao qual a variável etiqueta. Novamente, você não precisa escrever o código Gobstones, do contrário o número seria obtido  simplesmente por avaliar `quantoVale` logo depois de todas as designações.