# Chess System

>## Sobre o projeto
A aplicação consiste em um sistema de jogo de xadrez na linguagem Java, podendo ser executado através do terminal.
O objetivo do projeto foi para se aprofundar em POO, aplicando boas práticas.

>## Como jogar

 Cada peça é representada por uma letra, correspondendo a inicial do nome da peça (em inglês). Abaixo do tabuleiro, temos as peças capturadas de cada jogador, o turno em que jogo está e qual o jogador que deve jogar a próxima peça.

 - Peças: `Pawn (P), Rook (R), Knight (N), Bishop (B), Queen (Q) e King (K)`

***O jogador informa a posição de origem, passando primeiramente a coluna e em seguida a linha***

![source](https://github.com/ti-willi/assets/blob/main/chess-system/source.png) 

***Em seguida é exibido os possíveis movimentos da peça e o jogador informa a posição de destino, passando para o próximo turno***

![target](https://github.com/ti-willi/assets/blob/main/chess-system/target.png)

***Se o jogador informar uma posição que não é válida, será exibido uma mensagem de erro customizada***

![exception](https://github.com/ti-willi/assets/blob/main/chess-system/exception.png)

***Quando o jogador tiver em Check ou CheckMate, será exibido a mensagem na tela***

![check](https://github.com/ti-willi/assets/blob/main/chess-system/check.png)
