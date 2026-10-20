<h1 align="center">Gabriel Lima</h1>

<p align="center">
  <b>Desenvolvedor Full-Stack</b> · Python · FastAPI · HTMX · Next.js · React · SQL<br>
  Estagiário de Desenvolvimento de Sistemas na <b>ANAC</b> (Agência Nacional de Aviação Civil)
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/gabriel-lima000/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:bibis.gabriel@icloud.com"><img src="https://img.shields.io/badge/bibis.gabriel%40icloud.com-333333?style=for-the-badge&logo=icloud&logoColor=white" alt="bibis.gabriel@icloud.com"></a>
  <a href="https://gabriel00lima.github.io/worlds-2026-analytics/"><img src="https://img.shields.io/badge/Projeto_ao_vivo-Worlds_2026-C89B3C?style=for-the-badge&logo=leagueoflegends&logoColor=white" alt="Worlds 2026"></a>
</p>

<p align="center">📧 <b>bibis.gabriel@icloud.com</b></p>

<p align="center">🇧🇷 <a href="#-português">Português</a> · 🇺🇸 <a href="#-english">English</a></p>

---

## 🇧🇷 Português

Desenvolvo sistemas de ponta a ponta: banco de dados, API, regras de negócio e interface. Na ANAC, trabalho num sistema que transforma normas da aviação civil em dados estruturados e versionados. Fora dele, construo produtos para usuários reais: uma plataforma de torneios e loja online para uma organizadora de eventos esportivos, e uma central de estatísticas do Mundial de League of Legends que está no ar.

### 💼 Experiência

**Estagiário de Desenvolvimento de Sistemas · ANAC**
*Parser de Atos Normativos*: sistema web que lê o texto de resoluções, portarias e RBACs com uma gramática ANTLR e grava cada artigo, parágrafo, inciso e tabela como um registro versionado no banco, preservando todo o histórico de alterações.

O que eu desenvolvi:
- **Mapa de alterações:** tela que mostra quais atos alteram, acrescentam, suprimem ou revogam partes de outros, com visão geral, detalhe dispositivo a dispositivo (paginado) e linha do tempo que abre a versão vigente em cada data.
- **Tabelas dentro das normas:** criação por grade (linhas, colunas, mesclagem e cabeçalho) ou colando o HTML oficial, que é sanitizado automaticamente. Inclui prévia em tempo real feita com uma transação de ensaio (grava e desfaz), propagação entre versões do ato, trava contra gravar na versão errada, limites de tamanho, CLI de manutenção e **46 testes automatizados**.
- **Interface:** componentes server-side em Python com FastHTML e MonsterUI, e atualizações parciais de página com HTMX (`hx-swap-oob`), sem recarregar a tela.

No dia a dia: branch por funcionalidade, Conventional Commits, pull requests com code review e daily com a equipe.

`Python` `FastAPI` `FastHTML` `HTMX` `MonsterUI` `SQLModel` `SQLAlchemy` `Oracle` `ANTLR` `pytest` `ruff` `uv`

### 🚀 Projetos em destaque

#### 🏆 [Central do Worlds 2026](https://github.com/gabriel00lima/worlds-2026-analytics) · [ver ao vivo](https://gabriel00lima.github.io/worlds-2026-analytics/)
Site e API com chaveamento, partidas, estatísticas de jogadores e times, meta de campeões, comparações e replays narrados do Mundial de LoL 2026.
- **Pipeline de dados em Python** que consome a API do LoL Esports, processa a timeline de cada partida e gera um site estático publicado no GitHub Pages.
- **API REST em FastAPI** sobre **PostgreSQL**, com migrations em **Alembic**, e ambiente completo em **Docker Compose**.
- **Qualidade:** CI no GitHub Actions com `ruff`, `mypy` e `pytest`.
- Replay com estimativa da posição dos jogadores no mapa, mesmo sem coordenadas no feed de dados.

`Python` `FastAPI` `PostgreSQL` `Alembic` `Docker` `JavaScript` `GitHub Actions`

