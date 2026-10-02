# Case 2 — When a Plausible Provenance Explanation Was Mistaken for Source Evidence

> **Portfolio confidentiality note:** This case is generalized from documented work in an ongoing proprietary AI-assisted research and software-development project. Project names, business purpose, architecture, datasets, implementation details, internal identifiers, and other sensitive information have been omitted or generalized. The human–AI interaction pattern, intervention, and methodological lesson described here are real.

## Situation

During a research investigation, an AI-assisted workflow was attempting to determine the origin of a derived dataset and the relationship between several upstream data structures.

One diagnostic process identified what appeared to be the relevant upstream producer. The explanation was technically coherent and fit the surrounding evidence well.

Further investigation showed that the identification was wrong.

In the same investigation, the AI initially interpreted the absence of a particular identifier as a hard technical blocker. Later analysis showed that the required relationship could legitimately be reconstructed from other authoritative fields and contracts.

The important problem was therefore not merely that an answer changed.

A **plausible derivative explanation had begun to acquire more evidentiary authority than its source justified**.

## Human intervention

Rather than allowing the most coherent explanation to become the project record, I required the investigation to return to primary evidence.

That included examining:

- authoritative schemas;
- actual producer logic;
- source ledgers;
- routing records;
- cryptographic or identity evidence where applicable;
- canonical data artifacts; and
- direct equivalence checks against independently produced outputs.

The initial explanation was treated as a hypothesis until the source chain could actually support it.

## Governance change

The resulting rule was that a derivative report or AI explanation is authoritative only for what it directly demonstrates.

Claims about:

- provenance;
- implementation behavior;
- source identity;
- dependency relationships; or
- causal origin

must remain interpretations until they are verified against the relevant primary source.

The workflow also increasingly separated:

- source evidence;
- derived interpretation;
- recommendation;
- human decision; and
- runtime evidence.

## Why I consider this important

Advanced models can generate explanations that are:

- technically sophisticated;
- internally coherent;
- highly consistent with surrounding evidence;

and nevertheless **not actually grounded in the authoritative source they appear to explain**.

That creates an evaluation question I find particularly important:

**Can a human user reliably distinguish a model's source-grounded conclusion from a coherent reconstruction that merely fits the available context?**
