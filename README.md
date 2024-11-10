# Jogo da Velha

Este é um jogo simples de **Jogo da Velha** desenvolvido em Flutter, onde dois jogadores podem jogar entre si ou enfrentar a **CPU**. O jogo fornece uma interface amigável e fácil de usar, com indicação clara de vitória ou empate.

[//]: # (## Imagens)

[//]: # ()
[//]: # (<div style="display: flex; flex-wrap:wrap; gap: 10px; justify-content: center">)

[//]: # (  <img src="./img/home.png" alt="home_jogo_da_velha">)

[//]: # (  <img src="./img/result.png" alt="result_jogo_da_velha">)

[//]: # (</div>)

## Funcionalidades

- Jogo para 2 jogadores ou contra a **CPU**.
- Exibição do estado do tabuleiro após cada jogada.
- Indicação de vitória, empate e quem é o próximo jogador.
- Interface amigável com efeitos visuais de fácil compreensão.

## Tecnologias Utilizadas

<div style="display: flex; justify-content: center ; width: 100%">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/dart/dart-original.svg" alt="dart" height="30" width="40"> 
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/flutter/flutter-original.svg" alt="flutter" height="30" width="40"> 
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original.svg" alt="postgresql" height="30" width="40"> 
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg" alt="docker" height="30" width="40"> 
</div>

## Estrutura do Projeto

- `lib/`: Contém o código fonte da aplicação.
    - `main.dart`: Ponto de entrada da aplicação.
    - `game_screen.dart`: A tela onde o jogo é exibido e as jogadas são feitas.
    - `game_controller.dart`: Lógica do jogo, incluindo a verificação de vitórias e alternância de jogadores.
    - `modal.dart`: Exibe um modal com o resultado do jogo.

## Classes de Dados

### `GameLogic`

A classe `GameLogic` é responsável por armazenar e manipular os dados do tabuleiro, verificando as vitórias, alternando os jogadores e determinando o estado do jogo.

#### Principais Métodos:
- `makeMove(int index, bool vsCpu)`: Realiza uma jogada no tabuleiro.
- `resetGame()`: Reinicia o estado do jogo.
- `gameOver`: Verifica se o jogo terminou.

### `ModalGame`

A classe `ModalGame` exibe um modal com o resultado da partida, seja vitória ou empate, e oferece uma opção para reiniciar o jogo.

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests para melhorias e novas funcionalidades.

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

## Contato

Se tiver dúvidas ou sugestões, sinta-se à vontade para entrar em contato através de:

- **Email**: [liedson.b9@gmail.com](mailto:liedson.b9@gmail.com)
- **LinkedIn**: [liedsonlb](https://linkedin.com/in/liedsonlb)
- **Instagram**: [liedson.vue](https://www.instagram.com/liedson.vue)
- **Github**: [LiedsonLB](https://github.com/LiedsonLB)
- **Portfólio**: [Liedson Barros](https://liedsonbarros.vercel.app)

## Releases

- Release v1.0 - [Primeira entrega - Em andamento](Em andamento)