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
  <img src="https://res.cloudinary.com/practicaldev/image/fetch/s--zzjhiEgj--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_800/https://dev-to-uploads.s3.amazonaws.com/uploads/articles/o6kefkya5x9wfz94hmku.png" alt="Imagem">

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
