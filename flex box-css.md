# FlexBox
O HTML (Hipertext Markup Language) é uma liguagem de marcação utilizada para criar páginas, que serão exibidas em um navegador. Para viabilizar a navegação entres as paginas são utilziados hipertextos, entretanto, as tags, das quais o html possui, permite exibir o conteúdo e utilizar recursos de hiperlink, imagens, tabelas e vídeos, possui limitações quando se trata de formatação e designes personalizados ou mais elaborados. Para contonar esta limitação, utiliza-se em conjunto com o HTML o CSS (Cascading Style Sheets) que permite fazer alterações mais aprofundadas nos elementos. Desta forma o HTML passa a ser utilizado somente como elemento para estruturar as páginas e o CSS é utilizado na formatação das mesmas. (MILETTO, 2014).  

De acordo Alves (2021) além de fornecer as formatações mais avançadas, o CSS possibilita a reutilização do arquivo css criado em vários outros domuentos HTML. Dessa forma é possível formartar/estilizar vários documentos HTML de forma massiva e padronizada. Outro ponto positivo ao se utilizar arquivos CSS, é na criação de *layouts* mais eficientes, toranando mais dinâmico e flexivel os itens que estão presentes no arquivo HTML. A ferrmanenta *FlexBox (Flexible Box)* por exemplo, foi criada para tornar mais simples e fácil a posição de elementos, este modo fácil de dispor os elementos parte do príncipio de que os filhos de um elemento com *FlexBox*  podem se posicionar em qualquer direção e pode ter dimensões flexíveis para se adaptar. (AMOSEI, 2023).

Como dito anteriormente, o *FlexBox* possibilita maior facilidade me dispor os elementos filho. Basicamente, seus elementos filhos serão dispostos nos eixos principal e transversal do elemento pai. A orientação do eixo principal é definida pela propriedade `flex-direction`. Algumas propriedades são definidas no elemteno pai (*flex container*) como display, flex-direction, flex-wrap, flex-flow, justify-content, align-items, align-content; outras propridades são definidas nos elementos filhos (*flex Item*), como flex-grow, flex-basis, flex-shrink, flex, order e align-self. A seguir uma imagem que ilustra a direção de um flex container e os flex item :  
<img>![](/flex-container-direction.png)</img>  
<p1>fonte:https://codepen.io/team/lincolnloop/post/flexboxfridays</p1>  

Na imagem podemos notar que o flex container é divido pelas linhas *cross axis* e *main axis*, estas linhas possuem setas que indicam a orientação a qual os itens filhos que estão dentro do item pai seguirão, ou seja os itens filhos que estao dentro das caixas azuis com as letras F L E X, seguem esta orientação da esquerda para direia e de cima para baixo. Esta orientação pode ser alterada pelas propriedades `flex-direction: row-reverse`. Esta propriedade altera o sentido das direções que são padrão do flex-box (equerda para direira).  

Algumas propriedades de alinhamento do item pai são o *justify-content*, *align-items*, *align-content*. Basicamente estas propriendades definem a disposição dos *flex-items* em relação ao eixo principal e transversal do flex-container.

Referências Bibliográficas:  
MILETTO, Evandro Manara; DE CASTRO BERTAGNOLLI, Silvia. Desenvolvimento de Software II: Introdução ao Desenvolvimento Web com HTML, CSS, JavaScript e PHP-Eixo: Informação e Comunicação-Série Tekne. Bookman Editora, 2014.

ALVES, William P. HTML & CSS: aprenda como construir páginas web. Disponível em: Minha Biblioteca, Editora Saraiva, 2021.

AMOSEI, Juliana. Flexbox CSS: Guia Completo, Elementos e Exemplos. Alura, 18/09/2023. Disponível em: https://www.alura.com.br/artigos/css-guia-do-flexbox . Acesso em: 18 de Setembro de 2023.  

CODEPEN. Introducing Flexbox Fridays. Codepen, 06/02/2015. Disponível em: https://codepen.io/team/lincolnloop/post/flexboxfridays . Acesso em: 18 de Setembro de 2023.