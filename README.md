# Jogo da Palavra Secreta

Bem-vindo ao **Jogo da Palavra Secreta**! Este é um jogo simples e divertido onde você deve adivinhar uma palavra secreta com base em dicas fornecidas. Desenvolvido em React, este projeto demonstra o uso de hooks para gerenciar estados e a lógica do jogo.

## Descrição do Projeto

O jogo apresenta as seguintes características:
- O jogador deve adivinhar a palavra secreta com um número limitado de tentativas.
- A cada tentativa, o jogador insere uma letra. Se a letra estiver na palavra, ela é revelada; se não estiver, o número de tentativas diminui.
- O jogo termina quando o jogador adivinha a palavra ou esgota todas as tentativas.
- O jogador pode reiniciar o jogo após o término.

## Tecnologias Utilizadas

- **React**: Para construção da interface do usuário.
- **CSS**: Para estilização do aplicativo.
- **JavaScript**: Para a lógica do jogo.

## Hooks Utilizados

Neste projeto, utilizamos alguns hooks do React para gerenciar estados e controlar a lógica do jogo:

- **`useState`**: Permite adicionar estado aos componentes funcionais. Utilizamos esse hook para gerenciar estados como a palavra escolhida, categoria, letras adivinhadas, tentativas restantes e pontuação.
  
- **`useEffect`**: Usado para executar efeitos colaterais em componentes funcionais. Ele é utilizado para verificar se o jogador venceu ou perdeu, monitorando as mudanças nas letras adivinhadas e no número de tentativas restantes.

- **`useCallback`**: Permite memorizar funções, evitando que elas sejam recriadas em cada renderização. Isso é útil para otimizar o desempenho do jogo, principalmente em funções que lidam com a lógica de escolha da palavra e categoria.

## Como Usar

1. **Clone o Repositório**
   ```bash
   git clone https://github.com/Miltonnn/palavraSecreta_react.git

