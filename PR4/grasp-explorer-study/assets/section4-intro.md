# Section 3: Knowledge Graph & Detail Panel

This section is about the **Graph Reasoning** page: the knowledge graph itself, and the detail panel that opens below it when you click a node. The graph covers 55 of the 56 grasp planning methods. We want your feedback on both surfaces from a robotics-comparison standpoint.

## What you're looking at

The graph shows methods, papers, techniques, authors, institutions, datasets, and hardware as nodes. Edges include *cites*, *outperforms*, *cited_by_external*, *uses_technique*, *evaluated_on*, *compared_against*, and more.

Two views you can toggle at the top:

- **Knowledge Graph** — observed relationships extracted directly from the papers (citations, claims, techniques, tables).
- **Predicted Relationships** — relationships an HGT (Heterogeneous Graph Transformer) model thinks should exist but no paper states yet (e.g. "these two methods are likely benchmarked head-to-head," "this paper probably uses this technique").

## The detail panel (below the graph)

Clicking any paper node opens a panel below the graph with:

- **Identity strip** — year, authors, institution.
- **Method spec card** — input modality, output pose, end-effector, scene, planning approach, training, datasets, hardware.
- **Compared-with rail** — outperforms / compared-against rows with the metric and value pulled from that paper's own benchmark tables when available.
- **Chip ribbons** — techniques and benchmarks.
- **Contributions / Limitations / Problem addressed** — extracted from the paper's text.
- **Citation timeline** — yearly stance-coded bars (builds-on, neutral, contrasts, cited externally).
- **Provenance footer** — observed vs predicted edge counts.

## What we're asking you to do

1. Click a paper you know well. Read the detail panel below the graph. Does it match what you would say about the method to a colleague?
2. Switch to **Predicted Relationships**. Pick one or two predicted edges. Do they look plausible? Would you investigate them?
3. Now click a paper you don't know. Does the panel give you enough to write the first paragraph of a related-work section?

(**Tip:** hold ⌘ or Ctrl and scroll to zoom the graph. Plain scroll moves the page.)

## Heads up: what we will ask

- Are the HGT predictions plausible, and would you act on them?
- Did the detail panel give you what a roboticist needs to compare two methods?
- What is missing from either surface?

Click **Next** to explore.
