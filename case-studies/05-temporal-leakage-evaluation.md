# Case 5 — Detecting Temporal Leakage in an Evaluation

> **Portfolio confidentiality note:** This case is generalized from documented work in an ongoing proprietary AI-assisted research and software-development project. Project names, business purpose, architecture, datasets, implementation details, internal identifiers, and other sensitive information have been omitted or generalized. The human–AI interaction pattern, intervention, and methodological lesson described here are real.

## Situation

A research benchmark compared a set of target cases against historical reference cases using multiple derived views of time-dependent data.

The initial evaluation machinery could incorporate some information that became available **after the decision point being evaluated**.

Historically, the data was real.

Methodologically, however, it was not yet available to the hypothetical decision-maker at the relevant moment.

If that information influenced similarity, ranking, or evaluation results, the benchmark would be using future information in an ostensibly causal comparison.

## Human insight

I recognized that the important distinction was not:

> Does this information exist somewhere in the historical dataset?

The relevant question was:

> Was this information legitimately available at the precise time the evaluated decision had to be made?

Those are not equivalent.

## Correction

The benchmark contract was revised so that every relevant feature had to satisfy an explicit per-case information-availability cutoff.

The rule was applied symmetrically to:

- evaluation cases; and
- historical reference cases.

Information arriving after the cutoff was treated as unavailable for that comparison.

Importantly, the later observations were **not deleted from the research corpus**.

They remained legitimate evidence for research questions in which that later information was actually available.

The correction therefore did not redefine the data itself.

It restricted the data according to the causal question being asked.

## Validation

The revised evaluation was implemented as a separately versioned benchmark rather than silently rewriting the earlier research history.

Subsequent qualification confirmed that a nontrivial number of data views previously eligible for comparison occurred on or after the causal boundary and were therefore correctly excluded under the revised contract.

Existing upstream source data and earlier research outputs were preserved.

## Why I consider this important

The case illustrates a broader distinction:

**Historical availability is not the same thing as causal availability.**

A dataset may legitimately contain information that an evaluated agent, model, or human would not have possessed at the decision point.

That creates direct parallels with AI evaluation problems involving:

- future-information leakage;
- benchmark contamination;
- privileged context;
- post hoc information;
- improper reference populations; and
- hidden information asymmetries.

The broader research question is:

**How should an evaluation distinguish information that exists in the evaluator's corpus from information legitimately available to the system being evaluated?**
