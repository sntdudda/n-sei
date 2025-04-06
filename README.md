
O Jogo "Gênios":
Oque é
O jogo "Gênios"
é um jogo de memória onde o jogador precisa repetir uma sequência de cores que o computador mostra. A sequência fica cada vez mais longa e rápida, desafiando a memória do jogador.

Como o Código Funciona:
1.  Início:
    O jogo começa com uma sequência curta de cores piscando.
    O jogador tenta repetir a sequência clicando nos quadrados coloridos.

2.  Sequência e Dificuldade:
    A cada rodada correta, a sequência aumenta e a velocidade das cores piscando aumenta, tornando o jogo mais difícil.
    A dificuldade (fácil, médio, difícil) muda automaticamente conforme o jogador avança.

3.  **Erros e Recomeço:**
Se o jogador errar a sequência, uma mensagem de "Você errou!" aparece.
 O jogo recomeça do início.

4.  Interface:
    O jogo é uma grade de 3x3 quadrados coloridos.
     Um modal informa quando o jogador erra.
     A dificuldade e o tamanho da sequência são exibidos na tela.

Tecnicamente:

 O código usa "useState" para lembrar a sequência e a entrada do jogador.
 "useEffect" inicia o jogo.
"setTimeout" faz as cores piscarem.
 O estilo do app é feito com "StyleSheet".
