[English](README.md) · **Português** · [Español](README.es.md)

# Diego Riviere Padilha

Fundador, **RA** (RA Performance · RA Studios · RA Education) · Construindo o **Vivers de Cardedeu BOS** (viveiro familiar) · São Paulo · Nova York · Barcelona

Formação em finanças (finanças estruturadas CMBS na Moody's), hoje construindo produtos e experimentos de IA para pequenas empresas no Brasil e na Espanha, como projetos paralelos no meu tempo livre. Cuido do ciclo inteiro: arquitetura, código e QC.

> **A RA é um projeto pessoal. Tudo aqui é feito no meu tempo livre.**

[rastudios.com.br](https://rastudios.com.br) · [LinkedIn](https://linkedin.com/in/diegopadilha/) · diego.padilha2000@gmail.com

---

## O que estou construindo

### RA · 2026 – atual
Meu projeto pessoal, com três braços. O mesmo método em todos: spec primeiro, QC antes de entregar, e eu cuido do ciclo inteiro (arquitetura, código, QC).

**RA Performance — performance de pessoas e de negócios**
Apps construídos em torno de treino e coaching.

- **RA One:** app iOS para treinar em grupo (atividade compartilhada, posts, convites do seu pack). Swift + Supabase, em TestFlight (1.0), construído com um sócio · [privacidade e suporte](https://github.com/dpadilha1/raone-site)
- **Einstein Bud:** coach de check-in no WhatsApp para atletas, construído com ElevenLabs Agents. Em andamento.
- **Papel:** produto e engenharia

**RA Studios — projeto de estúdio digital**
Um projeto de estúdio que constrói sites, apps, consultoria de IA e filmes de produto para pequenas empresas no Brasil.

- **Design de sites:** landing pages, sites institucionais, lojas online e páginas link-in-bio. Feitos à mão em HTML / CSS / JS, portáveis para qualquer hospedagem, no ar na Cloudflare (Workers + Resend para formulários).
- **Apps:** web apps, ferramentas internas e apps mobile. Desenhados pela RA Studios: RA One e Vivers BOS (veja as seções deles).
- **Consultoria de IA:** ajudando empresas a adotar IA, do treinamento da equipe à implementação.
- **Filmes (5–60 s):** filmes de produto gerados no ElevenLabs / Higgsfield.
  - **Pipeline:** briefing → prompt de geração → QC em Python (geometria, loudness EBU R128, end-card frame a frame) → entrega
  - **Stack:** ElevenLabs · Higgsfield · Python / ffmpeg · Meta Ads
- **Status:** site de portfólio público · [rastudios.com.br](https://rastudios.com.br) · [@rastudios_br](https://instagram.com/rastudios_br) (Instagram)

**RA Education — ensinando o Brasil a usar IA**
Uma página no LinkedIn recém-lançada, "Ensinando o Brasil a usar IA", levando IA prática a profissionais, escolas, jovens e comunidades de baixa renda no Brasil.

- **Skills open source:** [ra-education-skills](https://github.com/dpadilha1/ra-education-skills), skills reutilizáveis para agentes de IA (Claude Code, Codex, Gemini CLI). A primeira: `/cleanup`, que audita um projeto atrás de segredos vazados, excesso de arquivos, docs desatualizados e tokens desperdiçados. Licença MIT.

### Vivers de Cardedeu — Business Operating System · nov 2025 – atual
Um sistema operacional para o [Vivers de Cardedeu](https://viverosdecardedeu.com/en/), viveiro familiar em Cardedeu (Barcelona): estoque, CRM, pedidos, relatórios e mapa de vendas — desenhado para virar um SaaS multi-tenant para PMEs espanholas.

- **Papel:** product lead — modelo de dados, regras de negócio e roadmap
- **Design:** estoque por variante · toda movimentação auditada · ciclo de pedido `DRAFT → FINALIZED → CANCELLED` · relatórios só sobre FINALIZED
- **Stack:** Node.js / Express · PostgreSQL / Prisma · Zod · Next.js 14 · React 18 · TypeScript · Tailwind · React Query · Leaflet · i18n (es / ca / en)
- **Status:** em testes internos antes do rollout · [viverosdecardedeu.com](https://viverosdecardedeu.com/en/)

Todos os códigos-fonte são privados.

---

## Como trabalho
Spec primeiro, depois build. Toda entrega é validada contra a spec antes de sair. Mudanças aditivas em vez de reescritas. Documentar tudo.

## Stack
Python · JavaScript / TypeScript · Node.js · PostgreSQL / Prisma · Next.js / React · Swift · ElevenLabs · Higgsfield · Supabase · Cloudflare · ffmpeg

## Background
Mestrado em Finanças, Georgia State (tênis NCAA D1). Ratings de finanças estruturadas (CMBS / CRE) na Moody's, onde avalio imóveis comerciais, classifico bonds e melhoro a eficiência de processos internos.

Fora do teclado: finisher de Ironman 70.3, treinando para o próximo.
