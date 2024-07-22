1. Pesquisa e contextualização das seguintes tags:
Header- Representa um grupo de suporte introdutório ou navegacional. Pode conter alguns elementos de cabeçalho mas também outros elementos como um logo, seções de cabeçalho, formulário de pesquisa, e outros.
O elemento <header> não é separador de conteúdo (sectioning content), portanto, não introduz uma nova seção no outline. Então, header agrega no valor semântico.
Exemplo:
<header>
  <h1>Título da Página Principal</h1>
  <img src="mdn-logo-sm.png" alt="MDN logo">
</header> 
Footer- O elemento HTML de Rodapé (<footer>) representa um rodapé para o seu conteúdo de seção. Fica no final da página e apresenta informações sobre o autor e informações osbre o site ou copyright. 
Exemplo:
<footer>
  Algumas informações de copyright ou talvez alguma informação do autor de um <article>?
</footer>
Main- O elemento <main> define o conteúdo principal dentro do <body> em seu documento ou aplicação. Entende-se como conteúdo principal aquele relacionado diretamente com o tópico central da página ou com a funcionalidade central da aplicação. O mesmo deverá ser único na página, ou seja, dentro do elemento <main> não deverão ser incluidas seções da página que sejam comuns a todo o site ou aplicação, tais como mecanismos de navegação, informações de copyright, logotipo e campos de busca (a não ser, é claro, caso a função principal do documento seja fazer algum tipo de busca).
Exemplo
<header></header>
<main>
  <article>
    <header></header>
    <div></div>
    <footer></footer>
  </article>
</main>
<footer></footer>
Section- A tag section é utilizada para marcar as seções de conteúdo de uma página. Com Esse elemento agrupamos de forma lógica nosso conteúdo, separando a informação em áreas diferentes. O principal objetivo é retirar essa responsabilidade das divs. Tendo como principal diferencial a navegação semântica.
Exemplo:
<section id="rock">
  <h2>Rock </h2>
  <!-- vários elementos article podem vir aqui -->
</section>
 
<section id="jazz">
  <h2>Jazz </h2>
  <!-- vários elementos article podem vir aqui -->
</section>
 
<section id="hip-hop">
  <h2>Hip hop </h2>
  <!-- vários elementos article podem vir aqui -->
</section>
Article- O elemento article destina-se a marcar um conteúdo que se constitua em um componente autossuficiente em uma página, aplicação ou site e que possa ser distribuido ou reusado de forma independente (isolada), como por exemplo via sindicalização. Tal conteúdo pode ser um post em um fórum, um artigo de uma revista ou jornal, uma matéria em um blog, um comentário de um usuário, um widget ou gadget interativo ou qualquer outro item independente de conteúdo.
Exemplo 
<article>       
<h1>Apple</h1>       
<p>The apple is the pomaceous fruit of the apple tree...</p>
...
</article>
Aside- O elemento HTML <aside> representa uma seção de uma página que consiste de conteúdo que é tangencialmente relacionado ao conteúdo do seu entorno, que poderia ser considerado separado do conteúdo. Essas seções são, muitas vezes, representadas como barras laterais. Elas muitas vezes contem explicações laterais, como a definição de um glossário; conteúdo vagamente relacionado, como avisos; a biografia do autor; ou, em aplicações web, informações de perfil ou links de blogs relacionados. 
Exemplo
<aside>
  <p>Algum conteudo relacionado a um &lt;article&gt;</p>
</aside>
Essas tags dão valor semântico para nosso código.
2. O elemento HTML <fieldset> é usado para agrupar elementos, assim como labels (<label>), dentro de um formulário web. 
O marcador <FIELDSET></FIELDSET> "Fieldset Element" ou campo definido é utilizado como diz o próprio nome; definir os limites visuais (perímetro) de um formulário.

Pode-se ou não ser usada com a tag <LEGEND></LEGEND> quando então o leitor estará diante de um arquivo de aço cheio de divisórias onde pastas de arquivos estão separadas por cartões duros com uma aba de identificação.
O marcador <FIELDSET></FIELDSET> tem uma serie agradável de modificações que podem ser feitas com CSS.

Se não dimensionada ocupa o tamanho do formulário na qual está contida.
Usa-se CSS para dimensioná-la ou dentro de uma outra tag.

A marcação inicial <FIELDSET>, como a marcação final </FIELDSET> é obrigatória.
1º Exemplo - Somente a definição do campo:

<form>
<fieldset>As tags que pretendo delimitar ficam neste intervalo. Sem limite de tags.</fieldset></form>

2º Exemplo - Definição do campo e inclusão da legenda:

<form>
<fieldset>
<legend>Aqui a legenda</legend>As tags que pretendo delimitar ficam neste intervalo. Sem limite</fieldset></form>
Elas agregam valor semântico.