#### 🏐 Dream Lab Sports: site, gestão de torneios e loja *(cliente real, repositório privado)*
Plataforma para uma organizadora de eventos de futevôlei e vôlei de praia.
- **Site público** e **painel administrativo** para rodar o torneio no dia do evento, com regras e categorias configuráveis pelos próprios organizadores.
- **Loja online:** carrinho, variação de tamanhos, pagamento via Pix e cartão, estoque automático e tela de gestão de pedidos.
- **Kanban de conteúdo** mobile-first dentro do admin, usado pelos donos para planejar as redes sociais.

`Next.js` `React` `Supabase` `PostgreSQL`

#### 🚗 [LavExpress](https://github.com/gabriel00lima/lima-lavexpress-python)
App de agendamento para lava-jato, com app mobile, painel web e backend com autenticação JWT.

`FastAPI` `React Native` `Angular` `Java`

### 🛠️ Stack

| Área | Tecnologias |
|---|---|
| Back-end | Python, FastAPI, Java, REST, JWT, ANTLR |
| Front-end | Next.js, React, React Native, Angular, HTMX, FastHTML, JavaScript, Tailwind |
| Dados | PostgreSQL, Oracle, Supabase, SQLModel, SQLAlchemy, Alembic |
| DevOps e qualidade | Docker, GitHub Actions, pytest, ruff, mypy, uv, Git |

---

## 🇺🇸 English

<details>
<summary><b>Click to expand</b></summary>

<br>

Full-stack developer building systems end to end: databases, APIs, business logic and user interfaces. At **ANAC** (Brazil's National Civil Aviation Agency) I work on a system that turns aviation regulations into structured, versioned data. Outside work I ship products for real users.

### 💼 Experience

**Systems Development Intern · ANAC (Brazilian Civil Aviation Authority)**
*Regulatory Acts Parser*: a web system that parses resolutions, ordinances and aviation regulations (RBAC) with an ANTLR grammar and stores every article, paragraph, item and table as a versioned database record, keeping the full amendment history.

What I built:
- **Amendment map:** a view of which acts amend, add to, suppress or revoke parts of others, with an overview, a paginated provision-by-provision diff and a timeline that opens the version in force on each date.
- **Tables inside regulations:** created from a grid editor (rows, columns, merged cells, headers) or by pasting the official HTML, which is sanitized automatically. Live preview through a dry-run transaction (write and roll back), propagation across versions, a guard against writing to the wrong version, size limits, a maintenance CLI and **46 automated tests**.
- **User interface:** server-side Python components with FastHTML and MonsterUI, and partial page updates with HTMX (`hx-swap-oob`), with no full reloads.

Workflow: feature branches, Conventional Commits, pull requests with code review and daily stand-ups.

### 🚀 Featured projects

**🏆 [Worlds 2026 Hub](https://github.com/gabriel00lima/worlds-2026-analytics) · [live demo](https://gabriel00lima.github.io/worlds-2026-analytics/)**
Site and API for the 2026 League of Legends World Championship: bracket, matches, player and team stats, champion meta, comparisons and narrated replays.
- Python data pipeline consuming the LoL Esports API, processing each match timeline and generating a static site on GitHub Pages.
- FastAPI REST API on PostgreSQL, Alembic migrations, Docker Compose environment.
- CI on GitHub Actions with ruff, mypy and pytest.

**🏐 Dream Lab Sports: website, tournament management and online store** *(real client, private repo)*
Public site plus admin panel for running beach sports tournaments with configurable rules, an online store (cart, sizes, Pix and card payments, automatic stock, order management) and a mobile-first content kanban. Built with Next.js and Supabase.

**🚗 [LavExpress](https://github.com/gabriel00lima/lima-lavexpress-python)**
Car-wash scheduling app with a mobile app, web dashboard and JWT-authenticated backend (FastAPI, React Native, Angular, Java).

### 🛠️ Stack
Python · FastAPI · Java · ANTLR · Next.js · React · React Native · Angular · HTMX · FastHTML · PostgreSQL · Oracle · Supabase · SQLAlchemy · Docker · GitHub Actions

</details>

---

<p align="center"><i>Aberto a oportunidades como Desenvolvedor Full-Stack · Open to Full-Stack Developer roles</i></p>
