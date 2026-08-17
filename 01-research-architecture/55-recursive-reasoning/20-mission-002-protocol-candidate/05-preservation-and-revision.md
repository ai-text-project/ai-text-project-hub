# Preservation and Revision

**Repository:** AI Text Project Hub  
**Research Area:** Recursive Reasoning  
**Mission:** Mission 002 — Protocol Candidate Formation  
**Document Type:** Operational Mechanism  
**Status:** Evidence-Supported / Internally Restabilized  
**Version:** v0.1

---

# Purpose

This document specifies the operational relationship between Preservation and Revision after recursive examination has been completed.

The preceding Mission 002 assets established:

- when a new observation becomes a meaningful recursive trigger
- when recursive re-entry is required
- where recursive examination should begin
- how far recursive examination should propagate

Those mechanisms determine whether and how earlier reasoning should be re-examined.

However, recursive examination alone does not determine what should happen to the reasoning structure that has been examined.

A further operational judgment is required:

> **What should remain unchanged?**

and:

> **What requires structural change?**

These correspond to:

- Preservation
- Revision

The objective of this document is not to define the complete downstream restabilization process.

The objective is to specify the operational mechanism governing the transition:

> **Recursive Examination → Structural Evaluation → Preservation / Revision**

The subsequent questions of how changes propagate through later reasoning and how the updated reasoning structure becomes stable again belong to downstream operational analysis.

---

# Position within Mission 002

The current Mission 002 sequence is:

~~~text
02 — Operational Requirements
        ↓
03 — Recursive Trigger and Re-entry
        ↓
04 — Recursive Target and Depth
        ↓
05 — Preservation and Revision
        ↓
06 — Restabilization
        ↓
07 — Human–AI Coupling
        ↓
Mission 002 Closure
~~~

The preceding asset answers:

> **Where should recursive examination begin?**

and:

> **How far should recursive examination propagate?**

This document begins after the relevant earlier reasoning has been examined.

Its central responsibility is:

> **To determine which elements of the examined reasoning structure remain structurally valid and should be preserved, and which elements exhibit materially consequential inadequacy or change and therefore require revision.**

---

# Relationship to Recursive Target and Depth

The preceding mechanism established:

> **Target determines where recursive examination begins.**

> **Depth determines how far structurally relevant examination propagates after entry.**

Together they establish:

> **Bounded Recursive Examination Scope**

The relationship to the present mechanism is:

~~~text
04 — Recursive Target and Depth
        │
        ▼
Recursive Target Selected
        │
        ▼
Recursive Depth Determined
        │
        ▼
Bounded Recursive
Examination Scope
        │
        ▼
Recursive Examination
        │
        ▼
──────────────────────────────
Responsibility Boundary
──────────────────────────────
        │
        ▼
05 — Preservation and Revision
        │
        ▼
What Remains Structurally Valid?
        │
        +
        │
What Requires Structural Change?
~~~

Accordingly, this document does not reconsider:

- whether recursive re-entry was necessary
- whether the selected target was appropriate
- whether the selected depth was sufficient

unless new evidence materially destabilizes those earlier judgments.

The operational focus has moved from:

> **scope of examination**

to:

> **disposition of examined structure**

---

# Core Operational Problem

Recursive re-entry does not imply that earlier reasoning was wrong.

An earlier finding may be re-examined and ultimately remain valid.

Likewise, discovering a problem in one component does not imply that the entire earlier structure must be replaced.

Therefore:

> **Recursive Re-entry ≠ Revision**

and:

> **Recursive Target ≠ Revision Target**

The fact that reasoning has been selected for reconsideration establishes only that it must be examined.

It does not predetermine the outcome of that examination.

---

# Initial Binary Candidate

The simplest operational model is:

~~~text
Earlier Finding Re-examined
        │
        ▼
Still Structurally Valid?
        │
        ├── Yes
        │     ↓
        │  Preserve
        │
        └── No
              ↓
           Revise
~~~

This suggests a binary classification:

> **Preserve OR Revise**

The model is attractive because it is simple.

However, it contains an implicit assumption:

> the entire examined Finding must receive one disposition.

That assumption requires counter-testing.

---

# Counter-Test — Partial Structural Failure

Consider an earlier Finding F composed of several structural components:

~~~text
Component A
     +
Component B
     +
Component C
     ↓
Finding F
~~~

Recursive examination produces:

~~~text
Component A → remains valid
Component B → remains valid
Component C → materially destabilized
~~~

If the entire Finding is classified as:

> Preserve

the problem in C is ignored.

