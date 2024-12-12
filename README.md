## Dropdown Simples
### Descrição

Este projeto cria um menu dropdown simples utilizando HTML e CSS. O menu exibe uma lista de navegação com opções, onde a opção "Linguagens" possui um submenu que se expande quando o usuário passa o mouse sobre ela. O submenu contém links para diversas linguagens de programação.

## Características
Menu Principal com os itens: "Home", "Linguagens", "Mais sobre a Empresa" e "Contato".
Submenu (Dropdown): Aparece ao passar o mouse sobre a opção "Linguagens" e contém links para HTML, CSS, JavaScript, Python e MySQL.
Design simples e intuitivo, ideal para projetos iniciais ou menus simples.
Interatividade com Hover: O submenu é exibido ao passar o mouse sobre a opção "Linguagens".

## Tecnologias Utilizadas
HTML: Estrutura do conteúdo da página.
CSS: Estilização e animação do menu e submenu.

## Estrutura do Código

### HTML
A estrutura do HTML é composta por uma lista não ordenada <ul>, onde os itens <li> representam as diferentes opções de menu. O submenu é colocado dentro de outra lista <ul class="dropdown">, que é revelada quando o usuário passa o mouse sobre o item de menu correspondente.

### CSS
O CSS define a aparência do menu e do submenu. Abaixo estão os pontos principais de estilo:

ul: Remove as marcações padrão de lista e define a cor de fundo do menu.
ul li: Exibe os itens do menu na horizontal (com inline-block).
ul li a: Estiliza os links, incluindo padding, cor e alinhamento.
ul li ul.dropdown: Define a aparência do submenu, que está inicialmente oculto com display: none. Quando o item do menu é "hovered", o submenu se torna visível com a regra display: block.

## Funcionamento
Hover: Quando o usuário passa o mouse sobre a opção "Linguagens", o submenu é exibido.
Estilos dinâmicos: O estilo do item do menu muda quando o usuário passa o mouse sobre ele, proporcionando uma interação visual.
Como Usar
Clone o repositório ou baixe os arquivos HTML e CSS.
Abra o arquivo HTML no seu navegador para ver o menu dropdown em funcionamento.
Personalize o conteúdo e os estilos conforme necessário para se ajustar ao seu projeto.
Personalização
Cores: Você pode alterar as cores de fundo e dos textos no arquivo style.css.
Links: Modifique os links dentro das tags <a> para direcionar para as páginas desejadas.
Layout: Modifique a estrutura do menu ou o estilo do submenu para atender às suas necessidades.
