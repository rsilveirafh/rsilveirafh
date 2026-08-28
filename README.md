# Ricardo Silveira

Zoologist by training, now working as a data and software engineer. For a decade I asked questions of biological data: phylogeography, herpetology, population genomics. Today I build the systems that turn environmental and field data into something a team can act on.

📍 Natal, RN, Brazil · he/him
[Website](https://rsilveirafh.netlify.app/) · [LinkedIn](https://linkedin.com/in/rsilveirafh) · [Lattes CV](http://lattes.cnpq.br/6028156427352678)

---

## What I do

Innovation Analyst at [Seteg](https://www.setegce.com/), an environmental consultancy, where I lead the development portfolio of a small team. The work groups into a few fronts.

**Field data collection.** Apps that replace paper forms and spreadsheets for biologists running fauna and flora surveys, so records arrive structured instead of being retyped weeks later.

**Business intelligence.** Dashboards in Power BI and in R/Shiny for coordinators and directors, built over operational data that used to live in systems that did not talk to each other.

**Environmental compliance and ESG.** A SaaS platform for compliance management, plus carbon inventories following the GHG Protocol.

**Energy analytics.** Analysis pipelines over hydro, solar and wind generation data.

**Platform consolidation.** Folding standalone internal systems into one platform. The instructive part was discovering that several modules already had working backends and nobody had migrated, which made it a cutover problem rather than a coding one.

Alongside the products I wrote the team's operating manual: how a requirement gets written, how git is used, how project boards are kept, and what the delivery lifecycle looks like from demand to handover. Most of the gain there came from putting documents that already existed into a defined order.

The thread running through all of it is the same. Someone is doing by hand, twice, something a system should be doing once.

---

## How I work

**Spec before code.** A project starts as a written contract: brief, domain research, then requirements mapped one to one onto vertical MVP phases, each with explicit success criteria. Nothing gets built without a phase that owns it.

**Agents inside a pipeline.** I drive Claude Code through custom skills I wrote for planning, execution, verification and review, so the same discipline applies whether the code comes from me or from an agent.

**Memory with a human in the loop.** An Obsidian vault where a daily journal goes in and structured proposals come out. I review every one before it is written.

**Green CI is not evidence.** Two of my releases shipped with type checks, tests and build all passing, and blockers waiting in production. Opening the live product by hand is now part of my definition of done.

**Backtests leak.** A 55% hit rate in one of my own models fell to 48.5% once the data clock was respected.

---

## Selected work

| Project | What it is | Stack |
|---|---|---|
| **[rr-quant](https://github.com/rsilveirafh/rr-quant)** | Personal quant dashboard. Pulls a 46-asset pre-market snapshot covering indices, commodities, FX, rates and volatility, then layers on regime and correlation reads, a logistic-regression scoreboard for the Ibovespa, and a Smart Money Concepts view over OHLC. Runs itself every trading session. | Python, yfinance, Vercel |
| **[dash_ppbio](https://github.com/rsilveirafh/dash_ppbio)** | *Panoramas da Biodiversidade Brasileira*, an interactive dashboard over occurrence and genetic data for PPBio, Brazil's Biodiversity Research Program. Built during my post-doctorate there in 2022. | R, flexdashboard, highcharter, plotly |
| **[postdoc_ppbio](https://github.com/rsilveirafh/postdoc_ppbio)** | Analysis scripts behind the same post-doctorate: species list assembly, taxonomic resolution through taxize, and the reporting pipeline. | R, taxize, Quarto |
| **[covid19_r](https://github.com/rsilveirafh/covid19_r)** | Shiny dashboard tracking COVID-19 in Brazil, 2020. Archived, the hosted app is no longer running. | R, Shiny |

🔒 = private repo, happy to walk through it.

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

### O que eu faço

Analista de Inovação na [Seteg](https://www.setegce.com/), consultoria ambiental, onde lidero o portfólio de desenvolvimento de um time pequeno. O trabalho se agrupa em algumas frentes.

**Coleta de dados em campo.** Apps que substituem formulário de papel e planilha para biólogos em levantamentos de fauna e flora, de modo que o registro chegue estruturado em vez de ser redigitado semanas depois.

**Business intelligence.** Dashboards em Power BI e em R/Shiny para coordenação e diretoria, montados sobre dados operacionais que antes viviam em sistemas que não conversavam entre si.

**Conformidade ambiental e ESG.** Uma plataforma SaaS de gestão de conformidade, além de inventários de carbono pelo GHG Protocol.

**Analytics de energia.** Pipelines de análise sobre dados de geração hídrica, solar e eólica.

**Consolidação de plataforma.** Absorver sistemas internos avulsos em uma plataforma única. A parte instrutiva foi descobrir que vários módulos já tinham backend pronto e ninguém havia migrado, o que tornou o problema um caso de cutover e não de código.

Junto aos produtos, escrevi o manual de operação do time: como um requisito é escrito, como o git é usado, como os boards de projeto são mantidos e qual é o ciclo de vida da entrega, da demanda ao repasse. O ganho maior veio de colocar em ordem definida documentos que já existiam.

O fio que atravessa tudo isso é o mesmo. Alguém está fazendo à mão, duas vezes, algo que um sistema deveria fazer uma vez.

### Como eu trabalho

**Especificação antes de código.** O projeto começa como contrato escrito: briefing, pesquisa de domínio e requisitos mapeados um a um em fases MVP verticais, cada uma com critérios de sucesso explícitos. Nada é construído sem uma fase que seja dona daquilo.

**Agentes dentro de um pipeline.** Conduzo o Claude Code por skills próprias de planejamento, execução, verificação e revisão, para que a mesma disciplina valha se o código vem de mim ou de um agente.

**Memória com humano no circuito.** Um vault Obsidian onde entra o diário e saem propostas estruturadas. Reviso cada uma antes de ser gravada.

**CI verde não é evidência.** Duas das minhas versões subiram com checagem de tipos, testes e build passando, e bloqueadores esperando em produção. Abrir o produto no ar na mão passou a fazer parte da minha definição de pronto.

**Backtest vaza.** Uma taxa de acerto de 55% em um modelo meu caiu para 48,5% quando o relógio dos dados foi respeitado.

### Formação e pesquisa

Doutorado e mestrado em Zoologia pela UFPB, em herpetologia, filogenética e filogeografia, principalmente de serpentes. Depois, dois pós-doutorados: UNEMAT, de 2018 a 2019, em ecologia vegetal e traços funcionais, e UFRN junto ao PPBio, de 2022 a 2023, em biodiversidade e bioinformática. Licenciatura em Ciências Biológicas pela UEFS.

Dezesseis artigos em periódicos, entre eles dois na *Science*, de 2023 e 2024, e um na *Molecular Ecology*. Lista completa no [Lattes](http://lattes.cnpq.br/6028156427352678).

</details>

---

<sub>Os repositórios aqui são um recorte. Boa parte do que construo é privada ou vive na organização em que trabalho.</sub>
