Finalmente nossa humilde horta deu seus frutos e já estamos em condições de colher os tomates. :grin: :tomato:

Como faremos isso? Muito simples, **tiraremos** os tomates das nossas 3 plantas-células e os deixaremos na origem. Vejamos que aspecto tem a nossa  horta:

**Antes de colher**

<gs-board>
  GBB/1.0
    size 4 1
    cell 1 0 Rojo 3
    cell 2 0 Rojo 7
    cell 3 0 Rojo 4
    head 0 0
</gs-board>

**Depois de colher**

<gs-board>
  GBB/1.0
    size 4 1
    cell 0 0 Rojo 14
    head 0 0
</gs-board>

Para que nos sirva para a próxima colheita também, vamos escrever um procedimento suficientemente _inteligente_ que funcione com qualquer quantidade de tomates (a horta por enquanto não aumentará, então isso não precisa ser um motivo de preocupação). Afortunadamente sua _caixa de ferramentas_ não vem vazia, te deixamos algumas coisas na Biblioteca:

* a função `quantidadeTomates()` que indica quantos tomates há na planta (célula) atual;
* o procedimento `ColherPlanta()` que colhe todos os tomates que há em uma planta;
o procedimento `DeixarTomates(quantidade)` que deixa a quantidade de tomates indicada pelo parâmetro na célula atual.

Além disso, te ajudamos um pouco com a estrutura da sua solução para que você só tenha que se concentrar no que queremos que você aprenda aqui: <del>a colher tomates</del> **a usar variáveis**. :wink:

> Complete o procedimento `ColherHorta()` com a ajuda que já  demos pra você.
