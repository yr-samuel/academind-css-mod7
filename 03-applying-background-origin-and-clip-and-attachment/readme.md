## Trabalhando com background-position

- A propriedade *background-position* aceita alguns tipos de valores, como __px__, __%__ e alguns outros valores predefinidos, como: __center__, __top__, __left__, __bottom__ e __right__.
- Pode também aceitar 1 ou mais valores, depedendo do tipo de valor que for tem algumas regrinhas diferentes.
- Vale ressaltar que essa propriedade tem comportamento diferente dependendo do tipo de valor passado.

---

- Quando usamos valores com __px__, podemos passar até dois valores, que serão relativos ao *eixo-x* e em seguida o *eixo-y*, e com esses valores definidos a imagem se distanciará da borda do elemento.
  - Quando passamos só um valor, como: *background-position: 10px*, o segundo valor por padrão ficará como __center__, então teremos a imagem 10px distante da borda esquerda do elemento (eixo-x) e na vertical a imagem estará centralizada.
  - Quando passamos dois valores como *background-position: 10px 10px*, a imagem de background se distanciará da borda esquerda e da borda de cima nesses valores.
  - __Um grande adendo é que, usando valores em *px* a imagem pode acabar ficando cortada, devido ao distanciamento das bordas, então ficando cropadas nas outra extremidades do eixo__

---

- Quando usamos valores com __%__, podemos passar até dois valores, como no caso dos __px__, se passarmos apenas um valor, o segundo será definido como *center*.
  - Então, temos o seguinte caso, *background-position: 10%*, onde o ponto 10% da imagem vai se encontrar com o ponto 10% do container, nesse caso na horizontal, e na vertical é *center*, mas podemos passar porcentagem para o eixo-y e terá o mesmo conceito.
  - Por isso, se colocarmos *background-position: 100%*, a imagem colará no final do container, pois o ponto 100% da imagem se encontra com o ponto 100% do container, no __eixo-x__, e a mesma coisa também acontecerá no __eixo-y__ se passado o valor.
  - Caso a imagem já esteja preenchendo 100% do container, seja no eixo-x ou no eixo-y, usar porcentagem não terá efeito, pois basicamente todos os pontos da imagem já estão alinhados com o do container.
  - __Com *ponto* eu quero dizer, posição x ou y no plano cartesiano da imagem ou do container__.

---

- Por fim, e não menos importante, temos alguns valores predefinidos, que são: *center*, *top*, *bottom*, *left*, *right*.
  - Os valores __top__ e __bottom__ são relacionados ao *eixo-y*. Esses valores seriam a mesma coisa que passar 0% ou 100% no eixo-y.
  - Os valores __right__ e __left__ são relacionados ao *eixo-x*. Esses valores seriam a mesma coisa que passar 0% ou 100% no eixo-x.
  - O valor __center__ é equivalente à usar 50%, seja no eixo-x ou eixo-y.
  - Uma curiosidade é que, até então sempre vimos que o eixo-x vinha primeiro na ordem dos valores, e em seguida o eixo-y, porém ao passarmos esses valores predefinidos, podemos passar na ordem que quisermos, que será interpretado da forma correta, só não podemos passar dois valores repetidos, como: *background-position: top top*.