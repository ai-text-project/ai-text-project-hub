# Recursive Target and Depth

**Repository:** AI Text Project Hub  
**Research Area:** Recursive Reasoning  
**Mission:** Mission 002 — Protocol Candidate Formation  
**Document Type:** Operational Mechanism  
**Status:** Evidence-Supported / Internally Restabilized  
**Version:** v0.1

---

# Purpose

This document specifies the operational relationship between Recursive Target Selection and Recursive Depth Selection.

The preceding Mission 002 asset established the conditions under which:

> a new observation becomes a meaningful recursive trigger

and:

> resolving that trigger requires recursive re-entry into an earlier reasoning state.

However, determining that recursive re-entry is required does not yet determine how re-entry should be performed.

Two additional judgments immediately arise:

> **Where should recursive examination begin?**

and:

> **How far should recursive examination propagate?**

These correspond to:

- Recursive Target Selection
- Recursive Depth Selection

The objective of this document is not to define the complete Recursive Reasoning Protocol.

The objective is to specify the operational mechanism governing the transition:

> **Recursive Re-entry Required → Target Selection → Depth Selection**

The subsequent questions of what should be preserved and what should be revised belong to the next operational mechanism.

---

# Relationship to Recursive Trigger and Re-entry

The preceding asset established:

> **Trigger ≠ Re-entry**

and identified:

> **Backward Access Requirement**

as the condition under which adequate resolution requires access to an earlier reasoning state.

Its operational endpoint was:

> **Recursive Re-entry Required**

This document begins from that state.

The responsibility relationship is:

~~~text
03 — Recursive Trigger and Re-entry
        │
        │  Should recursive return occur?
        ▼
Recursive Re-entry Required
        │
        ▼
04 — Recursive Target and Depth
        │
        │  Where should re-entry begin?
        │
        │  How deeply should examination propagate?
        ▼
05 — Preservation and Revision
        │
        │  What should be preserved?
        │
        │  What should be revised?
        ▼
Subsequent Operational Mechanisms
~~~

Accordingly, this document does not reconsider whether recursive re-entry is necessary.

That judgment has already been made.

Instead, it begins with the operational problem created by the decision to re-enter.

---

# Core Operational Problem

Once recursive re-entry is judged necessary, the reasoning process faces a potentially large set of earlier reasoning states.

These may include:

- assumptions
- evidence interpretations
- intermediate findings
- dependency relations
- structural judgments
- rejected alternatives
- previous boundary decisions
- earlier representations
- earlier reasoning configurations

The process cannot simply reopen all previous reasoning.

Doing so would transform selective recursion into unrestricted historical reconstruction.

Therefore:

> **Recursive re-entry requires selective access to earlier reasoning.**

Two forms of selectivity are necessary.

First:

> Which earlier reasoning state or state set should become the point of recursive examination?

Second:

> Once examination begins, how far should that examination propagate through earlier dependencies?

These are the Target and Depth problems.

---

# Target Selection

## Initial Candidate

The most immediate candidate rule is:

> Return to the earlier reasoning state in which the current problem originated.

This appears intuitive.

If the current trigger was produced by an earlier error, then returning to the origin of that error seems appropriate.

The structure might appear as:

~~~text
Current Trigger
        │
        ▼
Identify Earlier Cause
        │
        ▼
Return to Causal Origin
        │
        ▼
Recursive Target
~~~

However, this formulation contains an important weakness.

Reasoning problems do not necessarily have a single identifiable causal origin.

---

# Causal Origin Problem

Consider a reasoning trajectory:

~~~text
State A — Assumption
        ↓
State B — Interpretation
        ↓
State C — Finding
        ↓
State D — Structural Relation
        ↓
State E — Current Reasoning State
~~~

Suppose a new trigger destabilizes State D.

The immediate problem may appear at D.

However:

- D may depend on C
- C may depend on B
- B may depend on A

The structural consequence may therefore involve multiple earlier states.

In such a case, asking:

> Where did the problem originate?

may not produce a single operationally useful answer.

The earliest causal state may also be much earlier than necessary for resolving the current trigger.

Therefore:

> **Causal Origin ≠ Recursive Target**

A target should not be selected merely because it is historically earliest or causally prior.

---

# Historical Location vs. Resolution-Relevant Location

The preceding Trigger / Re-entry mechanism established that recursive return is justified by:

> **Backward Access Requirement**

This provides a more useful basis for Target Selection.

The relevant question becomes:

> Which earlier reasoning state must be accessed in order to adequately evaluate and resolve the structural consequence of the current trigger?

This changes the target concept.

A Recursive Target is not primarily:

> a historical location

but:

> **a resolution-relevant location in the earlier reasoning structure.**

This can be provisionally described as:

> **Resolution-Relevant Target**

The target is selected relative to the active trigger and its resolution requirements.

---

# Target Selection Is Relational

Just as Trigger Recognition was relational, Target Selection is also relational.

The relevant unit is not:

> Earlier State A

in isolation.

Instead, it is:

> **Earlier State A × Current Trigger × Resolution Requirement**

An earlier state may be highly important to the overall research trajectory while remaining irrelevant to the active recursive problem.

Conversely, a relatively small earlier judgment may become the appropriate target if it is structurally decisive for resolving the current trigger.

Therefore:

> **Historical importance does not determine recursive target priority.**

Target selection depends on the current resolution requirement.

---

# Multiple Candidate Targets

A single trigger may expose several plausible earlier targets.

Consider:

~~~text
A — Assumption
↓
B — Evidence Interpretation
↓
C — Finding
↓
D — Structural Relation
↓
E — Current State
        ↑
     Trigger X
~~~

If Trigger X destabilizes D, candidate targets may include:

- D itself
- C, which supports D
- B, which supports C
- A, which constrains B

Each may appear relevant.

This produces an operational problem:

> Which candidate should be selected?

Two simple rules are immediately available:

1. select the nearest affected state
2. select the earliest relevant state

Neither is sufficient.

---

# Nearest-State Rule

The nearest-state rule would select the earlier state closest to the current reasoning state.

For example:

~~~text
A
↓
B
↓
C
↓
D  ← Nearest affected state
↓
Current State
~~~

This minimizes recursive distance.

However, the nearest state may merely contain the visible consequence of a deeper structural problem.

If D depends on a problematic judgment in B, returning only to D may produce local correction without resolving the underlying structural condition.

Therefore:

> **Nearest Earlier State ≠ Necessarily Sufficient Target**

Recursive economy cannot be achieved by distance minimization alone.

---

# Earliest-State Rule

The opposite rule would return to the earliest plausible source.

For example:

~~~text
A  ← Earliest relevant state
↓
B
↓
C
↓
D
↓
Current State
~~~

This may capture deep assumptions and hidden dependencies.

However, it may also reopen reasoning that is already stable and irrelevant to the active trigger.

Possible consequences include:

- unnecessary recursive depth
- reopening stabilized findings
- increased branch generation
- additional reasoning cost
- delayed convergence

Therefore:

> **Earliest Relevant State ≠ Necessarily Appropriate Target**

The process requires a criterion other than historical distance.

---

# Minimal Sufficient Target

A more promising candidate is:

> Select the most limited earlier reasoning state that is sufficient to evaluate and resolve the current structural consequence.

This can be provisionally called:

> **Minimal Sufficient Recursive Target**

The logic is:

~~~text
Recursive Re-entry Required
        │
        ▼
Identify Candidate Earlier States
        │
        ├── State A
        ├── State B
        ├── State C
        └── State D
        │
        ▼
Which Candidate Is Sufficient
for Resolution?
        │
        ▼
Select the Minimum Sufficient Target
~~~

This candidate introduces an important principle:

> **Recursive examination should not reopen more earlier reasoning than necessary.**

This is consistent with the selective nature of recursive reasoning.

---

# Counter-Test of Minimal Sufficiency

Minimal Sufficiency initially appears attractive because it limits unnecessary recursion.

However, counter-testing exposes a weakness.

Consider:

~~~text
A — Hidden Assumption
        ↓
B — Interpretation
        ↓
C — Finding
        ↓
D — Current Problem
~~~

Suppose returning to C allows the immediate problem at D to be locally corrected.

C therefore appears sufficient.

However, if C remains dependent on a problematic Hidden Assumption at A, the same structural problem may remain embedded in the reasoning architecture.

The local problem may be repaired without resolving the deeper condition that produced it.

Therefore:

> **Local Resolution Sufficiency ≠ Structural Sufficiency**

A target cannot be judged sufficient merely because it permits an immediate correction.

It must support adequate evaluation of the structural consequence.

---

# Minimal Structurally Sufficient Target

The counter-test requires revision of the initial candidate.

The stronger formulation is:

> **Select the most limited earlier reasoning state or state set that is structurally sufficient to evaluate and resolve the active recursive problem.**

This can be called:

> **Minimal Structurally Sufficient Target**

The priority relationship is important:

~~~text
Structural Sufficiency
        ↓
then
        ↓
