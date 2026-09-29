<!-- =========================================================
     DUCKWSN — GitHub Profile
========================================================== -->

<div align="center">

# Duckwsn

### Software, games & experiments.

Transformando ideias em projetos reais, explorando desenvolvimento web,
jogos, ferramentas e novas experiências.

<br>

[![GitHub](https://img.shields.io/badge/GitHub-Duckwsn-181717?style=for-the-badge\&logo=github)](https://github.com/Duckwsn)

</div>

<br>

## 👋 Sobre mim

Desenvolvedor interessado em criar produtos que sejam realmente utilizáveis — desde aplicações web completas até jogos e ferramentas experimentais.

Gosto de trabalhar desde a ideia inicial e identidade visual até arquitetura, implementação, testes e deploy.

Atualmente, grande parte do meu trabalho está concentrada no desenvolvimento do **Lumio**, meu principal projeto.

<br>

<!-- =========================================================
     LUMIO
========================================================== -->

<div align="center">

<img src="./assets/lumio-banner.png" alt="Lumio" width="100%">

<br>
<br>

# ◈ LUMIO

### Watch. Listen. Talk. Together.

**Um espaço compartilhado para assistir, ouvir e conversar com quem você gosta.**

<br>

[![Repository](https://img.shields.io/badge/VER_REPOSITÓRIO-LUMIO-24332e?style=for-the-badge\&logo=github\&logoColor=white)](https://github.com/Duckwsn/Lumio)

</div>

<br>

O **Lumio** nasceu da ideia de reunir diferentes formas de estar junto online em um único ambiente.

Em vez de separar vídeo, música, chamadas e compartilhamento em várias aplicações, o Lumio organiza tudo ao redor de uma **Party compartilhada**.

Dentro dela, os participantes podem consumir conteúdo juntos, controlar uma fila compartilhada e conversar por voz enquanto o sistema mantém a experiência sincronizada.

### ✦ Principais recursos

* 🎬 **Player compartilhado** com reprodução sincronizada entre participantes
* 📺 **YouTube** integrado para busca e reprodução de conteúdo
* ☁️ **Google Drive** para acessar vídeos pessoais
* 🎵 Experiência preparada para diferentes tipos de mídia
* 📋 **Fila compartilhada** entre os participantes
* 🎙️ **Voice Call** integrada à Party
* 🏠 Sistema de **Parties privadas**
* 👥 Experiência pensada para amigos e família
* 🔄 Sincronização de estado em tempo real
* 📱 Interface responsiva e experiência mobile
* 💻 Experiência instalável como aplicação web

<br>

### 🧩 Ecossistema

```text
                       LUMIO
                         │
          ┌──────────────┼──────────────┐
          │              │              │
        PARTY          PLAYER          CALL
          │              │              │
    Participants    Shared Media      Voice
          │              │
          │        ┌─────┴─────┐
          │        │           │
          │     YouTube      Drive
          │
          └────────── Shared Queue
```

O objetivo é manter toda a experiência dentro de um mesmo ambiente, sem transformar cada funcionalidade em uma aplicação separada.

<br>

### ⚙️ Tecnologias utilizadas no Lumio

<div align="center">

![React](https://img.shields.io/badge/React-181818?style=for-the-badge\&logo=react\&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-181818?style=for-the-badge\&logo=typescript\&logoColor=3178C6)
![Vite](https://img.shields.io/badge/Vite-181818?style=for-the-badge\&logo=vite\&logoColor=646CFF)
![Node.js](https://img.shields.io/badge/Node.js-181818?style=for-the-badge\&logo=nodedotjs\&logoColor=5FA04E)

![Socket.IO](https://img.shields.io/badge/Socket.IO-181818?style=for-the-badge\&logo=socketdotio\&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-181818?style=for-the-badge\&logo=postgresql\&logoColor=4169E1)
![Docker](https://img.shields.io/badge/Docker-181818?style=for-the-badge\&logo=docker\&logoColor=2496ED)

</div>

<br>

### 🏗️ Arquitetura

O projeto é dividido entre frontend e backend, mantendo responsabilidades separadas para facilitar evolução e deploy.

```text
Browser
   │
   ▼
┌──────────────────────┐
│        Lumio Web     │
│   React + TypeScript │
│        + Vite        │
└──────────┬───────────┘
           │
           │ HTTP / WebSocket
           ▼
┌──────────────────────┐
│       Lumio API      │
│       Node.js        │
│      Socket.IO       │
└──────────┬───────────┘
           │
           ▼
┌──────────────────────┐
│      PostgreSQL      │
└──────────────────────┘

        + YouTube API
        + Google Drive API
        + WebRTC
```

A comunicação em tempo real é responsável por manter os participantes da Party sincronizados, enquanto o backend mantém o estado compartilhado e integra os serviços externos.

<br>

### 🚧 Status

O Lumio está em **desenvolvimento ativo**.

O foco atual é finalizar e estabilizar a primeira versão pública, trabalhando principalmente em:

```text
Performance
     ↓
Resiliência
     ↓
Persistência
     ↓
Deploy
     ↓
Lumio 1.0
```

Depois da primeira versão, o projeto continuará evoluindo com base no uso real e no feedback obtido.

<br>

<div align="center">

### ◈

**Lumio**

*Watch. Listen. Talk. Together.*

</div>

<br>

---

<!-- =========================================================
     OTHER PROJECTS
========================================================== -->

# Outros projetos

O Lumio é meu projeto principal, mas também desenvolvo jogos, ferramentas e experimentos em diferentes tecnologias.

<br>

### 🚀 Frações em Órbita

**Jogo educacional multiplayer sobre frações.**

Projeto criado para transformar exercícios matemáticos em uma experiência de jogo, utilizando um sistema de órbita onde o objetivo é completar exatamente um inteiro.

O projeto possui experiência local e multiplayer, sistema de perguntas, eventos e progressão baseada em frações.

`HTML` `CSS` `JavaScript` `Multiplayer`

<br>

### 🎮 Geokills

**Geometric survival game desenvolvido em C++ e Raylib.**

Um projeto inspirado no gênero survivor-like, explorando combate, movimentação, progressão e diferentes modos de jogo utilizando uma identidade visual geométrica.

O projeto também conta com o **Expedition Mode**, expandindo a estrutura tradicional de sobrevivência.

`C++` `Raylib` `CMake` `Game Development`

<br>

### ◉ Cerne

**Organização pessoal com abordagem local-first.**

Projeto voltado para centralizar informações e ferramentas pessoais mantendo uma experiência simples, rápida e independente.

`Web` `Local First`

<br>

### 📋 CA3 Planner

Ferramenta desenvolvida para auxiliar no **planejamento e organização de atividades**, trazendo informações importantes para uma interface centralizada.

`Web` `Productivity`

<br>

---

<!-- =========================================================
     TECHNOLOGIES
========================================================== -->

# 🛠️ Tecnologias

Tecnologias e ferramentas que fazem parte dos meus projetos:

<div align="center">

### Web

![TypeScript](https://img.shields.io/badge/TypeScript-181818?style=for-the-badge\&logo=typescript\&logoColor=3178C6)
![JavaScript](https://img.shields.io/badge/JavaScript-181818?style=for-the-badge\&logo=javascript\&logoColor=F7DF1E)
![React](https://img.shields.io/badge/React-181818?style=for-the-badge\&logo=react\&logoColor=61DAFB)
![HTML5](https://img.shields.io/badge/HTML5-181818?style=for-the-badge\&logo=html5\&logoColor=E34F26)
![CSS3](https://img.shields.io/badge/CSS3-181818?style=for-the-badge\&logo=css3\&logoColor=1572B6)

### Backend & Data

![Node.js](https://img.shields.io/badge/Node.js-181818?style=for-the-badge\&logo=nodedotjs\&logoColor=5FA04E)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-181818?style=for-the-badge\&logo=postgresql\&logoColor=4169E1)
![Socket.IO](https://img.shields.io/badge/Socket.IO-181818?style=for-the-badge\&logo=socketdotio\&logoColor=white)

### Games

![C++](https://img.shields.io/badge/C++-181818?style=for-the-badge\&logo=cplusplus\&logoColor=00599C)
![Raylib](https://img.shields.io/badge/Raylib-181818?style=for-the-badge\&logo=c\&logoColor=white)

### Tools

![Git](https://img.shields.io/badge/Git-181818?style=for-the-badge\&logo=git\&logoColor=F05032)
![GitHub](https://img.shields.io/badge/GitHub-181818?style=for-the-badge\&logo=github\&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-181818?style=for-the-badge\&logo=docker\&logoColor=2496ED)
![Vercel](https://img.shields.io/badge/Vercel-181818?style=for-the-badge\&logo=vercel\&logoColor=white)

</div>

<br>

---

<!-- =========================================================
     STATS
========================================================== -->

# 📊 GitHub

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=Duckwsn&show_icons=true&hide_border=true&theme=transparent&rank_icon=github" />

<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Duckwsn&layout=compact&hide_border=true&theme=transparent" />

</div>

<br>

---

<div align="center">

### Thanks for visiting.

Projetos são minha forma de aprender, experimentar e transformar ideias em algo que realmente possa ser usado.

<br>

**Duckwsn**

`build • experiment • improve`

</div>
