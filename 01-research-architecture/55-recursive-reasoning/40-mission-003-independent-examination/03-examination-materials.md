# Examination Materials

**Research Area:** Recursive Reasoning  
**Mission:** 003 — Independent Examination  
**Asset:** 03 — Examination Materials  
**Status:** Current Baseline  
**Upstream Assets:** `01-examination-boundary.md`, `02-independent-instance-protocol.md`  
**Downstream Asset:** `04-examination-procedure.md`

---

# Purpose

This document defines the material architecture for Independent Examination in Mission 003.

The Independent Instance Protocol established in `02-independent-instance-protocol.md` defines two primary operational safeguards:

```text
Instance-State Separation
        +
Context Control
        ↓
Formation-Process Separation
        ↓
Judgment Independence
```

The responsibility of this asset is narrower.

It asks:

> **What information should be presented to the independent examination source so that Object Validity is preserved without unnecessarily weakening Formation-Process Separation?**

The problem is therefore not to maximize or minimize information.

The problem is to construct a sufficient but non-conditioning Examination Material Package.

---

# Material Responsibility

The responsibility of this asset is:

```text
03 — Examination Materials
        ↓
Define the concrete information
composition presented to the
independent examination source
```

This asset does not redefine:

- the Mission 003 purpose;
- the Examination Boundary;
- the Independent Instance Protocol;
- the examination procedure;
- or the final Validation Status.

Its responsibility is limited to material exposure.

---

# Upstream Constraints

The Examination Material Package inherits two primary constraints.

From `01-examination-boundary.md`:

```text
Object Validity
        ↓
The intended research object
must remain meaningfully examinable.
```

From `02-independent-instance-protocol.md`:

```text
Context Control
        ↓
Necessary Object Context
must be preserved.

Formation-conditioning Context
must be restricted.
```

03 therefore operates between two failure directions:

```text
Too Little Information
        ↓
Object Validity weakened
```

and:

```text
Too Much Formation Information
        ↓
Formation-Process Separation weakened
```

The material architecture must remain between these two failure conditions.

---

# Core Material Principle

The Current Baseline is:

> **Provide what is necessary to examine the Protocol Candidate while excluding, by default, information whose primary function is to reconstruct the Protocol Candidate's formation trajectory.**

This can be represented as:

```text
Enough information
to examine the object
        +
Enough separation
from formation history
        ↓
Independent Examination Package
```

---

# Examination Material Package

The Current Baseline identifies four primary material components:

```text
        EXAMINATION MATERIAL PACKAGE
                    │
      ┌─────────────┼─────────────┐
      ▼             ▼             ▼
 Examination    Necessary      Canonical
  Mandate      Object Context Protocol Object
                                    │
                                    ▼
                            Evidence Boundary
```

These components serve different responsibilities.

They should not be collapsed into a general background package.

---

# 1. Examination Mandate

The independent examination source must understand what it is being asked to examine.

The Examination Mandate therefore establishes:

```text
What is being examined?

What kind of examination
is requested?

What judgment responsibility
belongs to the independent source?
```

The mandate must provide sufficient task orientation without directing the outcome.

It should not contain statements such as:

```text
Confirm that the Protocol works.
```

or:

```text
Demonstrate that the Protocol
is structurally robust.
```

Such framing may introduce Judgment Steering.

The mandate should preserve the possibility of:

```text
Preservation

Revision

Qualification

Rejection

Unexpected Observation
```

The exact wording of the examination instruction belongs to `04-examination-procedure.md`.

03 defines only the information requirement.

---

# 2. Necessary Object Context

The independent examination source requires sufficient context to understand the object being examined.

Necessary Object Context may include information required to understand:

- what Recursive Reasoning refers to in this research;
- what the Protocol Candidate is intended to do;
- relevant terminology;
- the Protocol's structural position;
- and the scope of the examination.

However:

```text
Necessary Object Context
        ≠
Complete Research History
```

The purpose is not to teach the independent instance how the Protocol was developed.

The purpose is to make the Protocol meaningfully examinable.

---

# Interpretive Sufficiency

Necessary Object Context is governed by:

> **Interpretive Sufficiency**

The independent examination source should receive enough information to interpret the Canonical Protocol Object without requiring reconstruction of Mission 001 or Mission 002.

Conceptually:

```text
Canonical Protocol Object
        ↓
Sufficiently Interpretable?
        │
     ┌──┴──┐
     ▼     ▼
    YES    NO
     │      │
     │      ▼
     │   Add Necessary
     │   Object Context
     │
     └──────┬──────
            ▼
     Examination Ready
```

If additional explanation is required, the preferred response is not automatically to expose Formation History.

