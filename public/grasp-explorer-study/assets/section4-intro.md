# Section 3: Knowledge Graph & Knowledge Base

This section covers two connected pages: the **Graph Reasoning** page (knowledge graph) and the **Knowledge Base** page (paper chunks). Both help you dig deeper into how methods relate to each other and what the papers actually say.

Note: The knowledge graph currently covers **34 of the 56 methods** (those with available papers). This is a work in progress — your feedback will help us prioritize what to build next.

## Graph Reasoning (Knowledge Graph)

The **Graph Reasoning** tab shows a structured knowledge graph built from the 34 ingested papers. Nodes represent methods, papers, techniques, authors, and hardware; edges represent relationships like *cites*, *uses_backbone*, *trained_on*, *uses_architecture*, and *semantically_similar*.

- **Subgraph exploration**: Click a method or paper to see its local neighborhood — what it cites, what backbone it uses, what techniques it shares with other methods
- **Predicted links**: An HGT (Heterogeneous Graph Transformer) model predicts relationships the papers don't explicitly state — potential connections between methods. We'd like your opinion on whether these are plausible.
- **Filters**: Toggle edge types and node types to focus on specific relationships

## Knowledge Base (Paper Chunks)

The **Knowledge Base** tab shows the 34 papers broken into searchable text passages (**chunks**), tagged by content type (*How it works*, *Implementation*, *Results*) and extraction level (*Overview*, *Section*, *Detail*).

- The **embedding scatter** shows chunks as dots — similar topics cluster together across papers
- Click a **paper chip** to highlight its chunks
- If you ran a query, relevant papers are highlighted automatically

## What to explore

1. Go to **Graph Reasoning** first — click a method node, explore its connections, check predicted links
2. Then visit **Knowledge Base** — browse chunk passages, try content type filters
3. Think about: do the graph relationships match your domain knowledge? Are the predicted links plausible? What's missing?

## Heads up: what we will ask after you explore

- Did the knowledge graph reveal relationships you didn't already know?
- Were the predicted links plausible or surprising?
- What relationship types or features would you want to see that aren't there yet?
- Were the text passages in the Knowledge Base readable and meaningful?

## Think aloud

Please describe what you discover in the graph, whether the connections make sense for your domain, and what you'd want us to add.

Click **Next** to explore the Knowledge Graph and Knowledge Base.
