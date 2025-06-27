# MAPEXERCISE

# Isometric Tilemap Example

Este projeto é um exemplo de tilemap isométrico em C++ usando OpenGL, GLFW, GLAD e GLM. O personagem pode ser movido pelo mapa definido por arquivo, e há suporte para tiles não caminháveis igualmente definidos por arquivo externo.

## Funcionalidades

- Carrega mapa e tileset a partir de arquivos de texto (`map.txt` e `tiles_bloqueados.txt`)
- Renderização de mapa isométrico
- Personagem animado com movimentação por teclado
- Tiles não caminháveis (obstáculos)

## Controles

- **W/A/S/D, Q/E/Z/X**: Movimentação do personagem (8 direções)
- **ESC**: Sair do jogo

## Estrutura dos Arquivos

- **map.cpp**: Código-fonte principal
- **map.txt**: Configuração do mapa e tileset  
- **tilesetIso.png**: Imagem do tileset
- **personagem_spritesheet.png**: Sprite sheet do personagem

## Como Compilar

Certifique-se de ter as bibliotecas **GLFW**, **GLAD**, **GLM** e **stb_image** disponíveis.

Exemplo de compilação (ajuste conforme seu sistema):

```sh
g++ [map.cpp](http://_vscodecontentref_/1) -o jogo -lglfw -lGL -ldl -lX11 -lpthread
