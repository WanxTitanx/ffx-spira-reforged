# Spira Reforged

## English

Public source and release channel for Spira Reforged. This repository contains
maintained authoring source and notices, without the private Editor history,
third-party Spira Mod Manager code, game dumps or native game binaries.

The authoring snapshot corresponds to Editor development commit
`536c8fb29ae64f273c07c2a54cdb85f07f93aa0f`; its complete filtered inventory is in
`authoring/SOURCE-MANIFEST.json`. See `authoring/SOURCE-README.md` for build inputs.
The existing GPL3 and third-party notices remain applicable.

Content version: `0.2.0`; release tag: `0.2.0-encounters`.
The managed content root is `data/mods` (FMX root `ffx-data-mods-v1`).
Tarot artwork, effects and Hooks configuration are a separate manual supplement
in `modules`, `magicFiles` and `_isolated`, installed relative to the game folder.
The FMX data package cannot install those other roots. Hooks is obtained
separately from [FFX Hooks](https://github.com/WanxTitanx/ffx-mod-hooks/releases).
Use a matching API4 build with regional SIN, Omega and Tarot support. Translation
packages must match the exact Spira tables; a vanilla PT-BR pack is not interchangeable.

Data packages are modifications for your existing FFX HD installation.
This release does not claim full gameplay validation. Dark Aeon T10,
progressive Touch/Imperil/Ward, Aurochs Reels changes and the low-MAG Omega Rite
are not advertised as completed functionality. New Game+ is outside this package.
See [complete bilingual notes](docs/0.2.0-encounters.md).

## Português (Brasil)

Canal público de fonte e releases do Spira Reforged. Este repositório contém
fonte de authoring e avisos de licença, sem histórico privado do Editor, código
do Spira Mod Manager de terceiros, dumps ou binários nativos do jogo.

A cópia de authoring corresponde ao commit de desenvolvimento do Editor
`536c8fb29ae64f273c07c2a54cdb85f07f93aa0f`; o inventário filtrado completo fica em
`authoring/SOURCE-MANIFEST.json`. Os inputs de build estão em
`authoring/SOURCE-README.md`. GPL3 e avisos de terceiros existentes são preservados.

Versão do conteúdo: `0.2.0`; tag de release: `0.2.0-encounters`.
A raiz gerenciada é `data/mods` (raiz FMX `ffx-data-mods-v1`).
Arte do Tarot, efeitos e configuração dos Hooks usam um suplemento manual
separado em `modules`, `magicFiles` e `_isolated`, relativo à pasta do jogo.
O pacote FMX de dados não instala essas outras raízes. Obtenha os Hooks
separadamente nas [releases FFX Hooks](https://github.com/WanxTitanx/ffx-mod-hooks/releases),
usando uma build API4 compatível com SIN regional, Omega e Tarot. A tradução
precisa corresponder às tabelas exatas do Spira; PT-BR vanilla não é intercambiável.

Os pacotes modificam sua instalação existente do FFX HD. Esta release
não atesta validação completa de uma partida. Dark Aeon T10, Touch/Imperil/Ward
progressivos, mudanças de Aurochs Reels e o Rite Omega de MAG baixo não são
anunciados como funcionalidades concluídas. New Game+ fica fora deste pacote.
Veja as [notas bilíngues completas](docs/0.2.0-encounters.md).
