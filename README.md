# Accessibility WebPage
Este é um simples plugin que irá ajudar você adicionar o recurso de acessibilidade para sua página Web. 

# Como usar

Ao clonar este projeto você verá que existe uma página index.html de exemplo. Nesta página existem três botões:

![Página de exemplo](https://github.com/fabioalmeida100/AccessibilityWebPage/blob/master/assets/sample-image/sample-image.jpg?raw=true)

* A+ : botão para aumentar a texto da página. Este botão precisa ter o *id="aumentar"*
* A : botão para aumentar a texto da página. Este botão precisa ter o *id="normal"*
* A- : botão para aumentar a texto da página. Este botão precisa ter o *id="diminuir"*

Portanto, você irá criar os três botões com os ids acima para manipular o tamanho da fonte e para você marcar quais elementos serão afetados pelo aumento/diminuição da fonte, basta você colocar a classe `.acessibilidade` nos elementos HTML. Veja no exemplo abaixo:

```
  <p>
      Só será afetado o elemento que tiver classe CSS <code>.acessibilidade</code>
  </p>

  <a href="" class="acessibilidade">Link</a>
```

# Como funciona

Neste recurso, cada elemento que possui a classe CSS `.acessibilidade` é selecionado quando se clica em alguns dos botões e é aplicado um estilo inline que alterar o atributo `fonte-size`do elemento HTML.
