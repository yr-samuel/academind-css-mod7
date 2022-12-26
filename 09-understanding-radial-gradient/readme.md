### Entendendo sobre Radial Gradient

- Primeiramente, o radial-gradient() é uma função do CSS que é passada como valor para o background-image, logo é reconhecido como imagem.

- O _radial-gradient_ pode receber varios argumentos, como: multiplas cores, formato e posição

  - É possível fazer as seguintes formas:

    - _background-image: radial-gradient(blue, red, yellow)_, e então ele formará um gradiente começando do azul, passando pelo vermelho e indo até o amarelo, e o formato padrão que terá é de uma elipse.
    - _background-image: radial-gradient(circle, blue, red, yellow)_, onde agora o formato do gradiente de fato é um circulo ao invés de uma elipse.
    - _background-image: radial-gradient(circle at top right, blue, red, yellow)_, aqui definimos o formato, as cores e também a posição onde o gradiente começará, nesse caso é a partir do lado direito superior, é possível também ao invés de passar esses valores pré-definidos, passar porcentagem, o primeiro valor refere ao eixo-x e o segundo ao eixo-y.
    - _background-image: radial-gradient(circle 20px at top right, blue, red, yellow)_, é possível também passar o tamanho que o gradiente terá.

  - No radial-gradient pode ser passado cor + tamanho/largura que a cor ocupará, **red 50%** igualmente ao linear-gradient.

  - Há algumas posições também pré-definidas alem de top, bottom, etc.
