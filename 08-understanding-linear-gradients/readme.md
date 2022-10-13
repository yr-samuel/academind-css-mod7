### Entendendo sobre Linear Gradients

- Primeiramente, o linear-gradient() é uma função do CSS que é passada como valor para o background-image, logo é reconhecido como imagem.

- O _linear-gradient_ pode receber varios argumentos, como: cor, direção, cor e tamanho

  - A direção que o gradiente vai seguir é sempre passada como primeiro argumento, algo como: **linear-gradient(to bottom)**, **linear-gradient(to top left)**.
  - A cor podemos passar com o nome, como hexadecimal, como rgb ou rgba: **linear-gradient(blue)**, **linear-gradient(blue, #f00)**, **linear-gradient(rgb(255, 0, 255), rgba(0, 0, 0, 0.4))**.
  - Cor e tamanho, aqui dizemos até onde a cor que escolhemos vai, então por exemplo: **linear-gradient(blue 30%, red 40%)**, quer dizer que a cor azul irá preencher até os 30% do elemento na direção que foi colocada, e o vermelho irá preencher a partir dos 40% do elemento até o final, e o intervalo entre 30% e 40% é onde acontecerá o gradient. Aqui por exemplo, se colocassemos: linear-gradient(blue 30%, red 30%), o azul terminaria nos 30% e o vermelho começaria nos 30%, no caso nem aconteceria o gradient.

- E por fim, é possível combinar todas essas opções, exemplo: **linear-gradient(top top right, #f00 50%, blue, rgba(255, 255, 0, 0.5))**