Recursive Minimality
~~~

Minimality is subordinate to sufficiency.

The process should not choose a smaller target if doing so leaves a meaningful structural dependency unresolved.

At the same time, it should not automatically extend farther backward once sufficient structural basis has been reached.

---

# Structural Sufficiency

Structural Sufficiency means that the selected target provides an adequate basis for evaluating the active trigger without excluding an earlier dependency that could materially alter the judgment.

The relevant question is:

> Is this target sufficient not merely to explain the visible problem, but to evaluate the structural conditions that matter to its resolution?

Structural Sufficiency may require access to:

- underlying assumptions
- evidence interpretation
- dependency relations
- earlier distinctions
- structural conditions
- prior judgments

but only when they remain consequential to the active recursive problem.

This preserves selectivity.

---

# Target Selection Judgment Dimensions

The operational examination suggests three principal judgment dimensions for Recursive Target Selection:

1. Relevance
2. Structural Sufficiency
3. Recursive Economy

These dimensions are related but not interchangeable.

---

# Target Dimension 1

## Relevance

A candidate earlier state must be materially related to the active structural consequence.

The question is:

> Does this earlier reasoning state contain information, relations, assumptions, or judgments that may materially affect resolution of the current trigger?

If not, the state should not become part of the recursive target merely because it is historically connected to the reasoning trajectory.

Therefore:

> **Historical connection ≠ Target relevance**

---

# Target Dimension 2

## Structural Sufficiency

A relevant state must also be sufficient for adequate recursive evaluation.

The question is:

> If recursive examination begins here, does the selected target provide enough structural basis to evaluate the active problem without omitting a materially consequential earlier dependency?

If not, backward access must be extended.

The mechanism becomes:

~~~text
Candidate Target
        │
        ▼
Structurally Sufficient?
        │
        ├── No
        │     ↓
        │  Extend Backward Access
        │
        └── Yes
              ↓
        Sufficiency Candidate
~~~

Structural Sufficiency prevents premature target selection.

---

# Target Dimension 3

## Recursive Economy

Once Structural Sufficiency is reached, the process must determine whether further backward extension is still warranted.

The question is:

> Would extending the target farther backward be reasonably expected to produce meaningful structural change in the current recursive judgment?

If the answer is no, further extension becomes unnecessary.

The mechanism becomes:

~~~text
Structurally Sufficient Candidate
        │
        ▼
Would Further Backward Extension
Likely Produce Meaningful
Structural Change?
        │
        ├── Yes
        │     ↓
        │  Extend / Re-evaluate Target
        │
        └── No
              ↓
        Select Recursive Target
~~~

This applies an existing Mission 002 judgment:

> **Expected Structural Change**

to Recursive Target Selection.

It does not create a new independent requirement.

---

# Expected Structural Change in Target Selection

Expected Structural Change functions as a limiting judgment.

Once a candidate target is structurally sufficient, the process asks whether moving farther backward is likely to materially change:

- interpretation
- dependency assessment
- structural judgment
- preservation decision
- revision requirement

If further backward access is unlikely to change any of these meaningfully, recursive expansion should stop.

Therefore:

> **A target should be extended only while additional backward access remains structurally consequential.**

This protects against unnecessary historical reopening.

---

# Candidate Target Mechanism

The Target Selection mechanism can now be represented as:

~~~text
Recursive Re-entry Required
        │
        ▼
Identify Earlier States
Relevant to Structural Consequence
        │
        ▼
Candidate Recursive Target
        │
        ▼
Structurally Sufficient?
        │
        ├── No
        │     ↓
        │  Extend Backward Access
        │     ↓
        │  Re-evaluate Candidate
        │
        └── Yes
              ↓
Would Further Backward Extension
Likely Produce Meaningful
Structural Change?
        │
        ├── Yes
        │     ↓
        │  Extend / Re-evaluate
        │
        └── No
              ↓
        Select Recursive Target
~~~

The target is therefore neither automatically nearest nor automatically earliest.

It is selected according to:

> **Resolution relevance + Structural Sufficiency + Recursive Economy**

---

# Counter-Test of the Single-Target Assumption

The mechanism above still contains an implicit assumption:

> Recursive Target = one earlier reasoning state.

This assumption also requires testing.

Consider:

~~~text
Assumption A ─────────┐
                      │
                      ▼
                  Finding C
                      ▲
                      │
Evidence Path B ──────┘
~~~

Suppose the active trigger concerns Finding C.

Adequate evaluation may require simultaneous access to:

- Assumption A
- Evidence Path B

Neither state alone may be structurally sufficient.

