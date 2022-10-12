### Estilizando imagens

- Por padrão, quando colocamos uma tag _img_ e apontamos para uma imagem, o tamanho desse elemento será da altura e largura original da imagem. E a partir daqui temos duas vertentes:

  - Se o elemento pai da tag **img**, for um elemento do tipo _inline_, a imagem ficará com o seu tamanho original.
  - Se o elemento pai for do tipo _inline-block_ ou _block_, aí ja é possível passar um tamanho pra esse pai e usar porcentagem para a a tag **img** que irá se comportar de acordo com o tamanho do container pai.

- Apenas um adendo, no curso fala que não é possível fazer muita coisa com a tag **img**, porém atualmente temos a propriedade _object-fit_ que funciona como se fosse um _background-size_.
