### Usando a propriedade background de forma abreviada.

- Para usar a forma abreviada da propriedade background devemos passar os valores numa certa sequência, que é a seguinte

        -color -image -position/-size -repeat -origin -clip -attachment

- Mas então, mesmo que eu só vá passar uma imagem, eu tenho que passar uma cor por causa dela ser a primeiro valor pedido?
  - É possível passar os dois ao mesmo tempo, porém não é obrigatório, se colocarmos somente a imagem, que é via **url()**, a propriedade entenderá que esse tipo de valor não se encaixa na posição _cor_, então ele passa para a proxima que de fato é a imagem, assim funciona com todos os outros valores a serem passados também.

---

    background: url("freedom.jpg") 50% top/cover padding-box border-box;

É O MESMO QUE:

    background: url("freedom.jpg");
    background-size: cover;
    background-repeat: no-repeat;
    background-position: 50% top;
    background-origin: padding-box;
    background-clip: border-box;
