Essa ideia de ir modificando uma variável usando o valor que já tinha e algo mais é conhecida como **acumulador** ou **contador**, e muitas vezes na comunidade é usada em demasia.

Não caia no vício de querer usar variáveis para tudo. Não esqueça tudo o que você já aprendeu e o poder das funções! Como sempre falamos, a solução **mais simples** é a melhor. Veja como também poderia ser resolvido sem usar variáveis:

``` gobstones
function numero() {
  return (centena() + dezena() + unidade())
}


function centena() {
  return (algarismo() * 100)
}


function dezena() {
  Mover(Leste)
  return (algarismo() * 10)
}


function unidade() {
  MoverN(2, Leste)
  return (algarismo())
}
```
