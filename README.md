# Tradução Dishonored (PT-BR)

Projeto de tradução completa e definitiva em Português do Brasil para o jogo **Dishonored 1** (versão PC / Steam), desenvolvido com fidelidade máxima ao cânone e terminologia oficial da Arkane Studios / Bethesda (alinhado com Dishonored 2).

> [!IMPORTANT]
> **Diferencial Exclusivo:** Além de traduzir **100% dos 658 arquivos de texto do jogo base e todas as DLCs**, este projeto traduz os **diálogos falados dinâmicos dos NPCs em cenários 3D** (falas de guardas, conversas de ambiente, falas de história e escolhas de diálogo do jogador) diretamente nos pacotes de script do Unreal Engine 3 (`.upk`), superando as limitações históricas das traduções antigas.

---

## 📁 Conteúdo Traduzido no Projeto:

### 🎙️ 1. Diálogos Dinâmicos em Cenários 3D (`CookedPCConsole/*.upk`):
- `DishonoredGame\CookedPCConsole\L_Tower_Script.upk`:
  - **100% dos Diálogos Falados e Legendas Dinâmicas do Prólogo:**
    - Diálogo do passeio de barco entre o Oficial Curnow e o timoneiro (*"Leve-nos direto para a Torre de Dunwall. Lorde Corvo tem notícias para a Imperatriz e viemos de muito longe."*, *"Soltar amarra!"*, *"Pressão constante!"*, etc.).
    - Conversas de ambiente dos guardas da Guarda da Cidade, operadores da eclusa e servos no cais.
    - Sessão de pintura entre Anton Sokolov e o Alto Supervisor Campbell reclamando da sidra e do retrato.
    - Discussão no gazebo entre a Imperatriz Jessamine Kaldwin e o Mestre Espião Hiram Burrows (*"São pessoas doentes, não criminosos. Eles são meus cidadãos, e nós vamos salvá-los da peste se pudermos. Todos eles."*).
    - Diálogos com a jovem Lady Emily Kaldwin (brincadeira de esconde-esconde, contagens de 1 a 15, perguntas sobre a viagem e pedidos de aulas de escalada).
    - **Escolhas de Diálogo do Jogador (Corvo):** Respostas interativas em cena 3D traduzidas (*"Tudo bem, mais uma vez."*, *"Sinto muito, Emily, mas preciso ir ver a sua mãe."*, *"Tudo bem, pode ir..."*).
    - Emboscada dos assassinos de Daud e a morte da Imperatriz.
    - Proclamação do Lorde Regente Hiram Burrows culpando Corvo pelo assassinato.
    - Gritos de combate, barks de alerta e investigação de guardas, estritos religiosos dos Supervisores e reações à peste.

- `DishonoredGame\CookedPCConsole\L_Prison_Script.upk`:
  - **100% dos Diálogos Falados e Legendas Dinâmicas da Prisão de Coldridge (Missão 1):**
    - Entrega do pão com a chave na cela de Corvo (*"O jantar está servido, Lorde Protetor. Coma a sua comida, Corvo. É de um amigo. Alguns de nós ainda acreditam em você."*).
    - Interrogatório da sala de tortura com o Lorde Regente Hiram Burrows e o Alto Supervisor Campbell confessando o plano (*"Corvo, a Imperatriz está morta, a filha dela, Emily, está escondida, e ninguém jamais saberá a verdade... Quando sua cabeça rolar no chão, quero que saiba que nós estaremos sorrindo."*).
    - Falas e reações de todos os prisioneiros nas celas (*"Diga ao Crowley que estou aqui! Ele tem que me tirar daqui!"*, *"Queimem este lugar até o chão!"*, etc.).
    - Anúncios oficiais do sistema de alto-falantes da prisão (*"Aviso: Corvo Attano, outrora Protetor Real e o assassino que vitimou a nossa amada Imperatriz, escapou de sua cela. A Prisão de Coldridge está agora em confinamento total."*).
    - Descoberta da cela vazia, perseguição dos guardas no pátio da prisão, explosão da porta externa e fuga rumo aos esgotos (*"Ele está indo para os esgotos! Se ele chegar ao esgoto nós vamos perdê-lo!"*).

