Arquitetura 

Na inicialização do tabuleiro

Definido que o gerenciamento das casas ficarão no módulo **jogovelha.py**.

As strings; "." para casa vazia, "X" para casa ocupada pelo primeiro jogador e "O" para casa ocupada pelo 2o jogador.

A função inicializar() retornará uma lista 3x3, onde cada posição conterá uma string para indicar o estado de uma casa 
do jogo e retornará todas as casas inicialmente vazias. 

A função jogar(jogador, linha, coluna) irá posicionar o jogador ('X' ou 'O') na posição definida por linha e coluna.
