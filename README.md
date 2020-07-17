# Accessibility WebPage
It is a simple plugin for help you implement feature of the acessibility in your web page.

# Como usar

Clone it and you will see that exist a page index.html with a sample. In this page exist three button:

![Página de exemplo](https://github.com/fabioalmeida100/AccessibilityWebPage/blob/master/assets/sample-image/sample-image.jpg?raw=true)

* A+ : button for increase the font size. This button need an *id="aumentar"*
* A : button for reset font-size. This button need an *id="normal"*
* A- : button for decrease the font size. This button need an *id="diminuir"*

So, you need create three button with ids above for control the font size and for indicate for the script wich elements you want increase/decrease the font size with the class CSS `.acessibilidade` in the elements HTML. See a example below: 

```
  <p class="acessibilidade">
      Increase/decrease font size!
  </p>

  <p>
      Nothing here <p>
  </p>
```
