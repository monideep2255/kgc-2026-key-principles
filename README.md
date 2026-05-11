# KGC 2026: key principles

Ten foundational principles for trustworthy AI with knowledge graphs, synthesized from the [Knowledge Graph Conference 2026](https://www.knowledgegraph.tech/) (May 04-08, 2026).

Live page: https://monideep2255.github.io/kgc-2026-key-principles/

## What this is

A single-page synthesis of ten foundational principles for trustworthy AI with knowledge graphs, drawn from across 20 sessions at KGC 2026. Color-coded by theme (technology, organization, people) with an interconnection diagram showing how the principles relate.

## What this is not

Not a transcript or a session-by-session recap. Speaker quotes, slides, and session content belong to the speakers and the conference. The principles here are abstractions in my own words.

## Sources

The 20 sessions I attended at KGC 2026 that fed into the synthesis. Titles match the official session listings on the conference site.

| Day | Session | Speaker(s) | Affiliation |
|-----|---------|-----------|-------------|
| May 04 | Designing Agent-Driven GraphRAG Systems with GNNs for High-Trust Healthcare AI | Giuseppe Futia | CSI Piemonte (Italy) |
| May 04 | RDFox Semantic Reasoning Workshop Overview | Diana Marks | Oxford Semantic Technologies |
| May 04 | Vector Search + Knowledge Graphs in Oracle AI Database. Using SQL. | Melli Annamalai, Matthew Perry, Shreya Pandey | Oracle |
| May 04 | AI Agents and Semantic Reasoning Workshop | Sean, Nafi, Don Simpson, Hal Cooper | AWS, Amazon Neptune |
| May 05 | Semantic RAG in Practice: Building Accurate, Enterprise-Grade GenAI with Knowledge Graphs and Multi-Model Data | Jim Morris, Drew Wanczowski | Progress Software |
| May 05 | Semantic Data Products in Practice: Hands-on with DPROD and Enterprise Information Architecture | Thomas Kaminski, Tony Seale | Metaphacts, The Knowledge Graph Guys |
| May 05 | Building Knowledge Maps: Evidence-First Knowledge Graphs for Unstructured Data | Weidong Yang | Kineviz, Inc. |
| May 06 | Front Runner's Guide to Scaling AI and Role of Semantic Layer | Richard Weng | Accenture |
| May 06 | Ask-A-Graph: A Principled Approach to Natural Language Graph Querying Through LLM-Orchestrated Entity Resolution and Schema-Aware Cypher Generation | Ryan Chandler | AbbVie |
| May 06 | Engineering the Enterprise Semantic Layer | Thomas Kaminski | Metaphacts |
| May 06 | Ontologists Taking Their Own Medicine: Personal Graph Building Journey | Casey | (independent) |
| May 06 | Bridging Knowledge Graphs and Data Management: How Ontologists and CDOs Win Together | Charles Ivie | Ortecha |
| May 06 | Lessons Learned from 25 Years in Semantics: Building the Cognitive Backbone of the Enterprise | Evren Sirin | Stardog |
| May 07 | The Spatial Web as a Knowledge Graph: Modeling Reality, Behavior, and Trust | Stephane Fellah | Geoknoesis LLC |
| May 07 | Grounding LLMs in Domain Knowledge: Hybrid KG Architectures for Reliable Industrial Recommendations | Anahita Pakiman | Amazon |
| May 07 | Ontology Generation with LLMs: Evaluation Framework and Quality Metrics | Anahita Pakiman, Nikos Trokanas | Amazon, Scania |
| May 07 | From Data to Decisions: How Marketer.com Used Knowledge Graphs and Reasoning to Build Trustworthy AI | Peter Crocker, Krisztián Szabó | Oxford Semantic Technologies, Marketer.com |
| May 07 | Migrating from Hierarchies to a Graph: An Enterprise Case Study | John Tulinsky, Bram Wessel | Factor |
| May 07 | The Context Layer: Knowledge Graphs' Second Act | Prukalpa Sankar | Atlan |
| May 08 | KGC 2026 Tools and Demos Track | Multiple presenters (12 tool demos) | Process Tempo, Triven, Graph Research Labs, Stardog, Northeastern, Lettria, Tom Sawyer, and others |

## How the key principles sheet was created

I attended 20 sessions at KGC 2026 over five days. For each session I had a mix of written notes (typed during or shortly after) and voice memos (recorded between sessions). I wanted to compress that raw material into something I could use in five minutes. Here is the process I ran:

1. AI transcribed my voice memos into text and combined them with my typed notes per session.
2. For each session, I added the official KGC session abstract (publicly published on the conference site) at the top of the notes file as framing context.
3. I ran each combined notes file through a structured first-principles prompt (below) to produce a plain-language summary and a candidate set of session-level principles.
4. I reviewed each summary against my original notes and dropped or rewrote anything not supported by what I actually heard.
5. AI extracted themes across all 20 standardized session files.
6. I cross-checked the themes against my notes again, dropped weak ones, and kept what showed up across multiple sessions or felt most actionable for me.
7. AI drafted a candidate relationship diagram showing how the principles connect. I refined the edges.
8. I selected the final 10 principles based on cross-session frequency, novelty, and what felt most useful for my day-to-day work.

Human-AI division: AI did transcription, summarization, first-pass theme extraction, and diagram drafting. I owned source selection, theme validation, principle curation, editorial voice, and final review.

### The prompt I used

I ran this prompt against each individual source. It biases the output toward first-principles breakdowns and plain language.

```
Deep-dive and summarize the [source-type] I am currently viewing.
Use first principles thinking—break down the key ideas into clear, simple
explanations as if teaching someone new to the topic. Use step-by-step
reasoning and, where helpful, simple examples or analogies.

Focus on:
– The main point and central argument
– How and why things work as described
– Any important background or context
– Actionable takeaways or implications

Write in plain language, assume no prior knowledge, and avoid jargon. Be as
thorough and accessible as possible.

Also suggest a name for the thread that you create and have it right at the
start of the thread.
```

### About this workflow

This workflow works best for me because I learn by writing summaries and connecting ideas across sources. It may not match how you learn. If you want to use it, treat it as inspiration and customize freely. Two axes worth tuning:

- The prompt: It favors first-principles breakdowns and plain-language teaching. Yours might emphasize examples, analogies, comparisons, story-based framing, or step-by-step problem solving. Swap the prompt for what fits your learning style.
- The editorial step: I picked 10 principles. You might want 5, or 25, or no synthesis at all (just summaries per source). Adjust to judgment and taste.

Treat both the workflow and the prompt as starting points, not templates.

## License

Released under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). You can share and adapt with attribution.
