# Matthew Miscisin — AI Portfolio

## Prompt Engineering · AI Interaction Design · Model Evaluation · Human–AI Workflow Design

Welcome to my AI portfolio.

This repository contains selected examples of my work with advanced AI systems, with an emphasis on **prompt engineering, long-context collaboration, model behavior, human oversight, multi-agent workflows, evidence provenance, and evaluation design**.

My background is unconventional. I do not come from a traditional computer-science or machine-learning career path. My experience has developed through sustained, practical work with advanced language models and AI coding agents on a complex proprietary research and software-development project.

That work has required me to learn how to translate human objectives into precise AI instructions, identify subtle model failure modes, manage long-running AI-assisted workflows, coordinate multiple AI agents, and preserve meaningful human control even when the AI system has greater implementation fluency than I do.

This portfolio presents selected examples of that work in a generalized form.

---

## What This Portfolio Demonstrates

My work with AI focuses less on finding clever wording and more on **designing reliable interaction systems**.

I approach prompt engineering as a form of specification engineering.

That means defining:

- what the model is being asked to accomplish;
- which information is authoritative;
- what assumptions are permitted;
- what actions are allowed or prohibited;
- what decisions belong to the AI and what decisions remain with the human;
- what evidence must be returned;
- what constitutes success or failure;
- how ambiguity should be handled; and
- how the resulting work can be validated.

My particular areas of interest include:

- Prompt architecture
- Complex instruction design
- Long-context AI collaboration
- AI model behavior
- Human–AI oversight
- Multi-agent orchestration
- Source provenance
- Epistemic reliability
- Evaluation design
- AI workflow governance
- Model failure analysis
- Human-in-the-loop systems

---

## Selected Case Studies

The case studies in this repository are generalized from documented work within an ongoing proprietary project.

Specific project names, datasets, internal architecture, filenames, business objectives, and implementation details have been omitted or generalized to protect confidential information.

The underlying human–AI interaction patterns are real.

### 1. Authority Drift in Long-Context AI Collaboration

A model retained a true operational restriction but gradually lost the restriction's scope, eventually treating a temporary condition as though it were a permanent system requirement.

The case examines:

- long-context semantic drift;
- temporary versus permanent constraints;
- instruction hierarchy;
- authority preservation; and
- mechanisms for preventing repeated statements from becoming unintended policy.

**Core question:**  
How reliably can long-context AI systems preserve the scope, authority, and temporal status of facts over extended collaboration?

---

### 2. Provenance vs. Plausible Reconstruction

An AI-assisted workflow produced a technically coherent explanation for the origin of certain data and system behavior.

The explanation fit the surrounding evidence but was not adequately supported by the authoritative source.

The case examines:

- source provenance;
- evidence versus interpretation;
- model-generated reconstruction;
- primary-source validation; and
- the risk of plausible explanations becoming accepted as facts.

**Core question:**  
Can a human reliably distinguish between a conclusion grounded in source evidence and a reconstruction that merely fits the available context?

---

### 3. Multi-Agent Diagnostic Handoff

A runtime failure passed through several layers of AI-assisted diagnosis and interpretation.

The proposed fix would likely have eliminated the immediate error, but it also would have weakened a higher-level architectural safeguard.

The case examines:

- multi-agent handoffs;
- symptom-level versus causal reasoning;
- architectural invariants;
- AI-generated remediation; and
- human review of technically plausible fixes.

**Core question:**  
How often do AI-assisted technical workflows solve the visible symptom of a problem while unintentionally violating a less-visible system requirement?

---

### 4. Human Control Despite Technical Asymmetry

This case examines how a non-programmer can maintain meaningful control over AI-generated technical work even when the AI system possesses substantially greater implementation fluency.

The workflow relies on human control over:

- objectives;
- scope;
- source authority;
- validation requirements;
- action boundaries;
- escalation;
- acceptance criteria; and
- authorization to proceed.

The AI may perform complex technical work, but technical capability does not automatically grant decision authority.

**Core question:**  
What constitutes meaningful human oversight when the AI has greater implementation capability than the human supervising it?

---

### 5. Temporal Leakage in Evaluation Design

A research benchmark contained historically valid information that was not actually available at the decision point being evaluated.

Allowing that information into the comparison would have created a subtle form of future-information leakage.

The evaluation was revised to distinguish:

> information that exists in the historical corpus

from:

> information legitimately available to the evaluated decision-maker at that moment.

The case examines:

- causal validity;
- temporal leakage;
- benchmark integrity;
- information availability;
- reference-population symmetry; and
- versioned experimental correction.

**Core question:**  
How should an evaluation distinguish between information available to the evaluator and information legitimately available to the system being evaluated?

---

### 6. Missing Evidence Is Still Missing

A sequence-analysis problem contained irregular observations and missing time periods.

Several computationally convenient approaches could have interpolated, filled, compressed, or otherwise regularized the missing evidence.

Instead, the analysis preserved the distinction between:

- an observation whose value is known; and
- a period for which no observation exists.

The case examines:

- missing data;
- epistemic integrity;
- synthetic reconstruction;
- AI-assisted research methodology; and
- computational convenience versus evidentiary meaning.

**Core question:**  
When evidence is incomplete, how reliably do AI systems preserve uncertainty rather than silently reconstructing a more convenient problem?

---

## My Prompt Engineering Approach

I generally use the following process when designing AI instructions:

1. **Define the intended outcome**
2. **Identify authoritative sources**
3. **Separate facts from assumptions**
4. **Define the AI system's role**
5. **Specify prohibited actions**
6. **Establish task boundaries**
7. **Define required outputs**
8. **Require evidence of completion**
9. **Define success and failure states**
10. **Specify ambiguity and escalation behavior**
11. **Evaluate the actual model response**
12. **Revise the prompt based on the failure mechanism**