If the entire Finding is classified as:

> Revise

the continued validity of A and B is obscured.

The actual disposition is:

~~~text
A → Preserve
B → Preserve
C → Revise
        ↓
Updated Finding F
~~~

Therefore:

> **Preservation and Revision are not necessarily mutually exclusive at the structural-component level.**

This directly challenges whole-Finding binary classification.

---

# Whole-Finding Binary Classification

The counter-test indicates that:

> **Preserve OR Revise**

is too coarse when applied to an entire reasoning structure.

A reasoning structure may contain:

- preserved components
- revised components
- preserved relations
- revised dependencies
- unchanged assumptions
- qualified scope conditions

simultaneously.

Therefore:

> **Whole-Finding Exclusive Binary Classification is not retained as the primary operational model.**

However, this does not yet imply that Preservation and Revision themselves should be abandoned.

---

# Preservation and Revision as an Operational Pair

The counter-test can be absorbed without creating multiple new disposition categories.

Instead of asking:

> Should this whole Finding be Preserved or Revised?

the process can ask:

> **What within the examined structure remains structurally valid?**

and:

> **What within the examined structure materially requires change?**

This produces:

~~~text
Examined Structure
        │
        ▼
Structural Evaluation
        │
        ├── Structurally Valid Elements
        │           ↓
        │       Preserve
        │
        └── Materially Affected Elements
                    ↓
                 Revise
~~~

Thus:

> **Preservation and Revision remain a valid Operational Pair even though they do not function as mutually exclusive classifications of the entire Finding.**

---

# Structural Granularity

The preceding counter-test exposes the importance of judgment granularity.

Preservation and Revision may apply to different structural units, including:

- complete findings
- finding components
- assumptions
- interpretations
- relations
- dependencies
- scope conditions
- qualifications

For example:

~~~text
Finding F
│
├── Core Relation        → Preserve
├── Scope Condition      → Revise
└── Supporting Evidence  → Preserve
~~~

The relevant unit of judgment may therefore vary with the structure being examined.

However, this does not require a new independent operational mechanism.

Structural Granularity is treated here as:

> **a property of Preservation / Revision Judgment**

rather than:

> a separate protocol stage.

---

# Structural Unit of Judgment

The examined structure may be decomposed only to the degree necessary for adequate Preservation / Revision judgment.

The process does not require every Finding to be decomposed into a universal set of predefined components.

Instead:

> **the Structural Unit of Judgment is context-sensitive to the recursive problem and the structure exposed during examination.**

This preserves compatibility with:

- single findings
- multi-component findings
- dependency structures
- assumption networks
- qualified propositions

without requiring a fixed universal ontology of reasoning components.

---

# Counter-Test — Qualification Without Replacement

Consider an earlier Finding:

> X is structurally necessary.

Recursive examination introduces evidence showing that the relation holds only under a particular condition:

> X is structurally necessary under condition Y.

The original Finding is not simply discarded.

Instead:

~~~text
Original Finding
        │
        ├── Core Relation
        │       ↓
        │    Preserve
        │
        └── Scope Condition
                ↓
             Revise
                ↓
Qualified Finding
~~~

This demonstrates:

> **Revision may occur through qualification rather than replacement.**

The presence of Revision therefore does not imply complete rejection of the earlier Finding.

---

# Counter-Test — Dependency Revision Without Finding Revision

Consider:

~~~text
A
↓
B
↓
Finding F
~~~

After recursive examination, the structure becomes:

~~~text
A
↓
C
↓
Finding F
~~~

The final Finding F remains unchanged.

However, its supporting dependency structure has changed.

Therefore:

~~~text
Finding F
        ↓
Preserve

Supporting Dependency
        ↓
Revise
~~~

This demonstrates that Preservation / Revision Judgment must be capable of operating below the level of the final Finding.

Again:

> **Finding Preservation does not imply complete structural preservation.**

---

# Preservation Is Not Mere Non-Rejection

A second weakness appears in the initial binary model.

Suppose recursive examination finds no contradiction.

The process might conclude:

~~~text
No Contradiction
        ↓
Preserve
~~~

However:

> **absence of detected contradiction does not necessarily establish adequate grounds for Preservation.**

Evidence may be insufficient.

Relevant dependencies may remain unresolved.

The examination may simply be unable to determine whether change is required.

Therefore:

> **Not Revised ≠ Necessarily Preserved**

A Preservation judgment requires an adequate basis.

---

# Judgment Readiness

This produces an apparent third state:

> Undetermined

At first, the operational structure might appear to require:

