# 🐍 Snake AI - Jogo da Cobrinha com Aprendizado por Reforço

Este é um projeto desenvolvido em **React + Vite**, estilizado com **Tailwind CSS**, que implementa o clássico **jogo da cobrinha**, mas com um diferencial: a cobrinha aprende a jogar sozinha usando **Aprendizado por Reforço (Reinforcement Learning)** com **TensorFlow.js**.

## 🎯 Objetivo do Projeto

Criar uma cobrinha autônoma que aprende a se mover em direção a frutas verdes (benefício) e evitar frutas vermelhas (punição), utilizando um agente de inteligência artificial treinado diretamente no navegador.

---

## 🧠 Inteligência Artificial 

- **Algoritmo**: Deep Q-Learning (DQN) com TensorFlow.js.
- **Entradas (estado)**:
  - Direção atual da cobrinha.
  - Posição relativa das frutas.
  - Obstáculos ao redor (paredes e corpo).
- **Ações possíveis**:
  - Mover-se para cima, baixo, esquerda ou direita.
- **Recompensas**:
  - 🍏 Fruta verde: `+10` pontos e crescimento da cobrinha.
  - 🍎 Fruta vermelha: `-10` pontos e diminuição da cobrinha.
  - ❌ Colidir com a parede ou com o corpo: `-100` e reinício do jogo.
  - ⏩ Movimento neutro: `-0.1` (incentiva decisões rápidas).

---

## 🛠️ Tecnologias Utilizadas

- [React](https://reactjs.org/)
- [Vite](https://vitejs.dev/)
- [Tailwind CSS](https://tailwindcss.com/)
- [TensorFlow.js](https://www.tensorflow.org/js)
