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

---

## 📁 Estrutura do Projeto

\`\`\`
snake-ai/
├── public/
├── src/
│   ├── components/
│   │   └── SnakeGame.jsx
│   ├── rl/
│   │   └── Agent.js
│   ├── App.jsx
│   └── main.jsx
├── tailwind.config.js
├── index.html
└── package.json
\`\`\`

---

## 🚀 Como Rodar o Projeto

1. **Clone o repositório**:
   \`\`\`bash
   git clone https://github.com/seu-usuario/snake-ai.git
   cd snake-ai
   \`\`\`

2. **Instale as dependências**:
   \`\`\`bash
   npm install
   \`\`\`

3. **Rode o projeto**:
   \`\`\`bash
   npm run dev
   \`\`\`

---

## ✅ Funcionalidades

- [x] Ambiente de jogo com grid dinâmico.
- [x] Geração de frutas aleatórias (verdes e vermelhas).
- [x] Lógica básica da cobrinha (movimento e colisão).
- [x] Implementação inicial do agente com TensorFlow.js.
- [ ] Treinamento com feedback em tempo real.
- [ ] Visualização da evolução do agente.
- [ ] Ajuste fino das recompensas e hiperparâmetros.

---

## 🧪 Testes e Melhoria Contínua

Futuramente, será adicionada uma interface de controle para testar diferentes estratégias de treinamento, visualização dos resultados e ajustes da IA.

---

## 📜 Licença

Este projeto está sob a licença [MIT](LICENSE).

---

## ✨ Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests.

---

## 🙋‍♂️ Autor

Desenvolvido por [Seu Nome] – sinta-se livre para entrar em contato!
