# 💖 Quiz do Casal: O Quão Bem Você Me Conhece?

Um web game interativo e romântico do tipo "Quiz" desenvolvido especialmente para casais. Este projeto foi criado como um presente criativo para celebrar o aniversário de namoro, testando os conhecimentos do parceiro(a) sobre momentos marcantes, gostos pessoais e piadas internas do relacionamento.

## 🎮 Sobre o Jogo

O jogo apresenta uma série de perguntas personalizadas com alternativas de múltipla escolha. A cada resposta, o jogador recebe um feedback visual imediato (verde para acertos, vermelho com animação de erro para erros). Ao final, uma tela de resultados exibe a pontuação total com uma mensagem carinhosa baseada no desempenho, coroada com uma explosão de confetes virtuais!

## ✨ Funcionalidades

*   **Embaralhamento Automático:** As alternativas de cada pergunta mudam de posição a cada nova jogada, garantindo que o jogo não fique repetitivo.
*   **Design Moderno (Glassmorphism):** Interface construída com um elegante efeito de "vidro fosco" sobre um fundo gradiente animado.
*   **Feedback Visual e Animações:** Efeitos de *shake* ao errar, *pulse* ao acertar, e transições suaves entre as telas.
*   **Barra de Progresso:** Acompanhamento visual de quantas perguntas faltam para terminar o quiz.
*   **Sistema de Pontuação Dinâmico:** Mensagens finais que variam de acordo com a porcentagem de acertos (Gabarito, Quase perfeito, Mediano ou Ruim).
*   **Confetes 🎉:** Integração com a biblioteca `canvas-confetti` para celebrar as vitórias.

## 🛠️ Tecnologias Utilizadas

Este projeto foi construído apenas com tecnologias Front-end nativas, sem necessidade de build ou frameworks complexos:

*   **HTML5** (Semântica e estruturação)
*   **CSS3 & Tailwind CSS** (Estilização via CDN para um desenvolvimento rápido e responsivo)
*   **JavaScript (Vanilla)** (Lógica do jogo, manipulação do DOM e embaralhamento)
*   **Canvas Confetti** (Biblioteca externa para os efeitos de confete)
*   **Google Fonts** (Tipografia Poppins)

## 🚀 Como Executar e Personalizar

Como é um site estático (apenas um arquivo `.html`), você não precisa instalar nada no seu computador para rodar.

1. Faça o clone deste repositório ou baixe o arquivo `quiz_do_casal.html` (ou `index.html`).
2. Abra o arquivo diretamente em qualquer navegador de sua preferência (Chrome, Edge, Firefox, Safari).

### Para fazer o seu próprio Quiz:
Se você quiser usar este código para fazer um presente para a sua pessoa amada, basta editar o código-fonte:
1. Abra o arquivo `.html` em um editor de texto ou código (como VS Code ou Bloco de Notas).
2. Desça até a tag `<script>` e procure a variável `const questions = [...]`.
3. Substitua as perguntas, a resposta correta (`answer`) e a lista de opções (`options`) pelas suas próprias memórias e histórias!

## 🌐 Publicação (Deploy)

Este projeto está pronto para ser hospedado gratuitamente no **GitHub Pages**. Basta colocar o arquivo principal como `index.html` na raiz do seu repositório e ativar o GitHub Pages nas configurações (Settings > Pages).

---
*Feito com muito amor (e código) ❤️*