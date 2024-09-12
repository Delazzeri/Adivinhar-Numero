Este jogo é uma versão de "adivinhe o número" com um limite de tentativas. Veja como jogar:

- Início do Jogo:

A função init() gera um número aleatório entre 1 e 100 que o jogador precisa adivinhar.
O número gerado é armazenado na variável computerNumber.

- Entrada do Jogador:

O jogador insere um número no campo de entrada (inputBox).
A função compareNumbers() compara o número inserido com o número secreto.

- Feedback:

O jogo dá dicas com base na distância do número inserido em relação ao número secreto:
"Seu número é MUITO alto" ou "Seu número é alto".
"Seu número é MUITO baixo" ou "Seu número é baixo".
Se o número estiver correto, o jogo exibe "Parabéns, este é o número exato!" e desativa o campo de entrada.

- Contagem de Tentativas:

O jogador tem até 10 tentativas (maxguesses).
A cada tentativa, o número é registrado em userNumbers e o número de tentativas é atualizado na interface.

- Fim de Jogo:

Se o jogador não acertar em 10 tentativas, o jogo informa que ele perdeu e revela o número secreto.
O campo de entrada é bloqueado.

- Novo Jogo:

A função newGame() recarrega a página para iniciar uma nova partida.
O jogador deve tentar adivinhar o número correto com o menor número de tentativas possível, utilizando as dicas dadas.
