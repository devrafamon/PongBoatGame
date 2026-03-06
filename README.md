# 🏓 Boat Pong — Unity / C#

![Unity](https://img.shields.io/badge/Engine-Unity-black?logo=unity)
![C#](https://img.shields.io/badge/Language-C%23-purple?logo=csharp)
![Platform](https://img.shields.io/badge/Platform-PC-blue)
![Status](https://img.shields.io/badge/Status-Not%20Maintained-lightgrey)

Um jogo **Pong 2D desenvolvido em C# utilizando Unity**, com temática náutica.

Este projeto representa **meu primeiro contato com a linguagem C#** e com o desenvolvimento de jogos utilizando a **Unity Engine**.

O objetivo do projeto foi aprender os fundamentos de programação aplicados ao desenvolvimento de jogos, implementando uma variação do clássico **Pong**, porém com mecânicas adicionais que modificam a dinâmica tradicional da partida.

⚠️ **Status do Projeto:** Descontinuado  
  
As mecânicas principais do jogo foram implementadas, porém ainda existem melhorias e bugs a serem tratados.  
No momento, não há previsão de continuidade ou manutenção deste projeto.
---

# 🎮 Sobre o Jogo

Inspirado no clássico Pong, o jogo coloca dois jogadores controlando embarcações que devem rebater uma boia de um lado para o outro da tela.

Cada jogador deve impedir que a boia ultrapasse seu lado enquanto tenta fazer com que ela passe pela defesa do adversário para marcar pontos.

Diferente do Pong tradicional, este jogo inclui **mecânicas adicionais e power-ups**, que tornam as partidas mais imprevisíveis.

---

# 📸 Gameplay Preview

## 🎥 Gameplay

![Gameplay](https://drive.google.com/file/d/12pB-e9RMR6x4u2uz1hQquJzbFH1311l4/view?usp=sharing)

## 📷 Screenshots

| Gameplay | Gameplay |
|--------|--------|
| ![](https://drive.google.com/file/d/12t43Xm9hS2YdmK7hemg5uPSsKP9pzofo/view?usp=sharing)| ![](https://drive.google.com/file/d/1pFylJAT12SCiG98hdFkSAQBxSQ-1UmPc/view?usp=sharing) |

---

# 🎮 Controles

| Jogador | Controles |
|-------|-------|
| Jogador 1 | `W` / `S` |
| Jogador 2 | `↑` / `↓` |

---

# ⚙️ Mecânicas do Jogo

Além da mecânica clássica do Pong, o jogo possui elementos adicionais que alteram a dinâmica da partida.

## ⚡ Power-ups

Durante a partida, podem ocorrer efeitos especiais.

### 🚀 Acelerar Barco

Ao acertar o power-up com a boia, o ultimo barco que tocou a boia recebe um aumento de velocidade, tornando um jogador mais ágil.

### ➕ +2 Pontos

Um power-up que concede **2 pontos** ao jogador que o ativa se for o próximo a marcar ponto.

Esses elementos introduzem **variação estratégica e imprevisibilidade** nas partidas.

---

## 🪝 Mecânica de "Furar a Bola"

As embarcações possuem **pontas afiadas**.

Se uma dessas pontas atingir diretamente a boia:

- A boia **"fura"**
- Ela perde seu comportamento físico normal
- Escapa pelos limites da tela

Quando isso ocorre, existe uma penalidade:

❗ **Ambos os jogadores perdem 1 ponto**

Essa mecânica adiciona um elemento de risco e estratégia à partida.
Isso incentiva quem tá liderando à tomar cuidado com a posição do barco e dá mais margem para o que está atrás virar o jogo.

---

# 🧠 Lógica do Jogo

O jogo foi implementado utilizando scripts em **C# dentro da Unity**, explorando conceitos fundamentais de desenvolvimento de jogos.

Alguns dos principais componentes da lógica incluem:

### 🎯 Controle da Bola

Responsável por:

- movimentação da bola
- aplicação de velocidade
- resposta a colisões
- reinício após pontuação

### 🛥️ Controle dos Jogadores

Scripts responsáveis por:

- leitura de input do teclado
- movimentação vertical das embarcações
- controle de limites da tela

### 💥 Sistema de Colisão

Utiliza o sistema de física 2D da Unity para detectar:

- colisões com as embarcações
- colisões com paredes
- eventos especiais como contato com power-ups

### 🧮 Sistema de Pontuação

Controla:

- pontuação dos jogadores
- penalidades
- power-ups que alteram o placar

### ⚡ Sistema de Power-ups

Permite modificar o comportamento do jogo dinamicamente:

- aumento de velocidade do barco
- alteração da pontuação

---

# 🛠️ Tecnologias Utilizadas

Este projeto foi desenvolvido utilizando:

- **C#**
- **Unity Engine**
- **Unity 2D Physics**
- **Visual Studio / VSCode**
- **Git**
- **GitHub**

---
