# Case 4 — Maintaining Human Control Despite Technical Asymmetry

> **Portfolio confidentiality note:** This case is generalized from documented work in an ongoing proprietary AI-assisted research and software-development project. Project names, business purpose, architecture, datasets, implementation details, internal identifiers, and other sensitive information have been omitted or generalized. The human–AI interaction pattern, intervention, and methodological lesson described here are real.

## Situation

I am not a professional software engineer, yet I have overseen a long-running proprietary project that uses AI systems to perform substantial software-development, data-processing, research, systems-administration, and validation work.

In many individual implementation tasks, the AI systems possess significantly greater programming fluency than I do.

I therefore could not create meaningful human control by pretending to independently reproduce all of their technical expertise.

Instead, I developed a governance model in which the human controls the **epistemic and procedural envelope** around the technical work.

## Human control of specification

I retain authority over:

- the problem being solved;
- the intended outcome;
- authoritative source materials;
- prohibited actions;
- task boundaries;
- acceptance criteria; and
- the definition of success.

The AI may propose implementations, but it does not independently redefine the objective.

## Separation of AI roles

Different AI systems are assigned bounded roles.

One system may assist with:

- interpretation;
- source reconciliation;
- task construction;
- evidence review; and
- research reasoning.

Another may perform:

- software implementation;
- diagnostics;
- testing; or
- environment-specific changes.

Capability does not automatically imply authority.

An implementing agent does not gain authority to approve its own work simply because it can perform the implementation.

## Bounded execution

A recurring operating pattern is:

> bounded instruction → bounded action → evidence return → review → next authorization.

This limits the ability of an AI system to convert technical initiative into unreviewed project authority.

## Separation of implementation from acceptance

A particularly important project rule is that AI systems may:

- implement;
- test;
- analyze;
- validate;
- classify evidence; and
- recommend a disposition.

They may not convert those activities into final human acceptance.

Approval of material state changes remains a separate human act.

## Human control of validation

Rather than reviewing every generated line of code, I can require evidence such as:

- schema validation;
- exact-path verification;
- before-and-after state comparisons;
- cryptographic hashes;
- frozen-input checks;
- negative tests;
- independent reproduction;
- no-mutation confirmation; and
- explicit failure reporting.

This allows meaningful human supervision even when the AI's implementation skill exceeds the human supervisor's coding skill.

## A representative example

In one acceptance test, the experimental protocol permitted a particular action to occur only once.

An unexpected interface interaction accidentally caused the action to occur a second time.

The easy response would have been to retry until the desired result appeared.

Instead, I required the existing trial to be treated as methodologically invalid for that condition, preserved the valid results from unaffected trials, and authorized a separate bounded continuation.

The governing principle was that **the experiment had to preserve its protocol even when violating the protocol would have been operationally convenient**.

## Why I consider this important

This experience raises what I think is an increasingly important oversight question:

**What constitutes meaningful human control when the AI system has substantially greater implementation capability than the human supervising it?**

My experience suggests that human control need not depend entirely on superior implementation skill.

It can instead reside in control over:

- goals;
- authority;
- source provenance;
- constraints;
- validation requirements;
- escalation;
- acceptance; and
- permission to proceed.
