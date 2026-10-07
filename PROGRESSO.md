# Progresso do jogo

## Pronto e testado no Play

- **Painel de nível:** caveira no medalhão laranja, selo octogonal com o nível, barra de XP com "+XP" piscando e pulso ao subir de nível. Diminui sozinho em tela de celular. O painel de Sucata tem o mesmo visual.
- **Lobby:** noite chuvosa com neblina azul e roxa, chão molhado com reflexo, chuva com som (para debaixo de teto), ponte metálica, torre com holofote verde, postes antigos, pichação "JUNTOS SOMOS MAIS FORTES" e ícones holográficos nos 4 portais.
- **8 armas 3D** geradas pela IA do Roblox, todas compatíveis com as skins.
- **Sensação de tiro:** recuo com mola, clarão e fumaça no cano, cápsulas ejetadas, faíscas, poeira, marcas de bala, sangue, telha da Escopeta e tambor da Magnum animados.
- **Pose de duas mãos** com cinemática inversa própria (o rig usa AnimationConstraint), vista pelos outros jogadores.
- **Zumbis:** animação oficial de zumbi do Roblox, morte com ragdoll e gemidos com tom diferente por tipo.
- **Raid "Avenida Quarentena":** calçadas, poças, entulho, barris em chamas, postes acesos, carros, ônibus, viaturas, barreiras, caçambas, lixo e pneus, mais um clima esverdeado só durante a raid.

## Bugs corrigidos

- O ragdoll dos zumbis arremessava o jogador pro céu. Agora o corpo usa um grupo de colisão que só colide com o cenário.
- A barra de armas mostrava armas duplicadas.
- O material de metal enferrujado não carregava.

## Próximos passos

1. **Desempenho:** com 40 zumbis o cliente fica em uns 32–38 FPS. Falta limitar quantos zumbis ficam vivos ao mesmo tempo e simplificar os enfeites deles.
2. **Jogabilidade:** revisar bosses, ondas e progressão.
3. **Multijogador:** testar com 2 a 4 jogadores.
4. **Limpeza:** apagar a pasta `_Estudio` do Workspace.

## Guardado no ServerStorage

- Backup da arena antiga.
- Pasta `Props` com os objetos gerados.
- Ferramenta de preparo de armas.
