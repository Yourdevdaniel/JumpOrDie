# 🎮 Jump or Die

> Jogo produzido durante atividade avaliativa em aula.

---

## 📋 Resumo do Projeto

**Jump or Die** é um endless runner 2D em pixel art onde o mapa avança sozinho, da direita para a esquerda, de forma contínua e infinita. O jogador controla um personagem em posição fixa no eixo X e precisa pular — ou dar duplo pulo — para desviar de obstáculos que surgem no caminho. A velocidade do cenário aumenta progressivamente, tornando o jogo cada vez mais difícil. O objetivo é sobreviver o maior tempo possível e superar o próprio recorde de pontuação.

---

## 🕹️ Mecânicas Implementadas

Todas as mecânicas descritas no GDD foram implementadas:

- **Scroll infinito do mapa** — fundo e chão em loop contínuo com efeito parallax
- **Pulo e duplo pulo** — detecção de chão via `OverlapCircle`, duplo pulo com reset ao aterrissar
- **Spawn aleatório de obstáculos** — cacto, pedra e pássaro com intervalo e posição variáveis
- **Progressão de dificuldade** — velocidade inicial de 5 u/s, aumentando 0,1 por segundo até o máximo de 18 u/s
- **Sistema de pontuação** — pontuação em tempo real proporcional à velocidade
- **Recorde persistente** — salvo entre sessões via `PlayerPrefs`
- **Tela de Game Over** — exibe score da rodada e recorde histórico com botão de reinício

---

## 👥 Integrantes

| Nome |
|---|
| Daniel Bernardes |

---

## 🎨 Direitos Autorais — Assets

| Asset | Tipo | Origem |
|---|---|---|
| `player_idle.png` | Sprite | Gerado por IA (Claude — Anthropic) |
| `player_jump.png` | Sprite | Gerado por IA (Claude — Anthropic) |
| `player_dead.png` | Sprite | Gerado por IA (Claude — Anthropic) |
| `obstacle_cactus.png` | Sprite | Gerado por IA (Claude — Anthropic) |
| `obstacle_rock.png` | Sprite | Gerado por IA (Claude — Anthropic) |
| `obstacle_bird.png` | Sprite | Gerado por IA (Claude — Anthropic) |
| `ground.png` | Sprite | Gerado por IA (Claude — Anthropic) |
| `background_sky.png` | Sprite | Gerado por IA (Claude — Anthropic) |

> Nenhum áudio de terceiros foi utilizado neste projeto.

---

## 🛠️ Tecnologias

- **Engine:** Unity 2D
- **Linguagem:** C#
- **Sprites:** SVG gerados via script Python com exportação para PNG

---

*Jump or Die — v1.0*
# JumpOrDie
