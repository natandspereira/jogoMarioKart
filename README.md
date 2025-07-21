# 🏁 Jogo Mario Kart - Corrida de Personagens

Este é um jogo de corrida simples entre dois personagens, onde cada um possui atributos distintos de **velocidade**, **manobrabilidade** e **poder**. Durante a corrida, os jogadores enfrentam desafios variados e utilizam suas habilidades para competir. O objetivo é acumular o maior número de pontos ao longo de cinco rodadas.

---

## 🕹️ Descrição do Jogo

O jogo é dividido em duas fases principais:

### 🏎️ Corrida

Durante a corrida, os personagens enfrentam uma sequência de desafios representados por blocos aleatórios:

- **RETA:** Testa a **velocidade** de cada personagem.
- **CURVA:** Avalia a **manobrabilidade**.
- **CONFRONTO:** Coloca os personagens em um embate direto com base no **poder**.

### 🏆 Declaração de Vencedor

Após cinco rodadas:

- O personagem com mais **pontos acumulados** é o vencedor.
- Em caso de **empate**, a corrida termina sem vencedor.

---

## 👤 Atributos dos Personagens

Cada personagem possui os seguintes atributos:

- **NOME:** Identificação do personagem.
- **VELOCIDADE:** Desempenho em blocos do tipo RETA.
- **MANOBRABILIDADE:** Habilidade em curvas.
- **PODER:** Força em confrontos diretos.
- **PONTOS:** Total de pontos acumulados ao longo da corrida.

---

## 🔄 Como Funciona

- Em cada rodada, os jogadores (`player1` e `player2`) **rolam dados**.
- Um **bloco aleatório** é sorteado (RETA, CURVA ou CONFRONTO).
- O resultado do desafio é definido pela **soma do atributo correspondente + valor do dado**.
- O personagem com o maior resultado **vence a rodada** e ganha **1 ponto**.

### ⚔️ Regras do Confronto (Bloco CONFRONTO)

- O vencedor faz o oponente **perder 1 ponto**.
- Em caso de empate, **ninguém perde pontos**.

---

## 💻 Tecnologias Utilizadas

- **JavaScript**
- **Node.js**

---

## ▶️ Como Executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/jogo-mario-kart.git

2. Acesse o diretório e execute o jogo:
cd jogo-mario-kart
node index.js
