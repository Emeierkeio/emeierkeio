# Mirko Tritella

**I build AI tools that make public information easier to explore, understand and verify.**

I'm a researcher and engineer working on AI interfaces to official records and open government data, designed so that every answer can be traced back to its source. My work combines public data, information retrieval, knowledge graphs and language models to make institutional knowledge more accessible and verifiable.

[Website](https://emeierkeio.github.io/) · [GitHub](https://github.com/Emeierkeio) · [LinkedIn](https://www.linkedin.com/in/mirko-tritella-4406361a3) · [ORCID](https://orcid.org/0009-0000-8611-8189) · [Publications](https://emeierkeio.github.io/#publications)

<table>
  <tr>
    <td align="center" width="25%"><a href="https://www.parliamentrag.it/"><img src="assets/parliamentrag.svg" height="56" alt="ParliamentRAG"><br><b>ParliamentRAG</b></a><br><sub>research centre</sub></td>
    <td align="center" width="25%"><a href="https://www.stenografo.it/"><img src="assets/stenografo.svg" height="44" alt="Stenografo"><br><b>Stenografo</b></a><br><sub>stenografo.it</sub></td>
    <td align="center" width="25%"><a href="https://www.fascicoli.it/"><img src="assets/fascicoli.svg" height="44" alt="Fascicoli"><br><b>Fascicoli</b></a><br><sub>fascicoli.it</sub></td>
    <td align="center" width="25%"><a href="https://www.scranno.it/"><img src="assets/scranno.svg" height="44" alt="Scranno"><br><b>Scranno</b></a><br><sub>scranno.it</sub></td>
  </tr>
</table>

## What I work on

- **Public information:** making large collections of institutional and public records easier to explore.
- **Verifiable AI:** building systems where generated answers stay connected to evidence and sources.
- **Knowledge representation:** using knowledge graphs and semantic relationships to preserve context: who said what, in which role, in which debate.
- **Digital democracy:** exploring how better interfaces to public information can support transparency and informed participation.


## ParliamentRAG

Research centre on the official records of the Italian Parliament, started at the University of Milano-Bicocca. The research behind it appears at ISWC 2026 (In-Use Track and Posters & Demos).

The Italian Chamber of Deputies publishes every plenary debate and every roll-call vote as open data. That record can answer most questions about what parliament does, but finding who said what means reading hundreds of pages. ParliamentRAG turns the record into a knowledge graph and builds answers that keep three guarantees:

1. **Every parliamentary group.** Majority and opposition both appear; when a group never spoke on the topic, the answer says so.
2. **Authoritative speakers.** An authority model ranks deputies on the topic by their speeches, acts, committee seats and roles.
3. **Exact quotes with official links.** Each quotation links to its passage in the stenographic record. A check drops any quote that does not match the source verbatim before you read it.

The data and the method that checks these guarantees are open. The applications built on top are separate products.

> 719 plenary sessions · 177k+ speech chunks · 36.7k parliamentary acts · 17.5k roll-call votes · 7M individual vote records
> XIX Legislature, updated from official open data

### Three systems on the same data

| | System | The question it answers |
|---|---|---|
| <img src="assets/stenografo.svg" height="20" alt=""> | **[Stenografo](https://www.stenografo.it/)** | How did a deputy vote? Who chairs a committee? Precise answers, each sentence linked to its source. |
| <img src="assets/fascicoli.svg" height="20" alt=""> | **[Fascicoli](https://www.fascicoli.it/)** | What does each group say about a topic, and how does it vote? One dossier per topic. |
| <img src="assets/scranno.svg" height="20" alt=""> | **[Scranno](https://www.scranno.it/)** | Who sits where? The Chamber in 3D, every deputy in their real seat. |

Under the hood: RAG · knowledge graphs · RDF/SPARQL · hybrid retrieval · authority-aware retrieval · citation verification · MCP

[Research centre](https://www.parliamentrag.it/) · [ISWC demo](https://truthful-amazement-production.up.railway.app/) · [Research code](https://github.com/Emeierkeio/ParliamentRAG) · [Research paper](https://emeierkeio.github.io/papers/who-speaks-matters-iswc2026.pdf) · [Demo paper](https://emeierkeio.github.io/papers/parliamentrag-demo-iswc2026.pdf) · [Dataset](https://doi.org/10.5281/zenodo.21560331)

## Why this matters

Public institutions publish more records than anyone can read. A language model can summarize them, but a summary without sources asks you to trust the model instead of the record. I build systems that show you what they retrieved, who said it, in which debate, and where to check it.

The question driving this work: *how can AI make complex public information easier to understand without making it harder to verify?*

## From open data to AI

My work started with local public data. In Roseto degli Abruzzi, my home town, election results existed only as PDFs on the municipal website, so I extracted and republished them as machine-readable data ([opendata-roseto](https://github.com/Emeierkeio/opendata-roseto)); during the pandemic I built a site tracking the town's COVID-19 statistics day by day ([roseto-covid](https://github.com/Emeierkeio/roseto-covid)). ParliamentRAG asks the same question at national scale: how can public information become easier to access and use?

## Research

- How can AI answers remain connected to evidence?
- How can knowledge graphs improve access to public information?
- How should a system represent who is speaking, and in what context?
- How should we evaluate AI systems that summarize public records, beyond simple answer accuracy?

Topics: retrieval-augmented generation · information retrieval · knowledge graphs · semantic web · LLM evaluation. Currently exploring semantic axes for political-position mapping and how parliamentary stances evolve over time.

## Publications

**Who Speaks Matters: Authority-Aware Multi-View Retrieval-Augmented Generation over Italian Parliamentary Proceedings**  
The research behind ParliamentRAG.  
Mirko Tritella, Riccardo Pozzi, Matteo Palmonari · ISWC 2026, In-Use Track · Springer, to appear  
[PDF](https://emeierkeio.github.io/papers/who-speaks-matters-iswc2026.pdf) · [Project](https://www.parliamentrag.it/) · [Dataset](https://doi.org/10.5281/zenodo.21560332) · [ORKG](https://orkg.org/papers/R1909763)

**ParliamentRAG: An Authority-Aware Multi-View RAG System for Italian Parliamentary Proceedings**  
Mirko Tritella, Riccardo Pozzi, Matteo Palmonari · ISWC 2026, Posters & Demos · CEUR-WS, to appear  
[PDF](https://emeierkeio.github.io/papers/parliamentrag-demo-iswc2026.pdf) · [Live demo](https://truthful-amazement-production.up.railway.app/) · [Code](https://github.com/Emeierkeio/ParliamentRAG)

## Tools I work with

**AI / retrieval:** RAG · embeddings · LLMs · hybrid retrieval  
**Knowledge:** knowledge graphs · Neo4j · RDF · SPARQL  
**Engineering:** Python · FastAPI · Next.js · Docker · MCP

---

MSc Data Science, University of Milano-Bicocca · BSc Computer Science, University of Bologna  
Rome / Milan / Roseto degli Abruzzi · [mirkotritella1999@gmail.com](mailto:mirkotritella1999@gmail.com)

[Website](https://emeierkeio.github.io/)
