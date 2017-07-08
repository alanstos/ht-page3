# ht-page3

1 - Qual o valor da medida em?
O tamanho de fonte do elemento no qual for usada.
Para exemplificar:
p {
    font-size: 20px;
    margin: 1em;
}
Ou seja, os parágrafos terão margem de 20 pixels.

2 - Qual o valor da medida rem?
O tamanho de fonte do elemento html ou, se não houver tamanho de fonte definido neste elemento, o tamanho de fonte padrão do navegador

No exemplo abaixo, 1rem vale 25px:

html {
    font-size: 25px;
}

p {
    margin: 1rem;
}


3 - Temos duas medidas que são relativas ao tamanho de fonte: em e rem. Quais as diferenças entre elas e quando usar uma e quando usar outra?
O tamanho rem possui um valor único para a página inteira, já a medida em varia de acordo com o elemento em que é utilizada.
(Nesta alternativa, explica a diferença entre as duas medidas. É interessante usarmos em quando queremos que a mudança de tamanho se propague pela página)

4 - Qual o valor da medida ch?
A largura do caractere "0" (zero).

5- A medida porcentagem é relativa a que outra medida?
Dependendo do contexto, pode ser à largura, à altura ou ao tamanho de fonte do pai do elemento.
