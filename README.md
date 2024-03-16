<h1 align="center" font-size="200em"><b>Jogo da Vida e Manipulação de Matriz</b></h1>

## Introdução
<p align="justify">
Este é um programa desenvolvido em C++ para a disciplina de Algoritmos e Estruturas de Dados I. O mesmo tem por objetivo simular o famoso "Jogo da Vida" idealizado por John Conway em 1970. O jogo da vida consiste em uma matriz de células, cada uma podendo estar em um de dois estados: vivo ou morto. A evolução das células segue regras simples, baseadas no número de células vizinhas vivas de cada célula. Essas regras determinam se uma célula continua viva, morre ou se uma célula morta se torna viva.

</p>

## Objetivos
<p align="justify">
Neste trabalho, o objetivo é criar um sistema que implementa uma simulação do "Jogo da Vida" em uma matriz bidimensional, permitindo a visualização da evolução das células ao longo do tempo através de um arquivo de texto. Além da opção de escolha do usuário da inserção do tamanho quadrático da matriz junto aos seus elementos e da quantidade de gerações desejadas. Sendo "1" para as células vivas e "0" para células mortas (sempre tentando manter uma fração de 2 para 1).

Quantos as regras envolvendo o "Jogo da Vida" tem-se:
Toda célula morta com exatamente três vizinhos vivos torna-se viva (nascimento).
Toda célula viva com menos de dois vizinhos vivos morre por isolamento.
Toda célula viva com mais de três vizinhos vivos morre por superpopulação.
Toda célula viva com dois ou três vizinhos vivos permanece viva.

<p align="center">
  <img src="(https://www.google.com/url?sa=i&url=https%3A%2F%2Fdev.to%2Fakadot_%2Fpraticando-html-css-e-javascript-vanilla-reproduzindo-o-jogo-da-vida-de-john-conway-2iog&psig=AOvVaw3UFvqKBb-6QhU4eQSCoceZ&ust=1710677604380000&source=images&cd=vfe&opi=89978449&ved=0CBMQjRxqFwoTCNDY1Org-IQDFQAAAAAdAAAAABAE)" alt="Visualização das Regras">
</p>


</p>

## Arquivos
### dataset
- ```input.mps.txt```: arquivo que contém a matriz inicial junto ao seu tamanho;
- ```geracoes.mps.txt```: arquivo que contém as gerações geradas (incluindo a inicial);
## src
- ```matriz.hpp```: arquivo que contém o cabeçalho das funções da classe Matriz;
- ```matriz.cpp```: arquivo que contém o código de funcionamento das funções da classe Matriz (manipulação);
- ```main.cpp```: arquivo principal.

## Resolução do problema



## Conclusão
<p align="justify">
</p> 

## Referências
<p align="center">
  <a href="https://pt.wikipedia.org/wiki/Jogo_da_vida" target="_blank">Artigo da Wikipedia sobre o Jogo da Vida</a>
</p>


## Compilação e execução
* | Comando                |  Função                                                                                           |                     
  | -----------------------| ------------------------------------------------------------------------------------------------- |
  |  `make clean`          | Apaga a última compilação realizada contida na pasta build                                        |
  |  `make`                | Executa a compilação do programa utilizando o gcc, e o resultado vai para a pasta build           |
  |  `make run`            | Executa o programa da pasta build após a realização da compilação                                 |

## Contato
<div>
<a style="color:black" href="mailto:juliarezende34@gmail.com?subject=[GitHub]%20Source%20Dynamic%20Lists">
✉️ <i>jprs1308@gmail.com</i>
</a>
 <p align="justify"> João Pedro Rodrigues </p>
 <a href="https://twitter.com/dreamhanta">
 <img align="center" src="data:image/png;base64,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"/> 
 </div>
 <br>
