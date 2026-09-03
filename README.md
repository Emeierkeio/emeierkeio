# Mirko Tritella

**I build AI tools that make public information easier to explore, understand and verify.**

I'm a researcher and engineer working on AI interfaces to official records and open government data, designed so that every answer can be traced back to its source. My work combines public data, information retrieval, knowledge graphs and language models to make institutional knowledge more accessible and verifiable.

**[Portfolio → emeierkeio.github.io](https://emeierkeio.github.io/)** · [GitHub](https://github.com/Emeierkeio) · [LinkedIn](https://www.linkedin.com/in/mirko-tritella-4406361a3) · [ORCID](https://orcid.org/0009-0000-8611-8189) · [Publications](https://emeierkeio.github.io/#publications)

## What I work on

- **Public information** — making large collections of institutional and public records easier to explore.
- **Verifiable AI** — building systems where generated answers stay connected to evidence and sources.
- **Knowledge representation** — using knowledge graphs and semantic relationships to preserve context: who said what, in which role, in which debate.
- **Digital democracy** — exploring how better interfaces to public information can support transparency and informed participation.

## Featured — ParliamentRAG

An AI interface for exploring the Italian Parliament through its official records.

The Italian Chamber of Deputies publishes every plenary debate and every roll-call vote as open data. In principle, that record can answer almost any question about what parliament does; in practice, finding who said what means reading hundreds of pages. ParliamentRAG lets you ask in plain language: it retrieves the relevant speeches and votes, writes an answer that covers every parliamentary group, majority and opposition alike, and links each quotation back to the exact passage in the official record. Quotes that cannot be verified verbatim against their source are removed before the answer is shown.

The principle behind it: **the answer should never be detached from the official record.**

> 705 plenary sessions · 174k+ speech chunks · 17.3k roll-call votes · 6.9M individual vote records
> XIX Legislature, updated continuously from official open data

Under the hood: RAG · knowledge graphs · RDF/SPARQL · hybrid retrieval · authority-aware retrieval · citation verification · MCP

[Live system](https://www.parliamentrag.it/) · [Source code](https://github.com/Emeierkeio/ParliamentRAG) · [Research paper](https://emeierkeio.github.io/papers/who-speaks-matters-iswc2026.pdf) · [Demo paper](https://emeierkeio.github.io/papers/parliamentrag-demo-iswc2026.pdf) · [Dataset](https://doi.org/10.5281/zenodo.21560331)

## Why this matters

Public institutions produce enormous amounts of digital information. AI can make that information easier to navigate, but generated answers should not become detached from the evidence behind them: a system that summarizes the public record without showing its sources replaces one opacity with another. I'm interested in building systems where retrieval, context and provenance remain visible parts of the interaction.

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

**Who Speaks Matters: Authority-Aware Multi-View Retrieval-Augmented Generation over Italian Parliamentary Proceedings** — the research behind ParliamentRAG.
Mirko Tritella, Riccardo Pozzi, Matteo Palmonari · ISWC 2026, In-Use Track · Springer, to appear
[PDF](https://emeierkeio.github.io/papers/who-speaks-matters-iswc2026.pdf) · [Project](https://www.parliamentrag.it/) · [Dataset](https://doi.org/10.5281/zenodo.21560332) · [ORKG](https://orkg.org/papers/R1909763)

**ParliamentRAG: An Authority-Aware Multi-View RAG System for Italian Parliamentary Proceedings**
Mirko Tritella, Riccardo Pozzi, Matteo Palmonari · ISWC 2026, Posters & Demos · CEUR-WS, to appear
[PDF](https://emeierkeio.github.io/papers/parliamentrag-demo-iswc2026.pdf) · [Live demo](https://www.parliamentrag.it/) · [Code](https://github.com/Emeierkeio/ParliamentRAG)

## Tools I work with

**AI / retrieval:** RAG · embeddings · LLMs · hybrid retrieval
**Knowledge:** knowledge graphs · Neo4j · RDF · SPARQL
**Engineering:** Python · FastAPI · Next.js · Docker · MCP

---

MSc Data Science, University of Milano-Bicocca · BSc Computer Science, University of Bologna
Rome / Milan / Roseto degli Abruzzi · [mirkotritella1999@gmail.com](mailto:mirkotritella1999@gmail.com)

**Explore the work → [emeierkeio.github.io](https://emeierkeio.github.io/)**
