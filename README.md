# Convenção de nomes de arquivos

Este documento define o padrão de nomenclatura para arquivos e pastas do projeto, com o objetivo de manter organização, legibilidade e escalabilidade.

Todos os arquivos devem seguir o padrão:

```
Tipo_Oque_Contexto.algo
```

## Regras gerais
- Usar snake_case (maiúsculo com _)
- Sem espaços ou acentos
- Ser descritivo e direto

O contexto pode ser:
- cena (fase1, menu, boss)
- localização (cozinha, floresta)
- variação (v1, quebrado, novo)

## Formato Básico

| Tipo             | Prefixo  | Descrição                   | Exemplo                       |
| ---------------- | -------- | --------------------------- | ----------------------------- |
| **Modelos 3D**   | `Model`  | Objetos 3D                  | `Model_Mesa_Cozinha.fbx`      |
| **Materiais**    | `Mat`    | Materiais do Unity          | `Mat_Mesa_Madeira.mat`        |
| **Texturas**     | `Tex`    | Imagens usadas em materiais | `Tex_Madeira_Clara.png`       |
| **Shaders**      | `Shader` | Shaders customizados        | `Shader_Agua_Lago.shader`     |
| **Áudios (SFX)** | `Sfx`    | Efeitos sonoros             | `Sfx_Porta_Abrindo.wav`       |
| **Músicas**      | `Music`  | Trilha sonora               | `Music_Menu_Principal.mp3`    |
| **UI**           | `Ui`     | Elementos de interface      | `Ui_Botao_Jogar.png`          |
| **Animações**    | `Anim`   | Animações                   | `Anim_Player_Correndo.anim`   |
| **Prefabs**      | `Prefab` | Prefabs do Unity            | `Prefab_Inimigo_Zumbi.prefab` |
| **Cenas**        | `Scene`  | Scenes do Unity             | `Scene_Fase1.unity`           |

## ⚠️ Exceções (Padrões do Unity)

| Tipo                   | Exemplo             | Observação                                                          |
| ---------------------- | ------------------- | --------------------------------------------------------------------|
| **Scripts**            | `PlayerMovement.cs` | Nome da classe deve bater com o arquivo                             |
| **Prefabs (opcional)** | `EnemyZombie`       | Se quiser alinhar com código                                        |
| **Pastas**             | `Third Party`       | Para pastas é liberado usar espaço e iniciais em maíusculo          |

Para convenções de código, dêem uma olhada em [Code Name Conventions](https://github.com/Senac-Code-Nuts/Code-Conventions)


