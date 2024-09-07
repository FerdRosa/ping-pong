# Jogo Ping-Pong - README

## Descrição

Este projeto é uma implementação simples de um **jogo de ping-pong** em JavaScript utilizando o elemento `<canvas>`. O jogador controla a raquete da esquerda com o movimento do mouse, enquanto a raquete da direita é controlada pelo computador. O objetivo é marcar pontos evitando que a bola ultrapasse sua raquete.

## Funcionalidades

- Controle da raquete esquerda com o mouse.
- Raquete direita controlada pela IA com aumento de dificuldade progressiva.
- Pontuação automática para o jogador e o computador.
- Velocidade da bola e da raquete direita aumenta a cada ponto marcado.
- Desenho dinâmico do campo de jogo, linha central, raquetes, bola e placar.

## Como Jogar

1. **Movimento**: Use o mouse para mover a raquete esquerda verticalmente.
2. **Objetivo**: Evite que a bola ultrapasse sua raquete e tente fazer com que ela ultrapasse a raquete direita (controlada pelo computador) para marcar pontos.
3. **Pontuação**: O placar será atualizado automaticamente toda vez que a bola ultrapassar uma das raquetes.

## Estrutura de Arquivos

- `index.html`: Contém o código HTML e JavaScript que implementa o jogo. O jogo é desenhado e executado diretamente no canvas do navegador.
  
## Controles

- **Mouse**: Move a raquete esquerda para cima e para baixo.

## Tecnologias Utilizadas

- **HTML5**: Para estruturar o jogo e usar o canvas.
- **CSS3**: Para aplicar estilo básico e remover o overflow.
- **JavaScript**: Para lógica de jogo, renderização dos elementos e interação com o jogador.

## Como Executar Localmente

1. Clone este repositório.
2. Abra o arquivo `index.html` no seu navegador de preferência.
3. Comece a jogar movendo o mouse para controlar a raquete esquerda.

## Melhorias Futuras

- Implementação de níveis de dificuldade.
- Adicionar sons para batidas e pontuações.
- Suporte para dois jogadores (um contra o outro).
- Melhorar a IA da raquete direita.

## Créditos

Este jogo foi desenvolvido como um projeto de prática para explorar as capacidades do **canvas** e melhorar habilidades em JavaScript.
