# 🚩 Flag Game

Um jogo interativo de perguntas e respostas ("Quiz") onde o objetivo é adivinhar a qual país pertence a bandeira exibida. Este projeto foi desenvolvido utilizando **React** e **Vite**.

## 📋 Sobre o Projeto

O **Flag Game** consome dados de uma API externa para gerar rodadas infinitas de perguntas. Em cada rodada:

1.  Uma bandeira é exibida.
2.  Três opções de países são apresentadas.
3.  O jogador deve clicar na opção correta.
4.  O jogo contabiliza os acertos e erros e fornece feedback visual imediato.

## 🚀 Funcionalidades

  * **Consumo de API:** Obtém os códigos e nomes dos países via `flagcdn.com`.
  * **Lógica de Jogo:** Seleção aleatória de 3 países, onde um é a resposta correta e os outros dois são distratores.
  * **Placar:** Contador de "Acertos" e "Erros" em tempo real.
  * **Feedback Visual:**
      * Botão fica **Verde** se acertar.
      * Botão fica **Vermelho** se errar (e exibe a mensagem correspondente).
  * **Interface:** Tema escuro ("Dark Mode") com detalhes em ciano e layout responsivo.
---

## 📦 Como Ver o Projeto

Acesse https://maryjenzz.github.io/flag-game/