~~~text
Preserve
Revise
Undetermined
~~~

However, closer examination suggests that Undetermined is not equivalent to Preservation or Revision.

Preservation and Revision describe:

> **structural disposition**

Undetermined describes:

> **the current readiness of the judgment**

Therefore the two dimensions should remain distinct.

---

# Disposition vs. Judgment State

The distinction is:

~~~text
JUDGMENT STATE

Is there a sufficient basis
for structural disposition?
        │
        ├── No
        │     ↓
        │  Judgment Not Yet Stabilized
        │
        └── Yes
              ↓
STRUCTURAL DISPOSITION

Preserve relevant structure
and/or
Revise affected structure
~~~

Thus:

> **Undetermined is not introduced as a third structural disposition.**

Instead:

> **Judgment Not Yet Stabilized**

describes a state in which the available recursive examination does not yet support an adequate Preservation / Revision judgment.

---

# Sufficient Basis for Judgment

Before Preservation or Revision can be assigned, the process must determine whether the recursive examination provides an adequate basis for structural disposition.

The question is:

> **Has the relevant structure been examined sufficiently to determine whether meaningful structural change is required?**

If not:

~~~text
Recursive Examination
        ↓
Insufficient Basis
        ↓
Judgment Not Yet Stabilized
~~~

The process should not force either Preservation or Revision merely to complete the operational sequence.

This protects against premature disposition.

---

# Preservation Minimum Condition

The first candidate Preservation rule is:

> Preserve when no contradiction is detected.

As already shown, this is insufficient.

A stronger formulation is:

> **Preserve examined structure when recursive examination reveals no materially consequential reason requiring structural change within the relevant judgment scope.**

This does not claim:

> the structure has been proven permanently correct.

Instead, it means:

> given the current evidence and the relevant dependencies examined, no material structural reason has been identified that justifies changing the structure.

---

# Preservation Is Provisional Relative to Evidence

Preservation should therefore be interpreted as:

> **continued structural validity under the current recursive examination**

rather than:

> final or irreversible correctness.

A preserved Finding may later become the target of another recursive trigger if new evidence emerges.

Thus:

~~~text
Preserve
    ≠
Permanent Freeze Against Future Evidence
~~~

Preservation closes the current disposition judgment.

It does not eliminate future revisability.

---

# Preservation Candidate Mechanism

The Preservation side can be represented as:

~~~text
Examined Structure
        │
        ▼
Sufficient Basis for Judgment?
        │
        ├── No
        │     ↓
        │ Judgment Not Yet Stabilized
        │
        └── Yes
              ↓
Materially Consequential
Reason for Structural Change?
        │
        ├── No
        │     ↓
        │  Preserve
        │
        └── Yes
              ↓
        Revision Evaluation
~~~

Preservation is therefore not triggered by mere inactivity.

It is the result of an explicit structural evaluation.

---

# Revision Minimum Condition

The simplest Revision candidate is:

> Revise whenever new evidence differs from the existing structure.

This is also too broad.

Not every difference is structurally consequential.

A new observation may:

- add detail without changing the Finding
- concern an irrelevant dependency
- fall outside the Finding's scope
- produce no meaningful effect on the current reasoning structure

Therefore:

> **Difference Detected ≠ Revision Required**

A stronger criterion is necessary.

---

# Material Structural Consequence

The emerging Revision criterion is:

> **Revision is required when unchanged Preservation would retain, lose, or distort materially consequential structural information exposed by recursive examination.**

This includes cases in which recursive examination reveals:

- contradiction
- inadequacy
- missing qualification
- materially altered dependency
- structurally relevant scope change
- necessary refinement

These need not become separate Revision categories.

They can be evaluated through the higher-order question:

> **Would preserving the current structure unchanged fail to represent the materially relevant result of recursive examination?**

If yes, Revision becomes necessary.

---

# Revision Candidate Mechanism

The Revision side can therefore be represented as:

~~~text
Recursive Examination
        │
        ▼
Newly Exposed Difference /
Evidence / Dependency
        │
        ▼
Would Unchanged Preservation
Lose, Distort, or Retain
Materially Consequential
Structural Information?
        │
        ├── No
        │     ↓
        │  Revision Not Required
        │
        └── Yes
              ↓
           Revise
~~~

Revision is therefore triggered by:

> **Material Structural Consequence**

rather than mere difference.

---

# Revision Is Not Limited to Error Correction

A particularly important implication follows.

Revision does not require the earlier Finding to be simply wrong.

For example:

~~~text
Earlier Finding

X affects Y

        ↓

Recursive Examination

        ↓

Updated Finding

X affects Y under condition Z
~~~

The original relation may remain broadly valid.

However, the new condition Z is materially relevant.

Leaving the Finding unchanged would lose structural precision.

Therefore:

> **Revision may be justified by Material Structural Refinement even when the earlier Finding is not simply false.**

Revision includes more than error correction.

---

# Revision Forms

Revision may take forms such as:

- qualification
- scope restriction
- dependency adjustment
- relation modification
- assumption replacement
- structural refinement
- component replacement

These forms are descriptive examples.

They are not introduced as separate protocol stages.

The common operational principle remains:

> **Revise only where recursive examination exposes materially consequential structural change.**

---

# Common Judgment Axis

Preservation and Revision can now be placed on a common judgment axis.

The central question is:

> **Does recursive examination expose a materially consequential reason for structural change?**

The mechanism becomes:

~~~text
Recursive Examination Completed
        │
        ▼
Sufficient Basis for Judgment?
        │
        ├── No
        │     ↓
        │ Judgment Not Yet Stabilized
        │
        └── Yes
              ↓
Material Structural Consequence?
        │
        ├── No
        │     ↓
        │  Preserve
        │
        └── Yes
              ↓
           Revise
~~~

However, this representation remains simplified because a complex structure may contain both preserved and revised components.

The judgment therefore operates at the relevant Structural Granularity.

---

# Component-Sensitive Disposition

The more precise form is:

~~~text
Recursive Examination Completed
        │
        ▼
Sufficient Basis for Judgment?
        │
        ├── No
        │     ↓
        │ Judgment Not Yet Stabilized
        │
        └── Yes
              ↓
Evaluate Relevant
Structural Components
              │
              ▼
For Each Structurally Relevant Unit:
              │
              ▼
Material Structural Consequence?
        │
        ├── No
        │     ↓
        │  Preserve
        │
        └── Yes
              ↓
           Revise
~~~

This allows Preservation and Revision to coexist within the same examined reasoning structure.

---

# Preservation and Revision Are Not Symmetric Labels

Although both operate through Material Structural Consequence, they should not be interpreted merely as opposite labels.

Preservation means:

> continued use of structure that remains adequate under recursive examination.

Revision means:

> modification of structure where unchanged continuation would fail to represent materially consequential recursive findings.

Thus the operational objective is not to classify.

The objective is:

> **to retain valid structure while changing only structure for which meaningful change is justified.**

---

# Emerging Selectivity

This produces a selective pattern:

~~~text
Examined Structure
        │
        ├── Unaffected / Valid
        │        ↓
        │     Preserve
        │
        └── Materially Affected
                 ↓
              Revise
~~~

At first, this may appear to require a separate:

> Selective Revision Mechanism.

That possibility requires counter-testing before the mechanism can be considered stable.

---

# Selective Revision Candidate

The independent-mechanism hypothesis would be:

~~~text
Preserve / Revise Judgment
        │
        ▼
Revision Required
        │
        ▼
Selective Revision Mechanism
        │
        ▼
Determine Revision Scope
~~~

Under this model:

1. the process first decides that Revision is required
2. a separate mechanism then determines how much structure should be changed

This would create an additional operational stage.

However, the component-sensitive disposition already identified may make this separate mechanism unnecessary.

The next section examines that possibility.

---

# Current Interim Assessment

At this stage, the following findings are supported:

1. Recursive re-entry does not imply Revision.
2. Recursive Target does not equal Revision Target.
3. Whole-Finding Preserve / Revise binary classification is too coarse.
4. Preservation and Revision remain viable as an Operational Pair.
5. Preservation and Revision can coexist across structural components.
6. Structural Granularity is a property of the disposition judgment rather than a separate mechanism.
7. Judgment readiness is distinct from structural disposition.
8. Undetermined does not require a third disposition.
9. Preservation requires more than absence of detected contradiction.
10. Revision requires Material Structural Consequence rather than mere difference.
11. Revision may include refinement or qualification rather than replacement.
12. Selective Revision has emerged as a candidate property whose independence must still be tested.

The mechanism has therefore moved beyond the initial binary model but has not yet completed Restabilization.

---

# Transition to Selective Revision Counter-Test

The next question is intentionally narrow:

> **Is Selective Revision genuinely an independent operational mechanism, or is it already contained within component-sensitive Preservation / Revision Judgment?**

If independent, Mission 002 may require an additional mechanism.

If absorbable, Preservation / Revision can remain structurally compact.

This counter-test is addressed in the next part of this document.

---

# End of Part 1/3
