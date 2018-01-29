Como você viu nos exercícios prévios, com uma **variável** podemos _etiquetar_ um **valor** para utilizar mais tarde, escrevendo por exemplo `numerozinho := 2`. A este comando que serve para dar um valor a uma variável chamamos **designação** e escrevemos `:=` (_dois pontos, igual_).

Uma variável pode etiquetar apenas **um valor**, e cada vez que designamos um novo o anterior é perdido - pode imaginar como uma etiqueta real: só é possível colar a etiqueta em um lugar de cada vez.

Vejamos outro exemplo:

``` gobstones
function direcaoMisteriosa() {
  resultado := Norte
  resultado := Leste
  resultado := Sul
  return (resultado)
}

```

> Do mesmo modo que fizemos no exercício anterior, escreva no editor o valor que você acha que devolve a função `direcaoMisteriosa()`.