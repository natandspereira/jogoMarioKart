# jogoMarioKart 

## Este é um jogo simples de corrida entre dois personagens, onde cada personagem tem atributos de velocidade, manobrabilidade e poder. Durante a corrida, os jogadores enfrentam diferentes tipos de desafios (reta, curva ou confronto) e utilizam suas habilidades para competir. O objetivo é acumular o maior número de pontos, com base no desempenho nas diferentes rodadas.

## Descrição do Jogo
### O jogo é composto por duas fases principais:

### Corrida: Durante a corrida, os personagens enfrentam uma série de blocos de desafios (RETA, CURVA e CONFRONTO).

* RETA: A habilidade de velocidade de cada personagem é usada para determinar quem é o vencedor.
* CURVA: A habilidade de manobrabilidade de cada personagem é testada.
* CONFRONTO: Um confronto direto onde o poder dos personagens é comparado. O vencedor do confronto faz o adversário perder pontos.
* Declaração de Vencedor: Após cinco rodadas, o personagem com mais pontos é declarado o vencedor da corrida. Caso haja empate, a corrida termina sem um vencedor.

## Atributos dos Personagens
### Cada personagem tem os seguintes atributos:

* NOME: Nome do personagem.
* VELOCIDADE: Determina o quão rápido o personagem é em retas.
* MANOBRABILIDADE: Reflete a habilidade do personagem em curvas.
* PODER: Determina a força do personagem em confrontos.
* PONTOS: O número de pontos que o personagem acumulou ao longo da corrida.

## Como Funciona
* Durante cada rodada, dois jogadores (player1 e player2) rolam dados para determinar o resultado de cada desafio.
* O bloco de cada rodada é escolhido aleatoriamente (RETA, CURVA ou CONFRONTO).
* O personagem com o maior resultado (atributo + dado) ganha a rodada e marca um ponto.
* Se ocorrer um confronto (bloco CONFRONTO), os personagens podem perder pontos dependendo de quem ganhar.

## Regras do Confronto
* Caso um personagem vença o outro em um confronto, o perdedor perde um ponto.
* Se ambos os personagens empatarem no confronto, nenhum ponto é perdido.

## Tecnologias usadas 
* JavaScript
* Node
