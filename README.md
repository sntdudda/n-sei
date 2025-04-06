Jogo da Memória (Genius Game)

Um jogo simples de memória estilo "Genius" desenvolvido com React Native, onde o jogador deve repetir uma sequência de luzes coloridas.

Como o Jogo Funciona

Conceito Básico

O jogo consiste em uma grade 3x3 de quadrados coloridos que piscam em uma sequência aleatória. O jogador deve memorizar e repetir essa sequência na ordem correta.

Níveis de Dificuldade

O jogo possui três níveis de dificuldade:

Fácil: Começa com 2 passos na sequência e velocidade mais lenta
Médio: Começa com 3 passos na sequência e velocidade média
Difícil: Começa com 4 passos na sequência e velocidade mais rápida
Como Jogar

Selecione um nível de dificuldade na tela inicial
Observe atentamente a sequência de quadrados que piscam
Quando a mensagem "Repita a sequência!" aparecer, toque nos quadrados na mesma ordem que eles piscaram
Se você acertar a sequência completa, um novo quadrado será adicionado à sequência
Se você errar, receberá uma mensagem de erro e o nível será reiniciado
Sua pontuação aumenta cada vez que você completa uma sequência corretamente
Implementação

Este jogo foi implementado usando:

React Native para a interface do usuário
Hooks do React (useState, useEffect) para gerenciamento de estado
Componentes TouchableOpacity para os quadrados interativos
Estilização simples com StyleSheet
Como Executar o Jogo

Certifique-se de ter o ambiente React Native configurado
Clone este repositório
Instale as dependências:
