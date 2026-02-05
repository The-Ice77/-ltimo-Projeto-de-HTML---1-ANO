# Último-Projeto-de-HTML---1-ANO
Como Último projeto de html do ano tentaremos aprimorar algo que gostamos, RPG. Esse projeto consiste em uma biblioteca intuitiva que armazena um grande catálogo de rpg

A Biblioteca de livros de RPG – RPGDex
Tema:
Projeto tem como base a opção de encontrar e obter títulos famosos de RPG, com intuito de facilitar os amantes da pratica a descobrirem e aproveitarem os diversos sistemas espalhados pela Web através de uma biblioteca de livros, o site funciona semelhante a um sistema de aluguel como Netflix e semelhantes, porem com conteúdo gratuito aos usuários(sem downloads de verdade).

O sistema conta com catálogos de organização dos conteúdos presentes no site, a area inicial de introdução ao funcionamento padrão, a zona de login para se registrar 

Instruções de execução:
O Projeto RPGDex se encontra no diretório do GitHub a seguir e fica localizado na pasta “Código”.
Link do diretório github: https://github.com/The-Ice77/-ltimo-Projeto-de-HTML---1-ANO

Basta obter o código no diretório e colocá-los em um executor da sua preferência, nesse projeto utilizamos o VSCODE e é mais garantido que ocorram menos erros se alguém executá-lo nele também, já que foi o único local onde os testes de bugs ocorreram.

Breakpoints: 

São responsáveis por criar a chamada responsividade do site entre dispositivos e seus diferentes tamanhos de tela, a seguir haverá a descrição do porque não utilizamos no projeto.

uma parte importante que não foi realmente necessária durante o processo, para os programadores se tornou bem mais intuitivo outros métodos de responsividade ja usadas anteriormente, por esse motivo optamos por não utiliza-los, mas deixando a possibilidade de incrementa-lo em alterações futuras, ja que pelo rumo que estamos seguindo, o RPGDEX pode se tornar algo fora dos arquivos e linhas.

Porem mesmo assim para concluirmos os requisitos do projeto, utilizamos na area catalogo, ja que seria a parte de maior parte de acesso do site, e faria grande sentido que ela tivesse esse foco.

descrevendo o uso, colocamos um tamanho máximo para 900px, mostrado na linha css 221(@media (max-width: 900px) {  .card-livro {
    width: 170px;
    height: 255px;
  })
e na linha 229 onde o máximo se tornou 600px(@media (max-width: 600px) {  .card-livro {
    width: 140px;
    height: 210px;)

Flexbox:
Parte crucial na organização dos elementos, de exemplo temos o alingn-items: center; e o justify-content: space-between; da pagina inicial do site que usamos para organizar os elementos horizontalmente dentro das regiões criadas
que serviram para criar intervalos entre os elementos e centraliza-los nos containers desejados.

de exemplo semelhante temos o catalogo que usou o mesmo sistema de organização do "inicio".

Na pagina "sobre" se identifica o justify-content: start; que foi usado na zona de titulo para mover os elementos em direção ao inicio da pagina.

fixando a importância do display: flex; que utilizamos em outra boa parte do código que é facilmente observada, ela serviu para alterar o eixo de exibição dos elementos e se tornou o pontapé inicial ao usar o FlexBox, ja que a forma 
como esses elementos passam a se comportar devido a indicação flex tornou a manipulação deles possível e mais funcional no processo

Integrantes do projeto:
Davi Gomes Suassuna -- 
João Victor Salles -- 
Jusdfran Medeiros Do Nascimento -- 
Luis Felipe Torres Jossué -- 
Tallys Araujo --
