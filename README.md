# Tradução Dishonored (PT-BR)

Projeto de tradução completa e definitiva em Português do Brasil para o jogo **Dishonored 1** (versão PC / Steam), desenvolvido com fidelidade máxima ao cânone e terminologia oficial da Arkane Studios / Bethesda (alinhado com Dishonored 2).

> [!IMPORTANT]
> **Diferencial Exclusivo:** Pela primeira vez na história da comunidade brasileira, este projeto traduz os **diálogos falados dinâmicos dos NPCs em cenários 3D** (falas de guardas, conversas de ambiente, falas de história e escolhas de diálogo do jogador) diretamente nos pacotes de script do Unreal Engine 3 (`.upk`), superando as limitações das traduções antigas que cobriam apenas arquivos de texto `.int`.

---

## 📁 Arquivos Traduzidos até o Momento:

### 🎙️ Diálogos Dinâmicos em Cenários 3D (`CookedPCConsole/*.upk`):
- `DishonoredGame\CookedPCConsole\L_Tower_Script.upk`:
  - **100% dos Diálogos Falados e Legendas Dinâmicas do Prólogo:**
    - Diálogo do passeio de barco entre o Oficial Curnow e o timoneiro (*"Leve-nos direto para a Torre de Dunwall. Lorde Corvo tem notícias para a Imperatriz e viemos de muito longe."*, *"Soltar amarra!"*, *"Pressão constante!"*, etc.).
    - Conversas de ambiente dos guardas da Guarda da Cidade, operadores da eclusa e servos no cais.
    - Sessão de pintura entre Anton Sokolov e o Alto Supervisor Campbell reclamando da sidra e do retrato.
    - Discussão no gazebo entre a Imperatriz Jessamine Kaldwin e o Mestre Espião Hiram Burrows (*"São pessoas doentes, não criminosos. Eles são meus cidadãos, e nós vamos salvá-los da peste se pudermos. Todos eles."*).
    - Diálogos com a jovem Lady Emily Kaldwin (brincadeira de esconde-esconde, contagens, perguntas sobre a viagem e pedidos de aulas de escalada).
    - **Escolhas de Diálogo do Jogador (Corvo):** Respostas interativas em cena 3D traduzidas (*"Tudo bem, mais uma vez."*, *"Sinto muito, Emily, mas preciso ir ver a sua mãe."*, *"Tudo bem, pode ir..."*).
    - Emboscada dos assassinos de Daud e a morte da Imperatriz.
    - Proclamação do Lorde Regente Hiram Burrows culpando Corvo pelo assassinato.
    - Gritos de combate, barks de alerta e investigação de guardas, estritos religiosos dos Supervisores e reações à peste.

---

### 📜 Menus, Interface e Textos (`Localization/INT/*.int`):
- `DishonoredGame.int`:
  - **Menu Principal Completo:** Novo Jogo, Missões, Estatísticas, Dificuldades (Fácil, Normal, Difícil, Muito Difícil e modos de Daud), Extras.
  - **Nomes Canônicos de Todas as Missões e Mapas:** Desonrado, Alto Supervisor Campbell, Casa dos Prazeres, O Médico Real, O Último Baile de Lady Boyle, Retorno à Torre, O Distrito Inundado, Os Leais, A Luz no Fim, etc.
  - **Interface do Diário (Journal):** Objetivos, Pistas, Tarefas, Audiógrafos, Notas, Livros, Mapas, Amuletos de Osso, e todos os Poderes (*Translação*, *Visão Sombria*, *Enxame Devorador*, *Dobrar o Tempo*, *Possessão*, *Rajada de Vento*, *Morte pelas Sombras*, etc.).
  - **Telas de Carregamento (Loading Tips):** 100% das 384 dicas e textos contextuais de carregamento traduzidos em todas as 41 seções do jogo.
  - **HUD em Jogo:** Objetivos (Concluído, Falhou, Atualizado, Novo), Notificações de Alvos (Assassinado, Neutralizado, Resgatado, Poupado) e Loja de Melhorias do Piero.
  - **Tutoriais e Mensagens de Sistema:** Todos os tutoriais de gameplay e telas de diálogo/erros do sistema.

- `Settings.int`:
  - **Menu de Opções / Configurações Completo:** Mapeamento de Teclas e Mouse, Esquemas de Controle, Configurações de HUD, Jogabilidade, Vídeo/Gráficos, Áudio e Nomes de todas as teclas.

- `Subtitles.int`:
  - **Legendas de Cutscenes e Vídeos:** 100% das legendas das cenas cinematográficas e monólogos narrados (Carta da Imperatriz Jessamine a Corvo na introdução, todos os monólogos de Daud em *The Knife of Dunwall* e *The Brigmore Witches*, e todos os desfechos/finais em Alto e Baixo Caos).

- `Twk_ChapterInfoList.int`, `DLC06_ChapterInfoList.int`, `DLC07_ChapterInfoList.int`:
  - **Textos de Introdução e Telas de Carregamento de Missão:** Títulos e descrições contextuais de todos os capítulos (incluindo o Prólogo "Retorno ao Lar", "Desonrado", "Alto Supervisor Campbell", "A Luz no Fim" e capítulos das DLCs).

- `L_Tower_Script.int` e `L_Prison_Script.int`:
  - **Scripts e Tutoriais do Início do Jogo:** Todos os tutoriais em jogo (olhar com o mouse, movimentação, corrida, esgueirar-se, bloqueio, combate, esconde-esconde com Emily, chaves das celas e pátio da Prisão de Coldridge).

- `Tower_Objectives.int` e `Prison_Objectives.int`:
  - **Objetivos de Missão:** Todos os objetivos, tarefas primárias e secundárias do Prólogo na Torre e da Fuga da Prisão de Coldridge.

- `AudioGraph_Twk.int`, `DLC06_AudioGraph_Twk.int`, `DLC07_AudioGraph_Twk.int`, `AudioGraph_Assets.int`:
  - **Audiógrafos / Gravações de Voz:** Transcrições e descrições completas de todos os 55 audiógrafos do jogo base e expansões (gravações de voz in-game de Hiram Burrows, Anton Sokolov, Slackjaw/Crowley, Daud, Callista, Havelock, Lorde Pendleton, Piero, Samuel, Emily e Rothwild).

---

## 🚀 Como Instalar no seu PC:

1. Baixe os arquivos desta pasta ou clone o repositório.
2. Certifique-se de que o jogo na Steam esteja configurado no idioma **Inglês** (o jogo lê por padrão os arquivos da pasta `INT`).
3. Copie a pasta `DishonoredGame` deste repositório e cole na raiz de instalação do seu jogo:
   ```text
   C:\Program Files (x86)\Steam\steamapps\common\Dishonored\
   ```
4. Confirme a substituição dos arquivos existentes quando o Windows solicitar.
5. Inicie o jogo e aproveite os menus, telas de loading, cutscenes e as falas dinâmicas em 3D totalmente em português!