Instead:

```text
Missing Interpretive Context
        ↓
Formation-neutral
Object Context
        ↓
Interpretive Sufficiency
```

should be attempted first.

---

# 3. Canonical Protocol Object

The central examination object must be the Protocol Candidate itself.

The Independent Instance should not examine only:

```text
A description of the Protocol
```

or:

```text
A retrospective summary
of the Protocol
```

when a canonical Protocol representation is available.

The Current Baseline therefore requires:

> **Canonical Object Exposure**

Conceptually:

```text
Protocol Candidate
        ↓
Canonical Representation
        ↓
Independent Examination
```

This protects Object Validity.

---

# Object Substitution Risk

If the Independent Instance receives only a secondary summary, the examination may become:

```text
Summary
        ↓
Examination
```

rather than:

```text
Protocol Candidate
        ↓
Examination
```

The resulting evidence would then apply most directly to the summary representation.

This creates an Object Substitution risk.

Therefore:

```text
Canonical Protocol Object
        ✓ REQUIRED
```

unless a later procedural reason demonstrates that another representation is necessary.

Any such substitution should be explicit and traceable.

---

# Representation Fidelity

The material package must preserve sufficient fidelity between:

```text
Research Object
```

and:

```text
Presented Examination Object
```

The relevant principle is:

```text
Presented Representation
        ↓
must preserve
        ↓
Material Structure of
the Protocol Candidate
```

This does not require every historical artifact to be included.

It requires the examination object itself to remain structurally faithful.

---

# 4. Evidence Boundary

The Independent Instance also requires sufficient information to understand the evidential responsibility of the examination.

This includes the distinction between:

```text
Examination
```

and:

```text
Validation
```

The examination source should not be implicitly instructed that the Protocol Candidate has already been validated.

Likewise, it should not be asked to assign evidential status beyond the examination it actually performs.

The material package should therefore preserve the current evidence boundary:

```text
Protocol Candidate
        ↓
Independent Examination
        ↓
New Evidence
```

not:

```text
Validated Protocol
        ↓
Confirmation
```

---

# Evidence Boundary Is Not Outcome Framing

The Evidence Boundary provides limits on what may legitimately be concluded.

It must not tell the Independent Instance what conclusion it should reach.

Therefore:

```text
Evidence Boundary
        ✓
```

but:

```text
Expected Examination Result
        ✗
```

This distinction protects Judgment Independence.

---

# Formation History

Formation History is not part of the default Examination Material Package.

Formation History may include:

- Mission 001 developmental reasoning;
- Mission 002 Candidate Formation history;
- Counter-test sequences;
- rejected alternatives;
- preservation rationales;
- developmental dialogue;
- prior interpretive debates;
- and reasons why specific structures survived earlier examination.

These materials may be valuable research records.

However, their value as research records does not make them necessary Independent Examination materials.

---

# Default Formation-History Rule

The Current Baseline is:

```text
Formation History
        ↓
EXCLUDED BY DEFAULT
```

The reason is not that Formation History is invalid or irrelevant.

The reason is that its inclusion may transfer:

```text
How the Protocol
was formed
```

together with:

```text
What the Protocol is
```

Mission 003 seeks to separate these where possible.

---

# Formation History versus Object Context

The distinction is:

```text
Object Context
        ↓
Helps understand
what is being examined
```

versus:

```text
Formation History
        ↓
Explains how and why
the object became what it is
```

Mission 003 requires the first.

It does not require the second by default.

---

# Formation History Is Not Absolutely Prohibited

The default exclusion rule is not an absolute prohibition.

An examination may reveal that a particular piece of historical information is genuinely necessary for interpreting the research object.

If this occurs, the requirement should be handled explicitly rather than silently expanding the package.

Conceptually:

```text
Independent Examination
        ↓
Material Information Gap
        ↓
Determine whether
additional context is necessary
        ↓
Assess conditioning risk
        ↓
Controlled additional exposure
```

The exact procedure for such requests belongs to `04-examination-procedure.md`.

---

# Developmental Reasoning

Developmental Reasoning should not be included merely because it makes the Protocol easier to explain.

Doing so may convert the examination from:

```text
Examine this Protocol.
```

into:

```text
Follow the reasoning through
which we concluded that this
Protocol should have this form.
```

Those are materially different tasks.

The second risks reconstructing the formation trajectory.

Therefore developmental explanation should be replaced, where possible, by formation-neutral Object Context.

---

# Counter-test History

Previous Counter-tests are particularly sensitive.

They may reveal:

```text
Which objections
were already considered

Which alternatives
were rejected

Which structures
were preserved

Why those structures
were preserved
```

