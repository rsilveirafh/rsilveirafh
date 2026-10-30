# Ricardo Silveira

Zoologist by training, now working as a data and software engineer. For a decade I asked questions of biological data: phylogeography, herpetology, population genomics. Today I build the systems that turn environmental and field data into something a team can act on.

📍 Natal, RN, Brazil · he/him
[Website](https://rsilveirafh.netlify.app/) · [LinkedIn](https://linkedin.com/in/rsilveirafh) · [Lattes CV](http://lattes.cnpq.br/6028156427352678)

> **Open to work.** Looking for remote roles as a data scientist or developer in environmental data, ESG, biodiversity or research. Reach me at rsilveirafh@gmail.com or on [LinkedIn](https://linkedin.com/in/rsilveirafh).

---

## Recent work

I lead the development portfolio of the innovation team at [Seteg](https://www.setegce.com/), an environmental consultancy, where my contract ends in November 2026. The work falls into a few fronts.

**Field data collection.** Apps that replace paper forms and spreadsheets for biologists running fauna and flora surveys, so records arrive structured instead of being retyped weeks later.

**Business intelligence.** Dashboards in Power BI and in R/Shiny for coordinators and directors, built over operational data that used to live in systems that did not talk to each other.

**Environmental compliance and ESG.** A SaaS platform for compliance management, plus carbon inventories following the GHG Protocol.

**Energy analytics.** Analysis pipelines over hydro, solar and wind generation data.

**Platform consolidation.** Folding standalone internal systems into one platform. The instructive part was discovering that several modules already had working backends and nobody had migrated, which made it a cutover problem rather than a coding one.

Alongside the products I wrote the team's operating manual: how a requirement gets written, how git is used, how project boards are kept, and what the delivery lifecycle looks like from demand to handover. Most of the gain there came from putting documents that already existed into a defined order.

Before that I spent four years as a data scientist at Conciso TI, and more than a decade doing environmental consulting on the side, most recently as technical lead of a sea turtle monitoring program at the Port of Natal.

In every one of these jobs I went looking for the same thing: work people were repeating by hand, so I could build the system that does it once.

---

## How I work

**Spec before code.** A project starts as a written contract: brief, domain research, then requirements mapped one to one onto vertical MVP phases, each with explicit success criteria. Nothing gets built without a phase that owns it.

**Agents inside a pipeline.** I drive Claude Code through custom skills I wrote for planning, execution, verification and review, so the same discipline applies whether the code comes from me or from an agent. The ones worth sharing are published as plugins in my [claude-plugins](https://github.com/rsilveirafh/claude-plugins) catalog.

**Memory with a human in the loop.** An Obsidian vault where a daily journal goes in and structured proposals come out. I review every one before it is written.

**Green CI is not evidence.** Two of my releases shipped with type checks, tests and build all passing, and blockers waiting in production. Opening the live product by hand is now part of my definition of done.

---

## Selected work

| Project | What it is | Stack |
|---|---|---|
| **[tetrapoDNA](https://github.com/rsilveirafh/tetrapoDNA)** | Which Brazilian amphibians, reptiles, birds and mammals still have no public DNA sequence at all? A [live dashboard](https://rsilveirafh.github.io/tetrapoDNA/) checks every species on the official checklists against BOLD and GenBank each week, flags names that need a closer look (synonyms, genus transfers), ranks the gaps by threat and endemism, and lets researchers publicly adopt a species to sequence. | R, GitHub Actions, GitHub Pages |
| **[banca-simulada](https://github.com/rsilveirafh/banca-simulada)** | Claude Code plugin that reviews a research proposal the way a Brazilian thesis committee or grant panel would, from undergraduate thesis to faculty hiring exams. It checks coherence, method, feasibility, research ethics and references, quotes the passage, grades the severity and suggests a fix without rewriting. It can only cite regulations from a file checked against official sources. In three test runs on fictional proposals with 12 planted errors each, it caught all of them and never quoted a passage that was not in the text. | Claude Code plugin, Markdown, Python |
| **[memoria-skills](https://github.com/rsilveirafh/memoria-skills)** | Claude Code plugin that turns a Markdown vault into a memory system with a human gate. The agent proposes, I review, a separate command applies. Four commands, and one of them exists only to say no. Running daily on my own vault since May 2026. | Claude Code plugin, Markdown, Git |
| **[rr-quant](https://github.com/rsilveirafh/rr-quant)** | Personal quant dashboard. Pulls a 46-asset pre-market snapshot covering indices, commodities, FX, rates and volatility, then layers on regime and correlation reads, a logistic-regression scoreboard for the Ibovespa, and a Smart Money Concepts view over OHLC. Runs itself every trading session. | Python, yfinance, Vercel |
| **[carona-solidaria](https://github.com/rsilveirafh/carona-solidaria)** | Volunteer ride matching for voters with limited mobility in Brazil's 2026 runoff. Went from a neighbourhood idea to three cities (Natal, Recife, João Pessoa) in four days: official polling-place lists, driver approval, bot limits and automatic data deletion after the election. 44 drivers and 13 ride requests. Closed on schedule. | JavaScript PWA, Google Apps Script, GitHub Pages |
| **[dash_ppbio](https://github.com/rsilveirafh/dash_ppbio)** | *Panoramas da Biodiversidade Brasileira*, an interactive dashboard over occurrence and genetic data for PPBio, Brazil's Biodiversity Research Program. Built during my post-doctorate there in 2022. | R, flexdashboard, highcharter, plotly |
| **[postdoc_ppbio](https://github.com/rsilveirafh/postdoc_ppbio)** | Analysis scripts behind the same post-doctorate: species list assembly, taxonomic resolution through taxize, and the reporting pipeline. | R, taxize, Quarto |

**Open source contributions.** Bringing community datasets in line with Brazil's 2026 official lists: a [pull request](https://github.com/paulobarros/amphiBR/pull/2) updating the [amphiBR](https://github.com/paulobarros/amphiBR) R package to the 2026 Brazilian amphibian checklist and the new federal threat categories (MMA Ordinance 1,704/2026), and a [proposal](https://github.com/omarentiauspe/ReptiliaBR/issues/1) for the same threat-status update in [ReptiliaBR](https://github.com/omarentiauspe/ReptiliaBR).

---

## Research

PhD and MSc in Zoology at UFPB, working on herpetology, phylogenetics and phylogeography, mostly snakes. Two post-doctorates followed: UNEMAT from 2018 to 2019 on plant ecology and functional traits, and UFRN with PPBio from 2022 to 2023 on biodiversity and bioinformatics. Licentiate in Biological Sciences at UEFS.

Sixteen peer-reviewed articles. A selection:

- Brazil's natural grasslands under attack. *Science* 384:168–169 (2024)
- Hidden costs of Europe's deforestation policy. *Science* 379:341–342 (2023)
- Estimating synchronous demographic changes across populations using hABC. *Molecular Ecology* (2017)
- Influence of soil properties on woody vegetation structure, diversity and seasonality in Neotropical savannas. *Austral Ecology* 49:e13501 (2024)
- Herpetofauna of Nísia Floresta National Forest. *Biota Neotropica* 24:e20241643 (2024)

Full list on [Lattes](http://lattes.cnpq.br/6028156427352678).

---

## Stack

**Languages.** R at an advanced level, including Shiny, golem and Roxygen2, plus Python, TypeScript, JavaScript and SQL.
**Web.** Next.js, Tailwind, shadcn/ui, Supabase, PostgreSQL, Vercel.
**Data and science.** tidyverse, pandas, phylogenetics and population genomics toolchains, Power BI, QGIS, spatial analysis with sf.
**Infrastructure and practice.** Git, Docker, CI/CD, cloud, Scrum, Claude Code with custom agent skills.

---

<details>
<summary><b>🇧🇷 Em português</b></summary>

<br>

Biólogo de formação, hoje trabalhando como engenheiro de dados e software. Durante uma década fiz perguntas a dados biológicos: filogeografia, herpetologia, genômica de populações. Hoje construo os sistemas que transformam dados ambientais e de campo em algo sobre o que um time consegue agir.

📍 Natal, RN · [Site](https://rsilveirafh.netlify.app/) · [LinkedIn](https://linkedin.com/in/rsilveirafh) · [Lattes](http://lattes.cnpq.br/6028156427352678)

> **Disponível para novas oportunidades.** Busco vagas remotas como cientista de dados ou desenvolvedor em dados ambientais, ESG, biodiversidade ou pesquisa. Contato: rsilveirafh@gmail.com ou [LinkedIn](https://linkedin.com/in/rsilveirafh).

### Trabalho recente

Lidero o portfólio de desenvolvimento do time de inovação da [Seteg](https://www.setegce.com/), consultoria ambiental, onde meu contrato vai até novembro de 2026. O trabalho se divide em algumas frentes.

**Coleta de dados em campo.** Apps que substituem formulário de papel e planilha para biólogos em levantamentos de fauna e flora, de modo que o registro chegue estruturado em vez de ser redigitado semanas depois.

**Business intelligence.** Dashboards em Power BI e em R/Shiny para coordenação e diretoria, montados sobre dados operacionais que antes viviam em sistemas que não conversavam entre si.

**Conformidade ambiental e ESG.** Uma plataforma SaaS de gestão de conformidade, além de inventários de carbono pelo GHG Protocol.

**Analytics de energia.** Pipelines de análise sobre dados de geração hídrica, solar e eólica.

**Consolidação de plataforma.** Absorver sistemas internos avulsos em uma plataforma única. A parte instrutiva foi descobrir que vários módulos já tinham backend pronto e ninguém havia migrado, o que tornou o problema um caso de cutover e não de código.

Junto aos produtos, escrevi o manual de operação do time: como um requisito é escrito, como o git é usado, como os boards de projeto são mantidos e qual é o ciclo de vida da entrega, da demanda ao repasse. O ganho maior veio de colocar em ordem definida documentos que já existiam.

Antes disso, fui cientista de dados na Conciso TI por quatro anos e fiz consultoria ambiental por mais de uma década, por último como responsável técnico do monitoramento de tartarugas marinhas no Porto de Natal.

Em todos esses trabalhos eu procurei a mesma coisa: o que as pessoas repetiam à mão, para construir o sistema que faz aquilo uma vez só.

### Como eu trabalho

**Especificação antes de código.** O projeto começa como contrato escrito: briefing, pesquisa de domínio e requisitos mapeados um a um em fases MVP verticais, cada uma com critérios de sucesso explícitos. Nada é construído sem uma fase que seja dona daquilo.

**Agentes dentro de um pipeline.** Conduzo o Claude Code por skills próprias de planejamento, execução, verificação e revisão, para que a mesma disciplina valha se o código vem de mim ou de um agente. As que valem a pena compartilhar estão publicadas como plugins no meu catálogo [claude-plugins](https://github.com/rsilveirafh/claude-plugins).

**Memória com humano no circuito.** Um vault Obsidian onde entra o diário e saem propostas estruturadas. Reviso cada uma antes de ser gravada.

**CI verde não é evidência.** Duas das minhas versões subiram com checagem de tipos, testes e build passando, e bloqueadores esperando em produção. Abrir o produto no ar na mão passou a fazer parte da minha definição de pronto.

### Projetos em destaque

- **[tetrapoDNA](https://github.com/rsilveirafh/tetrapoDNA)**: quais anfíbios, répteis, aves e mamíferos do Brasil ainda não têm nenhuma sequência de DNA pública? [Painel](https://rsilveirafh.github.io/tetrapoDNA/) atualizado toda semana com BOLD e GenBank, com a opção de um pesquisador adotar uma espécie para sequenciar.
- **[banca-simulada](https://github.com/rsilveirafh/banca-simulada)**: plugin do Claude Code que revisa projetos de pesquisa como uma banca ou comitê avaliador faria, do TCC ao concurso docente. Aponta o trecho, a gravidade e a sugestão, sem reescrever.
- **[memoria-skills](https://github.com/rsilveirafh/memoria-skills)**: plugin do Claude Code que transforma um vault Markdown em memória com portão humano. O agente propõe, eu reviso, um comando separado aplica.
- **[carona-solidaria](https://github.com/rsilveirafh/carona-solidaria)**: caronas voluntárias para eleitores com dificuldade de locomoção no 2º turno de 2026, em Natal, Recife e João Pessoa. Saiu da ideia ao ar em quatro dias.
- **[rr-quant](https://github.com/rsilveirafh/rr-quant)**: dashboard quant pessoal com snapshot pré-mercado de 46 ativos, rodando sozinho a cada pregão.
- **[dash_ppbio](https://github.com/rsilveirafh/dash_ppbio)**: *Panoramas da Biodiversidade Brasileira*, dashboard do pós-doutorado no PPBio (2022).

**Contribuições em código aberto.** Atualização de pacotes da comunidade para as listas oficiais de 2026: um [pull request](https://github.com/paulobarros/amphiBR/pull/2) no [amphiBR](https://github.com/paulobarros/amphiBR) com a Lista de Anfíbios do Brasil 2026 e as categorias da Portaria MMA 1.704/2026, e uma [proposta](https://github.com/omarentiauspe/ReptiliaBR/issues/1) da mesma atualização no [ReptiliaBR](https://github.com/omarentiauspe/ReptiliaBR).

### Formação e pesquisa

Doutorado e mestrado em Zoologia pela UFPB, em herpetologia, filogenética e filogeografia, principalmente de serpentes. Depois, dois pós-doutorados: UNEMAT, de 2018 a 2019, em ecologia vegetal e traços funcionais, e UFRN junto ao PPBio, de 2022 a 2023, em biodiversidade e bioinformática. Licenciatura em Ciências Biológicas pela UEFS.

Dezesseis artigos em periódicos, entre eles dois na *Science*, de 2023 e 2024, e um na *Molecular Ecology*. Lista completa no [Lattes](http://lattes.cnpq.br/6028156427352678).

</details>

---

<sub>Os repositórios aqui são um recorte. Boa parte do que construí na Seteg é privada e ficou com a empresa. · The repositories here are a sample; most of what I built at Seteg is private to the company.</sub>