- `DishonoredGame\CookedPCConsole\L_PrsnSewer_Script.upk`:
  - **100% dos Diálogos Falados e Legendas Dinâmicas dos Esgotos da Prisão (Fuga de Coldridge):**
    - Encontro com Samuel Beechworth na saída dos esgotos (*"Corvo, aqui! Rápido. Eu sou um amigo. Eu sou o Samuel, e trabalho para um pessoal de bem que quer muito conhecer você. Suba. Temos uma refeição quente e uma cama confortável esperando por você."*).
    - Escolhas de diálogo com Samuel no barco (*"Tudo bem, meu velho. Vamos."*, *"Espere aqui. Preciso de um momento primeiro."*).
    - Conversas dos guardas descartando cadáveres da peste nos esgotos (*"De onde veio essa carga de cadáveres? A Guarda isolou o Distrito do Tabaco... Deixe os ratos comerem."*).
    - Transmissões oficiais da Guarda da Cidade pelo rádio alertando toda Dunwall sobre a fuga de Corvo.

---

### 📜 2. Todos os Textos, Menus, Objetivos e Livros (`Localization/INT/` - 658 Arquivos):
- **Menu Principal e Interface Geral (`DishonoredGame.int`, `Settings.int`):**
  - Menus completos, opções gráficas, áudio, mapeamento de teclas e controles.
  - Journal/Diário completo, inventário, HUD, tela de melhorias do Piero e todas as 384 dicas de tela de carregamento.
- **Telas de Carregamento e Introdução de Capítulos (`Twk_ChapterInfoList.int`, etc.):**
  - 100% dos títulos e resumos contextuais de cada missão ("Retorno ao Lar", "Desonrado", etc.).
- **Legendas de Cenas e Monólogos (`Subtitles.int`):**
  - Todas as cenas pré-renderizadas e monólogos narrados (Imperatriz Jessamine e Daud).
- **Livros, Notas, Cartas, Pistas e Diários (`WrittenNotes_twk.int`, `ChapterNotes_twk.int`):**
  - Mais de 300 KB de textos de história e lore do mundo de Dunwall, cartas, diários pessoais, cartazes e livros religiosos.
- **Objetivos de Todas as Missões da Campanha Principal:**
  - `Prison_Objectives.int` (Prisão de Coldridge)
  - `Streets_Objectives.int` (Alto Supervisor Campbell)
  - `Brothel_Objectives.int` (Casa dos Prazeres / Golden Cat)
  - `Bridge_Objectives.int` (Ponte de Kaldwin)
  - `Boyle_Objectives.int` (O Último Baile de Lady Boyle)
  - `Flooded_Objectives.int` (O Distrito Inundado)
  - `Lighthouse_Objectives.int` (A Luz no Fim)
- **Audiógrafos / Gravações de Voz (`AudioGraph_Twk.int`, etc.):**
  - Todos os 55 audiógrafos com transcrições fiéis.
- **Itens, Poderes, Armas e Melhorias (`Blueprints_twk.int`, `Pwn_*.int`, `Twk_*.int`):**
  - Todos os esquemas de Piero e Sokolov, amuletos de osso, poderes (*Translação*, *Visão Sombria*, *Possessão*, *Enxame Devorador*, etc.).
- **Expansões / DLCs (`DLC05_*`, `DLC06_*`, `DLC07_*`):**
  - *Dunwall City Trials*, *The Knife of Dunwall* e *The Brigmore Witches* traduzidos.

---

## 🚀 Como Instalar no seu PC:

1. Baixe os arquivos desta pasta ou clone o repositório.
2. Certifique-se de que o jogo na Steam esteja configurado no idioma **Inglês** (o jogo lê por padrão os arquivos da pasta `INT`).
3. Copie a pasta `DishonoredGame` deste repositório e cole na raiz de instalação do seu jogo:
   ```text
   C:\Program Files (x86)\Steam\steamapps\common\Dishonored\
   ```
4. Confirme a substituição de todos os arquivos existentes quando o Windows solicitar.
5. Inicie o jogo e aproveite o Dishonored 100% traduzido em Português do Brasil!