This can substantially narrow the Independent Instance's search space.

Therefore:

```text
Prior Counter-test History
        ↓
EXCLUDED BY DEFAULT
```

The Independent Instance should be allowed to discover similar or different objections independently.

---

# Rejected Alternatives

Rejected alternatives are also excluded by default.

Providing them may direct the Independent Instance toward the same candidate space already explored during formation.

Mission 003 should preserve the possibility that the independent source identifies:

```text
Previously rejected alternatives

Previously unseen alternatives

Different problem formulations

Different structural weaknesses
```

without being preconditioned by the prior search trajectory.

---

# Preservation Rationales

Statements explaining why a structure survived Mission 002 should normally remain outside the initial material package.

For example:

```text
This component was preserved
because Counter-test X showed
that removing it creates Y.
```

contains more than object description.

It transfers a prior defense of the object.

Therefore:

```text
Preservation Rationale
        ↓
Formation-conditioning Context
```

unless the rationale is itself part of the canonical Protocol definition.

---

# Expected Outcome

Expected Outcome information should not be included.

Examples include:

```text
We expect the independent
instance to confirm...
```

```text
The Protocol is probably robust...
```

```text
Previous analysis strongly suggests...
```

Such information does not improve Object Validity.

It primarily affects Judgment Independence.

Therefore:

```text
Expected Outcome
        ✗
```

---

# Material Inclusion Test

A candidate material may be evaluated using two questions.

## Question 1 — Object Necessity

> **Is this material necessary for the Independent Instance to meaningfully understand or examine the Protocol Candidate?**

If:

```text
NO
```

there is no strong Object Validity reason for inclusion.

---

## Question 2 — Formation-conditioning Risk

> **Does this material substantially transfer the reasoning path, prior defenses, rejected alternatives, or expected outcome through which the Protocol Candidate was formed?**

If:

```text
YES
```

there is a Formation-Process Separation reason for exclusion or restriction.

---

# Inclusion Logic

The resulting logic is:

```text
Candidate Material
        ↓
Necessary for Object Validity?
        │
    ┌───┴───┐
    ▼       ▼
   YES      NO
    │        │
    ▼        ▼
Formation   Exclude
Risk?
    │
 ┌──┴──┐
 ▼     ▼
LOW   HIGH
 │      │
 ▼      ▼
Include  Seek a more
         formation-neutral
         representation
```

This is a selection principle rather than an exhaustive file-selection algorithm.

---

# Formation-neutral Representation

When a necessary concept exists only inside a Formation History asset, the preferred strategy is:

```text
Necessary Concept
        ↓
Extract functional meaning
        ↓
Represent without
developmental trajectory
        ↓
Necessary Object Context
```

The purpose is not to conceal research history.

The purpose is to prevent historical reasoning from being mistaken for necessary object definition.

---

# Initial Material Package

The Current Baseline therefore favors an initial package containing:

```text
1. Examination Mandate

2. Necessary Object Context

3. Canonical Protocol Object

4. Evidence Boundary
```

while excluding by default:

```text
Mission 001 Formation History

Mission 002 Development History

Prior Counter-tests

Rejected Alternatives

Preservation Rationales

Expected Outcome
```

This package is intended to be sufficient for examination without reproducing the formation environment.

---

# Material Minimalism Is Not the Goal

The package should not be minimized merely to make the examination appear more independent.

For example:

```text
Protocol File Only
        ↓
No Terminological Context
        ↓
Misinterpretation
```

may produce apparently independent but weak evidence.

Therefore:

> **Material sufficiency takes priority over artificial minimalism.**

The package should be as small as reasonably possible only after Object Validity is protected.

---

# Material Expansion Is Evidence-Relevant

If the Independent Instance cannot proceed without additional information, that observation is itself relevant.

It may indicate:

- insufficient Protocol self-containment;
- ambiguous terminology;
- hidden dependencies;
- missing object context;
- or excessive reliance on developmental knowledge.

Therefore additional-information requests should not automatically be treated as procedural inconvenience.

They may constitute evidence about the Protocol Candidate.

---

# Material Traceability

The examination package should be traceable.

Later Mission assets should be able to determine:

```text
What was provided?

What was withheld?

What was added later?

Why was additional material added?
```

This is necessary because examination results cannot be interpreted independently of the material environment in which they were produced.

---

# Relationship to 04 — Examination Procedure

03 determines:

```text
What information
constitutes the examination package
```

04 determines:

```text
How that package
is presented and used
```

Therefore:

```text
03
Material Composition
        ↓
04
Operational Examination Procedure
```

03 does not determine:

- exact prompt wording;
- interaction sequence;
- clarification rules;
- Human intervention rules;
- evidence capture procedure;
- or examination termination conditions.

