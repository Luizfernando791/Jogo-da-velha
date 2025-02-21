<h1>Jogo da Velha em Portugol Studio</h1>

<h2>Introdução:</h2>

<p>Este programa implementa o jogo da velha (tic-tac-toe) utilizando a linguagem Portugol Studio.

O jogo é projetado para dois jogadores que alternam entre os símbolos 'X' e 'O'.

O objetivo é completar uma linha, coluna ou diagonal com o mesmo símbolo antes do oponente. </p>

<h2>Estrutura do Código: </h2>

<h3>--Declaração de Variáveis--</h3>

<p>jogador: controla qual jogador está na vez (1 ou 2).

linha e coluna: armazenam as coordenadas da jogada.

numeroJogadas: conta o número total de jogadas realizadas.

vencedor: armazena o status do jogo (0 = em andamento, 1 = jogador 'X' venceu, 2 = jogador 'O' venceu).

tabuleiro[3][3]: matriz que representa o tabuleiro do jogo. </p>

<h3>--Apresentação Inicial--</h3>

<p>Exibe uma introdução explicando como o jogo funciona.

Mostra a referência das posições do tabuleiro para os jogadores.

Define que o jogador 1 joga com 'X' e o jogador 2 com 'O'. </p>

<h3>--Inicialização do Tabuleiro--</h3>

<p>A matriz tabuleiro é preenchida com espaços vazios (' ') para representar casas livres.

O tabuleiro inicial é exibido na tela. </p>

<h2>Mecânica do Jogo:</h2> 

<h3>--Estrutura de Repetição enquanto--</h3>

O jogo continua enquanto não houver vencedor e o número de jogadas for menor que 9. </p>

<h3>--Turno dos Jogadores--</h3>

<p>Se for a vez do jogador 1, ele insere uma jogada com 'X'.

Se for a vez do jogador 2, ele insere uma jogada com 'O'.

Caso a jogada seja inválida (fora do intervalo ou já ocupada), uma mensagem de erro é exibida e o jogador deve tentar novamente.

Após cada jogada válida, o tabuleiro atualizado é exibido.</p>

<h2>Verificação de Vencedor:</h2>

<h3>--Teste de Linhas--</h3>

<p>Verifica se alguma linha contém três 'X' ou três 'O'.</p>

<h3>--Teste de Colunas--</h3>

<p>Verifica se alguma coluna contém três 'X' ou três 'O'.</p>

<h3>--Teste de Diagonais--</h3>

<p>Verifica se uma das diagonais contém três 'X' ou três 'O'.</p>

<h3>--Atualização do Número de Jogadas--</h3>

<p>O contador numeroJogadas é incrementado após cada turno válido.</p>

<h2>Encerramento do Jogo:</h2>

<h3>--Exibição do Resultado--</h3>

<p>Se vencedor == 1, exibe "A pessoa que escolheu (X) venceu!".

Se vencedor == 2, exibe "A pessoa que escolheu (O) venceu!".

Se numeroJogadas == 9 e nenhum vencedor foi definido, exibe "Deu VELHA! Jogue novamente!".</p>
