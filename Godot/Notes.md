Criar pasta "addons" na raiz do projeto pra adicionar plugins e extensões.

Criar "Sprite2D" e colocar o tileset do personagem, configurar em "animation" os frames e criar a animação.

Criar um "CharacterBody2D" e adicionar um "CollisionShape2D" e jogar o sprite dentro.

Em caso de jogo com camera "top-down" mover o pé do personagem para o X0,Y0.

se for usar Pixel Art, mudar nas configuraçoes do projeto ou do Sprite o filtro de textura para "Nearest".
Project Settings -> General -> Texture -> "Default Texture Filter" = "Nearest" ou Sprite2D -> "CanvasItem" -> "Texture" -> "Filter" = "Nearest"

*Animação*: Criar "AnimationPlayer" dentro do "CharacterBody2D" e adicionar a animação usando o painel inferior. clicar no "Animation" e adicionar a animação.
Usando "Frame" e clicando na "Key" para adicionar a posição do personagem.

*Criar comandos*: project settings -> Input Map -> adicionar os comandos. digita o nome da ação e enter. depois clica no "+" e escolhe a tecla.

*process(delta)*: função que é chamada a cada frame(variavel de acordo com o fps do usuario). delta é o tempo entre um frame e outro.
*physics_process(delta)*: função que é chamada a cada frame(fps fixo), mas é chamada antes do process. é usado para movimentação de personagens.

*lerp*: função que faz a interpolação linear entre dois pontos. uma especie de movimento suave entre dois pontos.