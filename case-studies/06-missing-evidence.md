# Case 6 — Treating Missing Evidence as Missing Rather Than Inventing It

> **Portfolio confidentiality note:** This case is generalized from documented work in an ongoing proprietary AI-assisted research and software-development project. Project names, business purpose, architecture, datasets, implementation details, internal identifiers, and other sensitive information have been omitted or generalized. The human–AI interaction pattern, intervention, and methodological lesson described here are real.

## Situation

In a later sequence-analysis experiment, the underlying observations occurred at irregular intervals. Some expected time points had no observation.

Several technically convenient approaches were available:

- interpolate the missing periods;
- fill absent values;
- compress observed rows into an apparently continuous sequence; or
- assign an arbitrary penalty to missing intervals.

Each would have simplified the analysis.

Each would also have changed the epistemic meaning of the source data.

## Human intervention

I required the analysis to preserve the distinction between:

> an observation whose value is known;

and

> a time period for which no observation exists.

Missing evidence was therefore not treated as zero-valued evidence and was not synthetically reconstructed merely to make the sequence easier to process.

The original time coordinate remained authoritative, calculations operated on actual observations, and the burden created by gaps remained visible as diagnostic information.

## Why I consider this important

This case reflects a recurring principle in my work with AI-assisted research:

> **Absence of evidence should not silently become fabricated evidence merely because the fabricated representation is computationally convenient.**

That suggests another general evaluation question:

**When AI systems encounter incomplete evidence, how often do they preserve uncertainty versus silently regularizing the problem into something easier to reason about?**
