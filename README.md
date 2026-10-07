# Meu primeiro jogo em Lua

Jogo de sobrevivência contra zumbis em Roblox, com raids em equipe, lobby, armas e progressão.

## Como sincronizar o código com o Studio (Rojo)

Os scripts ficam guardados em `src/`, e o [Rojo](https://rojo.space) sincroniza essa pasta com o Roblox Studio.

1. Instale o Rojo (CLI) e o plugin do Rojo no Studio.
2. Na pasta do projeto, rode `rojo serve`.
3. No Studio, abra o plugin do Rojo e clique em **Connect**.

| Pasta                      | Vai para no Studio                 |
|----------------------------|------------------------------------|
| `src/ServerScriptService`  | ServerScriptService                |
| `src/ReplicatedStorage`    | ReplicatedStorage                  |
| `src/StarterPlayerScripts` | StarterPlayer.StarterPlayerScripts |

Os scripts que já existem no jogo precisam ser copiados uma vez para essas pastas, como arquivos `.server.lua` (servidor), `.client.lua` (cliente) ou `.lua` (ModuleScript). Os modelos 3D, o mapa e a arena continuam no arquivo do Studio, então salve e publique o lugar normalmente.

Veja o que já foi feito e o que falta em [PROGRESSO.md](PROGRESSO.md).
