# TAGS
 A tag label é uma etiqueta para a entrada de dados, para o input>.

# CSS
Qual propriedade devo alterar para que os meus input tenham um espaço entre a borda e o conteúdo?

A propriedade padding serve para alterarmos o espaçamento interno, entre o conteúdo e a borda.

# AULA
A criar um formulário HTML
A tag que o representa é a form
A tag input, para a entrada de dados do usuário
A criar uma etiqueta para o input, com a tag label
A conectar um input com o seu label
Colocamos um id para o input e associamos esse id ao atributo for do label
Alguns tipos de input, como text e submit
Que label possui o display inline e o input possui display inline-block
A estilizar o nosso formulário

# PERGUNTA
Qual a propriedade de um input do tipo radio que preciso criar para que eles façam parte do mesmo grupo?

A propriedade name só pode ser "preenchida" uma única vez, por isso que, quando eu seleciono um dos itens, ele desmarca o outro, mantendo somente um selecionado.

# AULA PARTE 3 HTML E CSS3
O textarea, para entradas de texto de mais de uma linha
O input do tipo radio
Como agrupar vários input do tipo radio, impedindo que mais de um input seja selecionado
O input do tipo checkbox
Que podemos criar um input dentro de um label, assim associando-os
Mais estilizações para a nossa página
Como funciona a hierarquia no CSS
O select, que é seletor, um campo de seleção de um item, e o option, que representa cada opção do seletor

# Qual tag usamos para marcar um título de um grupo de campos do formulário?
A tag legend que usamos para um título de um grupo de campos em qualquer formulário.

Alguns tipos de inputs para celular: email, tel, number, password, date, datetime, month e search
Como não permitir que um campo não seja preenchido, através do atributo required
Como exibir uma sugestão de preenchimento para os campos, através do atributo placeholder
Como deixar uma opção marcada por padrão nos nossos input radio e checkbox, através do atributo checked
Como estruturar melhor o nosso código com fieldset e legend
Como adicionar uma alternativa à imagem, descrevendo-a, com o atributo alt.

# Qual propriedade do CSS usamos para aumentar um elemento proporcionalmente?
Utilizamos a propriedade ( transform: scale() )para aumentar um elemento proporcionalmente.

Como estilizar o botão de envio de formulário
A realizar transições nos nossos elementos, com a propriedade CSS transition
A modificar o estilo do ponteiro do mouse, quando passar por cima de determinado elemento, através da propriedade CSS cursor
A realizar transformações nos nossos elementos, como aumentar proporcionalmente a escala de determinado elemento ou rotacioná-lo, através da propriedade CSS transform.

# Qual tag uso para criar linhas em uma tabela?
Utilizamos a tag tr para marcar uma linha de uma tabela.

# Como dividir uma tabela de forma mais semântica?
As tags thead, tbody e tfoot ajudam a deixar o conteúdo da tabela mais bem dividido e mais semântico.

As tabelas também nos oferecem a possibilidade de juntar células e montar um visual diferente. Por exemplo, quando uma linha, que deveria ter 5 células, passa a mostrar só "uma célula".

Esse efeito é conseguido através da propriedade colspan=X, onde X é o número de células que você quer agrupar.

Portanto, em uma tabela de 5 colunas, para ter uma célula única na linha, usamos um código assim:

tr
    td colspan="5">Rio de Janeiro td 
tr

# Nesta aula, aprendemos:
A criar uma tabela HTML
A tag table, que representa a tabela
A tag tr, que representa a linha da tabela
A tag td, que representa a célula da tabela
A tag thead, que representa o cabeçalho da tabela
A tag tbody, que representa o corpo da tabela
A tag th, que representa a célula do cabeçalho da tabela
A tag tfoot, que representa o rodapé da tabela
A estilizar a tabela

# HTML5 e CSS3 parte 4: avançando no CSS.

Para um bloco onde o conteúdo tenha o mesmo significado, o mesmo sentido, usamos uma <section></section>

# Para que serve a propriedade float?

Tanto o float:left quanto o float: right servem para que o elemento se destaque na tela, deixe de ocupar o espaço em que estava, para que os outros elementos possam se posicionar ao redor dele.

# Nesta aula, aprendemos:

A ajustar a página principal para utilizar os mesmos padrões da página de produtos
Medidas proporcionais com CSS
Como funciona a flutuação dos elementos e como modificá-la, com a propriedade float do CSS
Como limpar o float, com a propriedade clear do CSS.

#  PSEUDO-CLASSES

# Para seleção de elementos específicos temos três opções: a primeira delas é utilizar uma classe pseudo-elemento first-child. Temos seis itens que são irmãos nos itens da lista, e as alteração serão feitas no primeiro item. Escreveremos que o peso da fonte será em negrito.

.itens: first-child {
    font-weight: bold;
     Que marcará o primeiro item da lista.
}
.itens:last-child {
    Que marcará o último item da lista.
}
.itens:nth-child {
     Que receberá o número que quisermos, como por exemplo 4, que se refere ao quarto elemento da lista. Podemos ainda utilizar valores como 2n com o nth-child(), o que quer dizer marcamos todos os elementos pares da lista, isto é, o segundo, quarto e sexto elemento da lista ficam em negrito.
}
.itens:nth-last-child(2n) {
    font-weight: bold;
    O que quer dizer marcamos todos os elementos ímpares da lista.

}

#  PSEUDO-ELEMENTOS
Itens não são selecionavies na página.
.titulo-principal:first-letter {
    font-weight: bold;
    Com first-letter, teremos a primeira letra do título "Nosso estabelecimento" em negrito no caso (N)
}

p:first-line {
    font-style: italic;
    Primeira linha de todos os Páragrafos em ítalico
}
.titulo-principal::before{
    Content: "[ "
    Que vem antes
}
.titulo-principal::after {
    Content: "] "
    Que vem depois
}

# Criando um elemento antes de outro, com CSS

Como criar um elemento no HTML antes do meu item, através do CSS?
Com a propriedade :before
Quando queremos criar um elemento na página, via CSS, antes do elemento do HTML, usamos a propriedade :before.