These remain downstream.

---

# Relationship to the Examination Gate

The Examination Gate should not be crossed until both:

```text
03
Examination Materials
```

and:

```text
04
Examination Procedure
```

are sufficiently defined.

The sequence remains:

```text
02
Independent Instance Protocol
        ↓
03
Examination Materials
        ↓
04
Examination Procedure
        ↓
========================
    EXAMINATION GATE
========================
        ↓
05
Examination Results
```

---

# Core Material Representation

The Current Baseline can be represented as:

```text
             EXAMINATION MATERIAL PACKAGE
                         │
        ┌────────────────┼────────────────┐
        ▼                ▼                ▼
 Examination       Necessary         Canonical
  Mandate         Object Context   Protocol Object
                                           │
                                           ▼
                                   Evidence Boundary

                         │
                         ▼
                Object Validity
                   PRESERVED

------------------------------------------------

               FORMATION INFORMATION
                         │
        ┌────────────────┼────────────────┐
        ▼                ▼                ▼
 Development       Counter-test       Preservation
   History            History          Rationales
                         │
                         ▼
                 Expected Outcome

                         │
                         ▼
                EXCLUDED BY DEFAULT

                         │
                         ▼
             Formation-Process
             Separation protected
```

---

# Core Invariants

The Current Baseline preserves the following invariants.

## Invariant 1

```text
Canonical Protocol Object
        ✓ REQUIRED
```

The examination should apply to the Protocol Candidate rather than merely to a secondary description.

---

## Invariant 2

```text
Necessary Object Context
        ✓ PRESERVE
```

Independence must not be produced through object deprivation.

---

## Invariant 3

```text
Formation History
        ↓
EXCLUDED BY DEFAULT
```

Formation history is not necessary merely because it explains why the Protocol has its current form.

---

## Invariant 4

```text
Formation History
        ≠
Absolutely Prohibited
```

Additional exposure may occur when materially necessary, but must remain explicit and traceable.

---

## Invariant 5

```text
Interpretive Sufficiency
        ≠
Developmental Reconstruction
```

Missing interpretive information should preferably be supplied through formation-neutral Object Context.

---

## Invariant 6

```text
Evidence Boundary
        ≠
Expected Outcome
```

The former protects evidential responsibility.

The latter risks conditioning judgment.

---

## Invariant 7

```text
Material Minimalism
        ≠
Independent Examination
```

Object Validity remains mandatory.

---

# Material Readiness Test

Before proceeding to `04-examination-procedure.md`, the material architecture should satisfy:

```text
Canonical Object available?
        ✓

Necessary Object Context definable?
        ✓

Examination Mandate definable?
        ✓

Evidence Boundary definable?
        ✓

Formation History separable?
        ✓

Material exposure traceable?
        ✓
```

At the Current Baseline, no material structural gap prevents movement to the next asset.

---

# Current State

At completion of this asset:

```text
00 — Mission Definition
        ✓ COMPLETE

01 — Examination Boundary
        ✓ COMPLETE

02 — Independent Instance Protocol
        ✓ COMPLETE

03 — Examination Materials
        ✓ EXTERNALIZED

04 — Examination Procedure
        ← NEXT

==============================
       EXAMINATION GATE
==============================

05 — Examination Results
        PENDING

06 — Comparative Assessment
        PENDING

07 — Validation Status
        PENDING

README
        PENDING
```

No Independent Examination has yet occurred.

The material architecture has been defined, but the operational examination procedure has not yet been established.

---

# Next Research Responsibility

The next asset is:

`04-examination-procedure.md`

Its central question is:

> **How should the independent examination be conducted so that the material package is presented without reintroducing formation influence and the resulting judgment can be preserved as usable evidence?**

The next asset should therefore address only the procedural requirements necessary to reach the Examination Gate.

It should not attempt to perfect every possible examination scenario before empirical use.

Under Accelerated Evidence Mode, procedural design should stop once no Material Gap prevents a credible Independent Examination.

---

# Final Material Principle

The Examination Material Package should expose:

```text
Enough of the research object
to make examination valid
```

without exposing:

```text
So much of its formation trajectory
that the examination becomes
a reconstruction of prior reasoning.
```

The Current Baseline is therefore:

```text
Examination Mandate
        +
Necessary Object Context
        +
Canonical Protocol Object
        +
Evidence Boundary
        ↓
Sufficient Examination Object

Formation History
        ↓
Excluded by Default
        ↓
Formation-Process Separation
Protected
```

This material architecture provides the Current Baseline for proceeding to the final pre-examination design asset of Mission 003.

---

# End of Examination Materials
