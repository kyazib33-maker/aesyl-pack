# Aesyl Pack

Repositório de distribuição do modpack do **Aesyl**, um servidor modded de Minecraft Java Edition 1.20.1 (Forge 47.4.10).

Este repositório guarda só as Releases do pack: os mods, as configurações, os resource packs e os shaders do servidor, junto com um `manifest.json` que lista cada arquivo com o seu SHA-256. O **Aesyl Launcher** e o atualizador de pack leem esse manifesto para manter a instância do jogador na mesma versão do servidor.

## Como funciona

- Cada Release `pack-vX.Y.Z` contém os arquivos do pack e o `manifest.json`.
- A Release mais recente (`latest`) é a versão atual. O manifesto dela fica em:
  `https://github.com/kyazib33-maker/aesyl-pack/releases/latest/download/manifest.json`
- O cliente só baixa o que mudou, confere o SHA-256 de cada arquivo e remove jars que não fazem parte do pack.
- Os saves, as opções e as capturas de tela do jogador não são tocados.

## Requisitos

- Uma cópia legítima do Minecraft Java Edition.
- Java 17.
- Forge 47.4.10 para Minecraft 1.20.1.
- Pelo menos 12 GB de RAM no computador (o pack é pesado).

## O que este repositório não contém

- Nenhum arquivo do jogo da Mojang (cliente, assets ou bibliotecas).
- Nenhum segredo, senha, token ou dado de jogadores.

## Aviso

Este é um projeto de comunidade. **Não é um produto oficial do Minecraft e não é afiliado nem endossado pela Mojang Studios ou pela Microsoft.** Minecraft é uma marca registrada da Mojang Studios.

Cada mod do pack pertence aos seus respectivos autores e segue a licença original deles.
