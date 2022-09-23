### Entendendo sobre background-size

Essa propriedade *background-size* vai dizer o tamanho da imagem que está como background e pode receber vários tipos de valores, como px, %, e até alguns pré-setados como __cover__ e __contain__.

Também é possível passar dois valores pra essa propriedade, o primeiro seria relacionado a width e o segundo ao height da imagem, caso passemos só o primeiro valor, o segundo ficará por padrão como auto.

Quando colocamos 100% para essa propriedade, a imagem preenche todo o background do elemento, e no caso se passarmos somente o primeiro valor, o segundo ficará como *auto*, e para preservar a proporção (aspect-ratio) da imagem caso o elemento tenha um width maior que o height, a imagem de background sofrerá um crop nas extremidades verticais, se o height for maior que o width o crop será nas extremidades horizontais.

Quando colocamos __cover__ pra essa propriedade, é a mesma coisa que se estivessemos colocandom 100% auto.

Ao colocar __contain__, a imagem ficará no tamanho necessário para que todo seu conteúdo fique visível, mas talvez ela acabe não preenchendo todo o elemento. Mesma coisa que *background-size: auto 100%;*



