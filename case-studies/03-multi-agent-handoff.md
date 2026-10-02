# Case 3 — Multi-Agent Diagnostic Handoff Produced the Wrong Remedy

> **Portfolio confidentiality note:** This case is generalized from documented work in an ongoing proprietary AI-assisted research and software-development project. Project names, business purpose, architecture, datasets, implementation details, internal identifiers, and other sensitive information have been omitted or generalized. The human–AI interaction pattern, intervention, and methodological lesson described here are real.

## Situation

In a multi-agent software-development workflow, an automated test failed because one process could not interact correctly with a protected coordination resource.

The diagnostic evidence passed through several layers:

1. a runtime failure;
2. an AI coding agent's diagnostic output;
3. interpretation by another AI system;
4. a proposed remediation;
5. reconciliation against the governing architecture; and
6. a corrected implementation.

The first proposed fix appeared reasonable. The immediate symptom was an access problem, so the proposed remedy was to relax the permissions protecting the affected resource.

That would probably have removed the immediate failure.

It would also have weakened an intentional security invariant.

Further examination showed that the real problem was not that the protected resource was too restrictive. The problem was that a **read-only participant was attempting to access the resource using write/create semantics**.

The correct solution was therefore to preserve the restrictive security contract and change the reader's behavior.

## Human intervention

I required the proposed fix to be reconciled against the governing technical contract rather than judging the remedy only by whether it would eliminate the test failure.

That exposed the mismatch between the symptom-level diagnosis and the architectural requirement.

## Governance change

The general rule became:

> A technical remedy does not become valid merely because it makes a failing test pass. It must also preserve the higher-level invariant that the test and architecture are intended to protect.

The workflow therefore distinguishes between:

- symptom elimination;
- causal correction; and
- architectural compliance.

## Why I consider this important

The failure occurred across a chain of otherwise reasonable transformations.

A low-level runtime problem became a diagnostic explanation, which became an apparently sensible recommendation. At each step the output remained plausible.

Yet the accumulated handoff produced the wrong system-level conclusion.

This suggests a broader research question:

**How often do AI coding systems or AI-agent chains solve the observable symptom of a problem while unintentionally violating a less-visible architectural or safety invariant?**
