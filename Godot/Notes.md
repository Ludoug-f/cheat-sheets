Criar pasta "addons" na raiz do projeto pra adicionar plugins e extensões.

Criar um "CharacterBody2D" e adiciona um "Sprite2D", colocar o tileset do personagem, configurar em "animation" os frames e criar a animação.

Cria um "CollisionShape2D", em caso de jogo com camera "top-down" mover o pé do personagem para o X0,Y0.

Caso for usar Pixel Art, mudar nas configuraçoes do projeto ou do Sprite o filtro de textura para "Nearest".
Project Settings -> General -> Texture -> "Default Texture Filter" = "Nearest" ou Sprite2D -> "CanvasItem" -> "Texture" -> "Filter" = "Nearest"

*Animação*: Criar "AnimationPlayer" dentro do "CharacterBody2D" e adicionar a animação usando o painel inferior. clicar no "Animation" e adicionar a animação.
Usando "Frame" e clicando na "Key" para adicionar a posição do personagem.

*AnimatedSprite*: é um sprite que tem animações, é mais simples de usar que o AnimationPlayer.

*Criar comandos*: project settings -> Input Map -> adicionar os comandos. digita o nome da ação e enter. depois clica no "+" e escolhe a tecla.

*process(delta)*: função que é chamada a cada frame(variavel de acordo com o fps do usuario). delta é o tempo entre um frame e outro.
*physics_process(delta)*: função que é chamada a cada frame(fps fixo), mas é chamada antes do process. é usado para movimentação de personagens.

*lerp*: função que faz a interpolação linear entre dois pontos. uma especie de movimento suave entre dois pontos.

*Singleton*: é um script que é carregado automaticamente e pode ser acessado por qualquer script. é util para guardar informações que precisam ser acessadas por qualquer script.

*Autoload*: é um script que é carregado automaticamente quando o jogo inicia. é util para guardar informações que precisam ser acessadas por qualquer script. Project Settings -> Autoload -> adicionar o script.

*class_name*: é uma declaração que define o nome da classe do script. é util para criar scripts que podem ser usados em qualquer objeto.

Para usar mais de um script em um node, criar um Node como filho e adicionar os scripts.

Criar um grupo de nodes: selecionar os nodes -> clica com o botão direito -> "Group" -> criar um nome para o grupo.