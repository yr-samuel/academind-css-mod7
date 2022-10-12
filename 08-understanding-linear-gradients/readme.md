### Trabalhando com imagens no layout.

- Como o container que envolvia a imagem era do tipo _block_, foi possível passar um tamanho pra esse container, e depois foi passado 100% para width da imagem que tem o container como referência por ele ser do tipo block.

- Atribuimos inline-block para o container, para que ele pudesse ficar na mesma linha que o texto de informação do depoimento, para deixar tanto o texto quanto a imagem centralizados no eixo-x, foi usado a propriedade _vertical-align_ tanto no container quanto no container dos textos.

- Foi aplicado uma sombra no container das imagens, porém acabou que por a imagem ser um elemento do tipo inline, acabou criando aquele espacinho de texto, e ficou um espaço entre a imagem e a sombra, então para resolver isso foi usado uma hackzinho de aplicar _vertical-align: top_ para a imagem, e ficou pronto.
