# Mod de Botões do Xbox para God of War III Remastered PC

<div align="center">

[![Plataforma](https://img.shields.io/badge/Plataforma-Windows%20%7C%20Linux%20(AppImage)-0078D6?logo=windows&logoColor=white)](#compatibilidade)
[![Port do Jogo](https://img.shields.io/badge/Port-God%20of%20War%20III%20PC-E62828?logo=playstation&logoColor=white)](https://github.com/FelipePrado0/gow3_pc)
[![Tipo de Mod](https://img.shields.io/badge/Tipo-Interface%20%26%20QTEs%20Xbox-107C10?logo=xbox&logoColor=white)](#recursos)
[![Instalação](https://img.shields.io/badge/Instala%C3%A7%C3%A3o-N%C3%A3o--Destrutiva%20(Pasta%20mods)-brightgreen)](#como-instalar)
[![Licença](https://img.shields.io/badge/Licen%C3%A7a-GPL--2.0-yellow.svg)](LICENSE)

[English](README.md) | **Português (Brasil)**

</div>

Um mod completo de substituição dos botões do controle para o port de PC de **God of War III Remastered** (Windows / Linux). Substitui os comandos nativos de PlayStation pelos botões oficiais do **Controle Sem Fio Xbox** em todos os menus, tutoriais, QTEs, pontos de interação e ícones flutuantes de execução nos inimigos.

> [!IMPORTANT]
> **Nenhum arquivo protegido por direitos autorais do jogo é redistribuído.** Este mod contém apenas arquivos de textura de interface modificados (`WAD`) que são sobrepostos na memória do jogo de forma não destrutiva sobre a sua própria cópia/dump do PS4.
> Este projeto não é afiliado à Sony Interactive Entertainment, Santa Monica Studio ou Microsoft. God of War é uma marca registrada da Sony Interactive Entertainment.

---

## Conteúdo

- [Demonstração Visual](#demonstração-visual)
- [Recursos](#recursos)
- [Estilos Disponíveis (Presets)](#estilos-disponíveis-presets)
- [Como Instalar](#como-instalar)
- [Como Trocar de Estilo](#como-trocar-de-estilo)
- [Compatibilidade](#compatibilidade)
- [Como Funciona](#como-funciona)
- [Créditos](#créditos)
- [Licença](#licença)

---

## Demonstração Visual

![Comparativo das 5 versões visuais](comparativo_todas_as_versoes.png)

---

## Recursos

- **Mapeamento Completo para Xbox**: Substitui todos os botões frontais do PlayStation ($\times, \bigcirc, \square, \triangle$) pelos botões do Xbox (**A, B, X, Y**), e os botões de ombro ($L1, R1, L2, R2$) pelos bumpers e gatilhos (**LB, RB, LT, RT**).
- **Molduras de Fogo Originais Preservadas**: Mantém as icônicas molduras animadas de fogo características do God of War ao redor de cada botão na tela.
- **Menu de Controles Personalizado**: O menu `Opções -> Controles -> Visualização do Controle` exibe um Controle Sem Fio Xbox moderno com gatilhos, bumpers e discos coloridos correspondentes.
- **Correção do Botão 3D Flutuante no Inimigo**: Corrige o bug de UV invertido do modelo 3D de agarrar (`MDL_5cef139e` em `R_PERM.WAD`), garantindo que o botão **B** flutuando sobre a cabeça dos inimigos atordoados nunca fique invertido ou espelhado.
- **Centralização e Proporção Equilibrada**: Prompts de ação (como o **RB** para puxar correntes ou abrir portas) possuem proporções generosas e alinhamento central milimétrico, evitando letras espremidas ou cortadas.
- **100% Não Destrutivo**: Não altera nenhum arquivo da sua cópia original do jogo (`Image0`).

---

## Estilos Disponíveis (Presets)

O repositório inclui **5 estilos tipográficos distintos**:

| Pasta do Estilo | Inspiração & Estilo | Tipografia dos Botões | Descrição |
| :--- | :--- | :--- | :--- |
| **`1_God_of_War_Classic`** | Espartano / Trilogia Clássica | `gowfont.ttf` | Letras gregas clássicas autênticas e espessas. Visual heroico e marcante que se funde perfeitamente ao anel de fogo original. |
| **`2_God_of_War_Modern`** | GoW 2018 & Ragnarök UI | `XboxClean-Bold.ttf` | Tipografia de interface moderna inspirada nos lançamentos recentes de PC da Santa Monica Studio, com alta legibilidade em QTEs. |
| **`3_Xbox_Official_Series`** | Xbox Series X\|S Oficial | `XboxClean-Bold.ttf` | Design contemporâneo do ecossistema Xbox oficial, com discos escuros suaves e as cores originais da Microsoft. |
| **`4_Spartan_Gold`** | Monte Olimpo / Ouro Imperial | `Cinzel-Black.ttf` | Letras imperiais romanas/gregas cinzeladas com nobreza e acabamento dourado espartano divino. |
| **`5_Berserker_Viking`** | Fúria Nórdica Berserker | `berserkere.ttf` | Tipografia agressiva entalhada à lâmina de machado com brasas ardentes forjadas em batalha. |

---

## Como Instalar

Não são necessários instaladores, scripts `.bat` ou programas de terceiros. A instalação consiste em apenas colocar a pasta na sua pasta `mods`:

1. Baixe ou clone este repositório.
2. Escolha a sua versão favorita (por exemplo: `1_God_of_War_Classic`).
3. Copie a pasta `EXEC` de dentro dela:
   ```text
   Xbox Controller Mod For God of War III PC Port/
   └── 1_God_of_War_Classic/
       └── EXEC/
   ```
4. Cole na pasta `mods/Xbox_Buttons/` do seu jogo:
   ```text
   God of War III Remastered (Pasta Raiz do Jogo)/
   ├── God of War III.exe
   ├── Play God of War III.exe
   └── mods/
       └── Xbox_Buttons/
           └── EXEC/
               └── WAD/
                   └── PS4_LE/
                       ├── R_PERM.WAD
                       └── R_UI.WAD
   ```
5. Inicie o jogo normalmente pelo **`Play God of War III.exe`** ou pelo **Playnite**!

---

## Como Trocar de Estilo

Para mudar para outro visual a qualquer momento:
1. Abra a pasta da nova versão que você quer (ex: `2_God_of_War_Modern`).
2. Copie a pasta `EXEC`.
3. Cole e substitua dentro de `mods/Xbox_Buttons/`.

---

## Compatibilidade

- **Sistema Operacional**: Windows 10/11 (64-bit) & Linux (AppImage).
- **Versões do Jogo**: Testado nas versões `CUSA01623` e `CUSA01715` (Atualizações 01.00 e 01.02).
- **Modos de Vídeo e Patches**: Compatível com patches de resolução (720p, 1080p, 1440p, 4K), 60/120 FPS e mods Ultrawide.

---

## Como Funciona

O executável do port de PC de God of War III possui um sistema virtual de arquivos embutido. Ao iniciar o jogo, qualquer pasta presente em `mods/<Nome_Do_Mod>/EXEC/` é montada sobre a rota `/app0/EXEC/` na memória sem alterar nada no disco do jogo original.

Como este mod modifica apenas as texturas internas do `R_UI.WAD` (interface 2D, menus, QTEs) e do `R_PERM.WAD` (ícone 3D de agarrar sobre os inimigos), seus arquivos originais do PS4 nunca são tocados. Para desinstalar, basta excluir a pasta `mods/Xbox_Buttons`.

---

## Créditos

- **Felipe Prado & kvicken**: Criadores do port de PC de God of War III Remastered.
- **Santa Monica Studio & Sony Interactive Entertainment**: Jogo original e recursos de arte.
- **Microsoft**: Design e marcas do controle Xbox.

---

## Licença

Este projeto é disponibilizado sob a licença **GNU General Public License v2.0 (GPL-2.0)** - compatível com a licença do projeto oficial do port de God of War III para PC.