I am particularly interested in prompts that must remain reliable across:

- long conversations;
- multiple AI agents;
- changing project states;
- conflicting evidence;
- tool use;
- high-autonomy tasks; and
- human approval boundaries.

---

## Multi-Agent AI Workflows

A substantial part of my experience involves coordinating different AI systems or agents with different responsibilities.

A typical workflow may involve:

1. a human defining the objective;
2. one AI system analyzing the problem;
3. another AI agent implementing technical work;
4. evidence being returned;
5. a separate review of the evidence;
6. human authorization before the next material action.

A core principle of my workflow is:

> **Capability does not automatically confer authority.**

An AI system may be capable of implementing, testing, analyzing, or recommending a result without being authorized to approve its own work.

---

## Evidence and Validation

I place strong emphasis on designing AI workflows that leave evidence.

Depending on the task, this can include:

- structured reports;
- before-and-after comparisons;
- schema validation;
- exact-path verification;
- negative tests;
- checksums;
- independent reproduction;
- explicit failure states;
- source references;
- no-mutation confirmation; and
- preservation of original evidence.

The underlying principle is:

> **Do not merely ask the AI to complete a task. Design the workflow so that successful completion can be independently evaluated.**

---

## Working Principles

Several principles recur throughout my work:

> **AI-generated confidence is not evidence.**

> **Plausibility and provenance are different properties.**

> **A passing test does not necessarily prove preservation of the intended invariant.**

> **Technical capability does not automatically create decision authority.**

> **Temporary context should not silently become permanent policy.**

> **Missing evidence should remain missing unless reconstruction is justified.**

> **Human approval should remain distinguishable from AI recommendation.**

> **AI systems should be evaluated not only by what they produce, but by whether the process that produced it remains trustworthy.**

---

## Proprietary Work and Confidentiality

Much of the practical experience represented in this portfolio comes from an ongoing proprietary technical project.

For that reason, portfolio examples intentionally omit or generalize:

- project names;
- internal architecture;
- datasets;
- source code;
- filenames;
- system identifiers;
- business logic;
- proprietary research objectives; and
- operational details.

The examples are intended to demonstrate **reasoning, AI interaction, evaluation methodology, and workflow design**, not to disclose confidential project information.

Where appropriate, additional detail may be discussed privately within reasonable confidentiality boundaries.

---

## Areas of Professional Interest

I am interested in opportunities involving:

- Prompt Engineering
- AI Interaction Design
- AI Workflow Design
- Model Evaluation
- Human–AI Collaboration
- AI Quality Assurance
- Agent Orchestration
- Human-in-the-Loop Systems
- Model Behavior Analysis
- AI Governance Implementation
- Applied AI Research Support
- AI Reliability and Validation

---

## Portfolio Contents

Planned materials for this repository include:

- `case-studies/` — generalized AI interaction and evaluation cases
- `prompt-examples/` — selected prompt design examples
- `workflow-examples/` — multi-stage and multi-agent workflow designs
- `evaluation-examples/` — examples of validation and evaluation reasoning
- `resume/` — current professional résumé
- `recommendations/` — selected professional recommendation materials
- `about/` — background and professional-interest information

Repository structure may evolve as additional examples are added.

---

## About Me

**Matthew Miscisin**

I am an independent applied-AI practitioner with extensive hands-on experience working with advanced language models and AI coding agents in long-running technical and research workflows.

My particular interest is the boundary between **human intent and AI execution**: how instructions are interpreted, how authority is preserved, how errors propagate, how evidence is validated, and how humans can remain meaningfully in control as AI systems become more capable.

I am especially interested in work where thoughtful AI interaction, prompt design, evaluation, and human oversight matter as much as raw model capability.

---

## Contact

**Email:** [YOUR PROFESSIONAL EMAIL]

**LinkedIn:** [YOUR LINKEDIN URL]

**Portfolio / Website:** [YOUR WEBSITE, IF APPLICABLE]

**GitHub:** https://github.com/mcmiscisin

**WhatsApp:** [YOUR WHATSAPP LINK, IF YOU WANT TO INCLUDE IT]

**Location:** [CITY, STATE]

**Availability:** [REMOTE / HYBRID / TRAVEL / RELOCATION DETAILS]

---

## Professional Materials

- [Résumé](./resume/README.md)
- [AI Interaction Case Studies](./case-studies/README.md)
- [Prompt Engineering Examples](./prompt-examples/README.md)
- [Letter of Recommendation](./recommendations/README.md)

*Links above can be updated as portfolio materials are added.*

---

## A Note on AI Assistance

AI systems have played a substantial role in the technical work represented by this portfolio.

That is intentional.

My professional interest is not in presenting AI-assisted work as though it were produced without AI. My interest is in demonstrating the ability to **direct, constrain, evaluate, and collaborate effectively with capable AI systems**.

The relevant question is not simply:

> "Did AI help produce this?"

The more useful questions are:

> "Was the human objective specified correctly?"

> "Was the AI given appropriate authority?"

> "Can the resulting work be verified?"

> "Were assumptions and evidence kept separate?"

> "Did the human retain meaningful control over important decisions?"

Those are the questions this portfolio is intended to explore.

---

## License

Unless otherwise stated, the written case studies and portfolio materials in this repository are provided for viewing and professional evaluation only.

No license for reuse, modification, or redistribution is granted unless explicitly stated for a particular file.

---

*Last updated: September 2026*
