---

# Xadrez Console - Projeto C# (Curso Nélio Alves)

Este projeto é uma implementação do jogo de xadrez em console utilizando C#. Foi desenvolvido durante o curso de C# do professor **Nélio Alves**. O objetivo deste projeto é entender conceitos de programação orientada a objetos, manipulação de tabuleiro e peças, e a implementação das regras do jogo de xadrez de forma simples e funcional, com uma interface em console.

## Descrição

O projeto simula uma partida de xadrez no formato de um jogo por console. Ele utiliza classes para representar o **tabuleiro**, **pecas** e **partidas de xadrez**. As jogadas são realizadas com base em comandos simples para definir a origem e destino das peças no tabuleiro.

## Funcionalidades

- Implementação das regras básicas do jogo de xadrez (movimentos das peças, capturas, etc.).
- Visualização do tabuleiro no console.
- Validação de jogadas (verificação de movimentos válidos, peças no caminho, etc.).
- Exceções personalizadas para erros durante a execução (por exemplo, se uma jogada for inválida).
- Controle de turno (jogador de cada vez).
  
## Tecnologias Utilizadas

- **C#**
- **.NET (versão específica do projeto)**

## Como Rodar o Projeto

### Pré-requisitos

1. **Instalar o .NET SDK**: O projeto foi desenvolvido utilizando o .NET, então você precisa ter o SDK do .NET instalado. Para instalar o .NET SDK, siga as instruções no [site oficial do .NET](https://dotnet.microsoft.com/download).

2. **Editor de código**: Recomenda-se utilizar o [Visual Studio](https://visualstudio.microsoft.com/) ou [Visual Studio Code](https://code.visualstudio.com/), mas você pode usar qualquer editor de sua preferência.

### Passos

1. **Clone o repositório**

   Clone este repositório para sua máquina local:

   ```bash
   git clone https://github.com/guilherme705218/xadrez-console.git
   ```

2. **Abra o projeto**

   Abra o arquivo `.sln` no Visual Studio ou em outro editor de sua escolha.

3. **Rode o Projeto**

   No terminal, navegue até a pasta do projeto e execute o comando para rodar o projeto:

   ```bash
   dotnet run
   ```

   Se estiver utilizando o Visual Studio, você pode clicar no botão "Start" para executar o projeto.

### Como Jogar

1. Ao rodar o projeto, o tabuleiro de xadrez será exibido no console.
2. O programa solicitará a entrada do jogador para a origem e o destino das peças.
3. O jogo continuará até que um dos jogadores vença, ou o jogo seja encerrado.
4. Durante o jogo, o console mostrará mensagens informando o turno atual, o jogador que está fazendo a jogada e qualquer erro ou situação específica.

### Comandos

- O jogo solicita a posição de origem e destino para a movimentação das peças no formato **a1**, **b2**, etc.
- As jogadas válidas são determinadas de acordo com as regras do xadrez.

## Estrutura do Projeto

O projeto é dividido nas seguintes pastas e arquivos principais:

- **tabuleiro**: Contém as classes relacionadas ao tabuleiro, incluindo `Tabuleiro`, `Posicao`, e `Peca`.
- **xadrez**: Contém as classes relacionadas às peças de xadrez, como `Rei`, `Torre`, `Cavalo`, `Bispo`, `Rainha` e `Peao`.
- **xadrez_console**: Contém a classe `Program`, que é a entrada do jogo, e a classe `Tela` que gerencia a interface com o console.
  
---
