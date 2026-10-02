# AI Interaction & Evaluation Case Studies

These case studies are drawn from documented work within an ongoing **proprietary AI-assisted technical research and software-development project** in which I have worked extensively with advanced AI systems and AI coding agents over a prolonged period.

## Why the cases are generalized

The underlying project's purpose, architecture, datasets, implementation details, internal identifiers, research outputs, and other project-specific information are proprietary. For that reason, the cases in this public portfolio intentionally omit or generalize details that could reveal the project itself.

The generalization is intended to protect proprietary information—not to make the cases hypothetical.

The human–AI interaction patterns, failure modes, interventions, governance changes, and methodological lessons described here are based on real project work.

## Access to more specific case material

Where appropriate, more specific supporting material or a less-generalized discussion of an individual case **may be available upon request**.

Because that material could contain proprietary or confidential information, any additional disclosure would be considered on a case-by-case basis and may require execution of an appropriate **Non-Disclosure Agreement (NDA)** before access is provided.

Availability of additional detail is not guaranteed; disclosure depends on the nature of the request, the information involved, and applicable confidentiality constraints.

## Case studies

### 1. [Authority Drift in Long-Context AI Collaboration](./01-authority-drift.md)

A valid temporary restriction gradually became represented by an AI system as though it were a permanent architectural requirement.

**Focus:** long-context semantic drift, instruction scope, authority preservation, and temporal status.

---

### 2. [When a Plausible Provenance Explanation Was Mistaken for Source Evidence](./02-evidence-provenance.md)

A technically coherent AI-generated explanation acquired more evidentiary authority than the underlying source justified.

**Focus:** provenance, evidence versus interpretation, source grounding, and primary-source verification.

---

### 3. [Multi-Agent Diagnostic Handoff Produced the Wrong Remedy](./03-multi-agent-handoff.md)

A chain of otherwise reasonable AI-assisted diagnostic steps produced a proposed fix that addressed the visible symptom while weakening a higher-level invariant.

**Focus:** multi-agent handoffs, causal diagnosis, architectural constraints, and human review.

---

### 4. [Maintaining Human Control Despite Technical Asymmetry](./04-human-control-technical-asymmetry.md)

A governance approach for maintaining meaningful human control when AI systems possess substantially greater implementation fluency than the human supervisor.

**Focus:** human oversight, bounded execution, authority separation, validation, and acceptance controls.

---

### 5. [Detecting Temporal Leakage in an Evaluation](./05-temporal-leakage-evaluation.md)

Historically valid information was distinguished from information legitimately available at the evaluated decision point.

**Focus:** causal validity, temporal leakage, benchmark integrity, and information availability.

---

### 6. [Treating Missing Evidence as Missing Rather Than Inventing It](./06-missing-evidence.md)

Missing observations were preserved as unobserved evidence rather than being silently interpolated or regularized for computational convenience.

**Focus:** epistemic integrity, missing data, synthetic reconstruction, and research methodology.

---

## Common pattern across the cases

Across these examples, the recurring issue is not usually an obvious model failure. The AI output is often locally reasonable but becomes problematic when an important distinction is lost:

- a temporary constraint becomes permanent;
- a plausible explanation becomes source truth;
- a symptom-level fix violates a higher-level invariant;
- technical capability becomes confused with decision authority;
- historical data becomes confused with causally available information; or
- missing evidence becomes reconstructed evidence.

My recurring role has been to identify those hidden distinctions, make them explicit, preserve the original evidence, define the relevant authority boundary, and require a validation mechanism capable of showing whether a proposed correction actually works.

I am particularly interested in whether observations like these can be converted into controlled evaluations of advanced AI systems in areas such as:

- long-horizon human–AI collaboration;
- epistemic reliability;
- provenance;
- specification interpretation;
- human oversight;
- multi-agent coordination;
- evaluation validity; and
- meaningful human control.

---

## Portfolio context

These files are intended to demonstrate reasoning, AI interaction, evaluation methodology, and workflow design while respecting the confidentiality of the proprietary project from which the cases originate.
