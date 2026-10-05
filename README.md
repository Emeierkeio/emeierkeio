# Mirko Tritella

**I build AI tools that make public information easier to explore, understand and verify.**

I work on AI interfaces to official records and open government data. Every answer these systems give links back to its source. The work combines public data, information retrieval, knowledge graphs and language models.

[Website](https://emeierkeio.github.io/) · [LinkedIn](https://www.linkedin.com/in/mirko-tritella-4406361a3) · [ORCID](https://orcid.org/0009-0000-8611-8189) · [Publications](https://emeierkeio.github.io/#publications)

<p align="center">
  <a href="https://www.parliamentrag.it/"><img src="assets/card-parliamentrag.svg" width="200" height="132" alt="ParliamentRAG, research centre"></a>
  <a href="https://www.stenografo.it/"><img src="assets/card-stenografo.svg" width="200" height="132" alt="Stenografo, stenografo.it"></a>
  <a href="https://www.fascicoli.it/"><img src="assets/card-fascicoli.svg" width="200" height="132" alt="Fascicoli, fascicoli.it"></a>
  <a href="https://www.scranno.it/"><img src="assets/card-scranno.svg" width="200" height="132" alt="Scranno, scranno.it"></a>
</p>

## ParliamentRAG

A research centre on the official records of the Italian Parliament, started at the University of Milano-Bicocca. Its research appears at ISWC 2026, in the In-Use Track and in Posters & Demos.

The Italian Chamber of Deputies publishes every plenary debate and every roll-call vote as open data. That record answers most questions about what parliament does, but finding who said what means reading hundreds of pages. ParliamentRAG turns the record into a knowledge graph and builds answers that keep three guarantees:

1. **Every parliamentary group.** Majority and opposition both appear. When a group never spoke on the topic, the answer says so.
2. **Authoritative speakers.** An authority model ranks deputies on the topic by their speeches, acts, committee seats and roles.
3. **Exact quotes with official links.** Each quotation links to its passage in the stenographic record. A check drops any quote that does not match the source verbatim before you read it.

The data and the method that checks these guarantees are open. The applications built on top are separate products:

- **[Stenografo](https://www.stenografo.it/)** answers precise questions (how did a deputy vote, who chairs a committee) and links each sentence to its source.
- **[Fascicoli](https://www.fascicoli.it/)** builds one dossier per topic: what each group says and how it votes.
- **[Scranno](https://www.scranno.it/)** shows the Chamber in 3D, with every deputy in their real seat.

> 719 plenary sessions · 177k+ speech chunks · 36.7k parliamentary acts · 17.5k roll-call votes · 7M individual vote records  
> XIX Legislature, updated from official open data

**Stack:** RAG · knowledge graphs · RDF/SPARQL · hybrid retrieval · authority-aware retrieval · citation verification · MCP

[Research centre](https://www.parliamentrag.it/) · [ISWC demo](https://truthful-amazement-production.up.railway.app/) · [Research code](https://github.com/Emeierkeio/ParliamentRAG) · [Dataset](https://doi.org/10.5281/zenodo.21560331)

## Publications

**Who Speaks Matters: Authority-Aware Multi-View Retrieval-Augmented Generation over Italian Parliamentary Proceedings**  
Mirko Tritella, Riccardo Pozzi, Matteo Palmonari · ISWC 2026, In-Use Track · Springer, to appear  
[PDF](https://emeierkeio.github.io/papers/who-speaks-matters-iswc2026.pdf) · [Dataset](https://doi.org/10.5281/zenodo.21560332) · [ORKG](https://orkg.org/papers/R1909763)

**ParliamentRAG: An Authority-Aware Multi-View RAG System for Italian Parliamentary Proceedings**  
Mirko Tritella, Riccardo Pozzi, Matteo Palmonari · ISWC 2026, Posters & Demos · CEUR-WS, to appear  
[PDF](https://emeierkeio.github.io/papers/parliamentrag-demo-iswc2026.pdf) · [Live demo](https://truthful-amazement-production.up.railway.app/) · [Code](https://github.com/Emeierkeio/ParliamentRAG)

## Research

Public institutions publish more records than anyone can read. A language model can summarize them, but a summary without sources asks you to trust the model instead of the record. I build systems that show you what they retrieved, who said it, in which debate, and where to check it.

The questions I work on:

- How can an AI answer stay connected to its evidence?
- How should a system represent who is speaking, in which role and in which debate?
- How can knowledge graphs improve access to public records?
- How do you evaluate a system that summarizes public records, beyond answer accuracy?

**Topics:** retrieval-augmented generation · information retrieval · knowledge graphs · semantic web · LLM evaluation  
**Now exploring:** semantic axes for mapping political positions, and how parliamentary stances change over time.

## From open data to AI

I started with local public data. In Roseto degli Abruzzi, my home town, election results existed only as PDFs on the municipal website, so I extracted them and republished them as machine-readable data ([opendata-roseto](https://github.com/Emeierkeio/opendata-roseto)). During the pandemic I built a site that tracked the town's COVID-19 figures day by day ([roseto-covid](https://github.com/Emeierkeio/roseto-covid)). ParliamentRAG takes the same idea to the national parliament.

## Tools I work with

**AI and retrieval:** RAG · embeddings · LLMs · hybrid retrieval  
**Knowledge:** knowledge graphs · Neo4j · RDF · SPARQL  
**Engineering:** Python · FastAPI · Next.js · Docker · MCP

---

MSc Data Science, University of Milano-Bicocca · BSc Computer Science, University of Bologna  
Rome / Milan / Roseto degli Abruzzi · [mirkotritella1999@gmail.com](mailto:mirkotritella1999@gmail.com)
