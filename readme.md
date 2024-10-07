# Yu-Gi-Oh Jo-Ken-Po Edition

Bem-vindo ao **Yu-Gi-Oh Jo-Ken-Po Edition**, um jogo de pedra, papel e tesoura inspirado no universo de Yu-Gi-Oh. Aqui você pode testar suas habilidades em duelos rápidos e emocionantes!

## Índice
- [Yu-Gi-Oh Jo-Ken-Po Edition](#yu-gi-oh-jo-ken-po-edition)
  - [Índice](#índice)
  - [Introdução](#introdução)
  - [Requisitos](#requisitos)
  - [Instalação](#instalação)
  - [Como Jogar](#como-jogar)

## Introdução

Este projeto é um jogo de pedra, papel e tesoura com cartas inspiradas em Yu-Gi-Oh, onde os jogadores competem contra o computador. Cada carta possui atributos que determinam qual carta vence, empata ou perde com outra.

O jogo é construído com **HTML**, **CSS** e **JavaScript**, utilizando vídeos, sons e sprites para criar uma atmosfera imersiva no estilo Yu-Gi-Oh.

## Requisitos

Antes de executar o projeto, certifique-se de que você tenha instalado:

- [Node.js](https://nodejs.org/) (Opcional, se desejar rodar em ambiente de desenvolvimento com servidor local)
- Um navegador compatível com HTML5 (recomendado: Google Chrome, Firefox)

## Instalação

1. Clone este repositório na sua máquina local:

   ```bash
   git clone https://github.com/SeuUsuario/Yu-Gi-Oh-Jo-Ken-Po-Edition.git
   ```
2. Navegue até o diretório do projeto:

```bash
cd Yu-Gi-Oh-Jo-Ken-Po-Edition
```
3. Se desejar rodar com um servidor local, você pode utilizar a extensão Live Server do VSCode ou instalar uma ferramenta de servidor local como http-server:

```bash
npm install -g http-server
http-server .
```
4. Caso contrário, você pode abrir diretamente o arquivo index.html em seu navegador.

## Como Jogar
1. Ao abrir o jogo, você verá uma tela com duas áreas de cartas (uma para o jogador e outra para o computador).
2. Escolha uma carta da sua área passando o mouse sobre ela. As informações da carta aparecerão no painel à esquerda.
3. Clique na carta desejada para iniciar o duelo.
4. O computador selecionará uma carta aleatória e o duelo começará.
5. O jogo seguirá as regras do clássico pedra, papel e tesoura:
- Dragão Branco de Olhos Azuis (Papel) vence Mago Negro (Pedra) e perde para Exodia (Tesoura).
- Mago Negro (Pedra) vence Exodia (Tesoura) e perde para Dragão Branco de Olhos Azuis (Papel).
- Exodia (Tesoura) vence Dragão Branco de Olhos Azuis (Papel) e perde para Mago Negro (Pedra).
6. O placar será atualizado após cada duelo, mostrando suas vitórias e derrotas.


Estrutura do Projeto
O projeto está organizado da seguinte maneira:

```graphql
.
├── index.html                  # Página principal do jogo
├── src/
│   ├── assets/
│   │   ├── audios/             # Áudios de fundo e efeitos sonoros
│   │   ├── cursor/             # Sprites personalizados de cursor
│   │   ├── favicon/            # Ícones de favicon
│   │   ├── icons/              # Ícones e imagens das cartas
│   │   └── video/              # Vídeos de fundo
│   ├── scripts/
│   │   └── engine.js           # Lógica do jogo
│   └── styles/
│       ├── buttons.css         # Estilos dos botões do jogo
│       ├── containers_and_frames.css  # Estilos dos contêineres e molduras
│       ├── main.css            # Estilos principais e layout
│       └── reset.css           # Reset CSS para normalizar os estilos
└── README.md # Documentação do projeto
```

- `index.html`: Estrutura principal da página, onde todo o jogo é carregado.
- `src/assets/`: Contém todos os recursos multimídia, incluindo áudio, vídeos e imagens.
- `src/scripts/engine.js`: Arquivo JavaScript responsável pela lógica do jogo, como manipulação de cartas, atualização de placar e controle das rodadas.
- `src/styles/`: Contém os arquivos CSS que estilizam a página e seus elementos.