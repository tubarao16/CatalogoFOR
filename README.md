# CatalogoFOR]
Este código consiste em um formulário HTML que permite aos usuários selecionar múltiplas opções de tipos de música em uma lista suspensa. Abaixo da lista suspensa, há um botão que, quando clicado, exibe um alerta com o total de opções selecionadas.
 
* Formulário HTML: O formulário inclui uma lista suspensa de seleção múltipla com o atributo multiple="multiple", permitindo que o usuário selecione mais de uma opção. Cada opção na lista representa um tipo de música, como R&B, Jazz, Blues, etc.
 
* Botão de Contagem: O botão "Quantos foram selecionados?" é associado a uma função JavaScript que é acionada quando o botão é clicado.
 
* Função JavaScript howMany: Esta função recebe como argumento o objeto de seleção (a lista suspensa de tipos de música) e itera sobre todas as opções dentro dela. Para cada opção, verifica se está selecionada. Se estiver, incrementa um contador. Ao final da iteração, o contador é retornado, representando o número total de opções selecionadas.
 
* Evento de Clique do Botão: Quando o botão é clicado, é acionado um evento que chama a função howMany passando o objeto de seleção (a lista suspensa) como argumento. O valor retornado é então utilizado para exibir um alerta mostrando o total de opções selecionadas.
 
Em resumo, este código permite aos usuários selecionar vários tipos de música em uma lista suspensa e fornece um meio de contar quantas opções foram selecionadas através de um botão de ação. É uma abordagem simples e eficaz para permitir a seleção múltipla de itens em um formulário HTML.

# FERRAMENTAS UTILIZADAS: 
    * Live Server
    * HTML5
    * CSS3
    * Visual Studio Code