If so, requiring a single target would artificially simplify the recursive structure.

Therefore:

> **Recursive Target need not always be a single state.**

---

# Target Set

The target concept can be extended without creating a new operational branch.

A Recursive Target may consist of:

> **a reasoning state or a structurally related state set**

when multiple earlier elements are jointly necessary for adequate evaluation.

The mechanism therefore becomes:

~~~text
Candidate Earlier Reasoning
        │
        ├── Single State
        │
        └── State Set
              ↓
Structurally Sufficient for Resolution?
              ↓
Recursive Target
~~~

This does not create a separate Target-Set mechanism.

It is a variation within Target Selection.

---

# Single Target vs. Target Set

The distinction can be stated as follows.

## Single Target

A single earlier reasoning state contains sufficient structural basis for recursive evaluation.

## Target Set

Multiple earlier reasoning states must be jointly accessed because no single state adequately represents the relevant structural conditions.

The selection criterion remains unchanged:

> **Minimal Structural Sufficiency**

The difference concerns only the form of the selected target.

---

# Target Is Not the Entire Recursive Scope

At this point, an important boundary becomes visible.

Selecting a Recursive Target does not determine the complete scope of recursive examination.

Suppose the selected target is:

> Finding C

Once C is examined, the process may discover that C depends on:

> Interpretation B

and B may depend on:

> Assumption A

The target therefore determines:

> **where recursive examination begins**

but not necessarily:

> **where recursive examination ends**

This produces the next operational problem.

---

# Target Selection vs. Depth Selection

The distinction can initially be represented as:

~~~text
Recursive Re-entry Required
        │
        ▼
TARGET SELECTION
        │
        │  Where should recursive examination begin?
        ▼
Recursive Target
        │
        ▼
DEPTH SELECTION
        │
        │  How far should recursive examination propagate?
        ▼
Recursive Examination Scope
~~~

This suggests that Target and Depth are distinct judgments.

However, whether they remain genuinely distinct after operational examination requires further testing.

That question is addressed in the next part of this document.

---

# Provisional Target Definition

At this stage, Recursive Target can be provisionally defined as:

> **The minimally extended earlier reasoning state or state set that provides a structurally sufficient and resolution-relevant entry point for recursive examination.**

This definition contains four important elements:

- earlier reasoning access
- resolution relevance
- structural sufficiency
- bounded recursive expansion

It deliberately does not specify the full backward extent of examination.

That is the responsibility of Recursive Depth Selection.

---

# Target Selection Failure Modes

The Target Selection mechanism exposes several provisional failure modes.

## Failure Mode 1 — Nearest-State Bias

The process selects the closest affected state because it minimizes recursive distance.

Possible consequence:

- deeper structural dependency remains unresolved

## Failure Mode 2 — Earliest-State Bias

The process returns to the earliest plausible origin.

Possible consequence:

- unnecessary reopening of stable reasoning
- excessive recursive scope

## Failure Mode 3 — Local Sufficiency Error

A target is considered sufficient because it permits immediate correction.

Possible consequence:

- hidden structural condition remains active

## Failure Mode 4 — Single-Target Reduction

A multi-dependency problem is forced into one earlier state.

Possible consequence:

- incomplete recursive evaluation

## Failure Mode 5 — Unbounded Target Expansion

Backward access continues after Structural Sufficiency has already been reached.

Possible consequence:

- unnecessary reasoning cost
- branch proliferation
- delayed convergence

These failure modes are not yet formal protocol validation criteria.

They are operational risks exposed by the current examination.

---

# Target Selection — Current Assessment

The examination supports the following provisional finding:

> Recursive Target Selection should not be based on historical proximity or causal priority alone.

Instead:

> The reasoning process should select the most limited earlier reasoning state or state set that is structurally sufficient to evaluate and resolve the active recursive problem.

Further backward extension remains justified only while it is reasonably expected to produce meaningful structural change.

This yields the candidate relationship:

~~~text
Resolution Relevance
        +
Structural Sufficiency
        +
Recursive Economy
        ↓
Minimal Structurally Sufficient
Recursive Target / Target Set
~~~

This Target mechanism is sufficiently stable to support examination of Recursive Depth.

---

# Transition to Recursive Depth

Once a Recursive Target has been selected, the reasoning process has established:

> **where recursive examination should begin.**

However, the selected target may itself depend on earlier reasoning.

The next operational question is therefore:

> **How far should recursive examination propagate beyond the selected target?**

This is the responsibility of Recursive Depth Selection.

---

# End of Part 1/3
