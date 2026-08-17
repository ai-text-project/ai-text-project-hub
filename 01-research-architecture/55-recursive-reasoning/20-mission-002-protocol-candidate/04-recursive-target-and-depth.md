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


# Recursive Depth Selection

Once a Recursive Target has been selected, recursive examination can begin.

However, Target Selection alone does not determine how much earlier reasoning must be reconsidered.

A selected target may depend on:

- earlier assumptions
- earlier interpretations
- earlier evidence relations
- earlier structural judgments
- earlier dependency configurations

Some of these dependencies may be necessary for adequate evaluation.

Others may be historically connected but structurally irrelevant to the active trigger.

Therefore:

> **Recursive Target Selection does not determine Recursive Depth automatically.**

A separate operational judgment is required.

---

# Initial Depth Candidate

The simplest candidate rule is:

> Continue backward examination until the problem is resolved.

The mechanism would appear as:

~~~text
Recursive Target
        │
        ▼
Begin Examination
        │
        ▼
Problem Resolved?
        │
        ├── No
        │     ↓
        │  Examine Earlier Reasoning
        │
        └── Yes
              ↓
        Stop
~~~

This appears reasonable.

However, the meaning of:

> **resolved**

is too ambiguous to serve as a sufficient Depth criterion.

---

# Resolution Ambiguity

A recursive problem may appear resolved at several different levels.

For example:

~~~text
A — Assumption
        ↓
B — Interpretation
        ↓
C — Finding  ← Recursive Target
~~~

Suppose C is reconsidered.

The immediate contradiction affecting C may be explained by B.

At that point the process could claim:

> The problem has been explained.

However, B may itself depend on an assumption at A that materially affects whether B should be preserved.

Therefore:

> **Explanatory Resolution ≠ Structural Resolution**

A problem may be explainable before its relevant structural dependencies have been adequately examined.

This means that:

> **Problem Resolved?**

is too weak as the sole stopping criterion for Recursive Depth.

---

# Depth Is Not Historical Distance

Another simple interpretation would define Depth numerically.

For example:

~~~text
Target C
    ↓
Depth 1 → B
    ↓
Depth 2 → A
~~~

This representation can be useful descriptively.

However, it does not provide the operational principle for deciding whether Depth 1 or Depth 2 is appropriate.

The number of backward steps is a consequence of the reasoning structure.

It is not the governing judgment.

Therefore:

> **Recursive Depth ≠ Historical Distance**

Recursive Depth should instead be understood in relation to the structural dependencies required for adequate recursive evaluation.

---

# Dependency-Relevant Depth

A stronger candidate is:

> Extend recursive examination only through earlier dependencies that remain relevant to evaluating the selected target and the active trigger.

This can be provisionally called:

> **Dependency-Relevant Depth**

The mechanism becomes:

~~~text
Selected Recursive Target
        │
        ▼
Examine Target
        │
        ▼
Is an Earlier Dependency
Required for Adequate Evaluation?
        │
        ├── No
        │     ↓
        │  Stop Depth Expansion
        │
        └── Yes
              ↓
        Examine Relevant Dependency
              │
              ▼
        Re-evaluate Sufficiency
~~~

This is more selective than reopening the entire earlier reasoning trajectory.

---

# Selective Recursive Depth

The emerging mechanism is consistent with the Selective Depth property identified during Mission 001.

Operationally, Selective Recursive Depth means:

> **Recursive examination is extended only while additional backward examination remains structurally consequential to the active recursive problem.**

This can be represented as:

~~~text
Depth 0
Target Only
        │
        ▼
Relevant Unresolved Dependency?
        │
        ├── No → Stop
        │
        └── Yes
              ↓
Depth 1
Relevant Earlier Dependency
        │
        ▼
Further Structurally Consequential
Dependency?
        │
        ├── No → Stop
        │
        └── Yes
              ↓
Depth 2
        │
        ▼
...
~~~

Depth therefore emerges from the dependency structure encountered during recursive examination.

It need not be fully determined before re-entry begins.

---

# Dynamic Depth

This produces an important operational property:

> **Recursive Depth may be dynamically determined during recursive examination.**

The process begins at the selected Recursive Target.

It then evaluates whether adequate judgment requires access to an earlier dependency.

If yes, Depth expands.

After that dependency is examined, the process evaluates again.

Depth is therefore not necessarily:

> selected once before recursive examination begins.

Instead, it may be:

> **progressively bounded through repeated sufficiency judgments.**

This distinguishes Recursive Depth from a predefined search radius.

---

# Structural Sufficiency in Depth Selection

Structural Sufficiency, already used in Target Selection, also appears in Depth Selection.

However, its function is slightly different.

In Target Selection, Structural Sufficiency asks:

> Does this state or state set provide an adequate entry point for recursive examination?

In Depth Selection, it asks:

> Has recursive examination now covered enough relevant earlier reasoning to support an adequate structural judgment?

Thus:

~~~text
TARGET
Structural Sufficiency of Entry Point

DEPTH
Structural Sufficiency of Examination Extent
~~~

The same higher-level judgment principle appears in two different operational locations.

---

# Initial Depth Stop Condition

A provisional Depth Stop Condition can therefore be stated as:

> Stop backward expansion when the current recursive examination is structurally sufficient for the active problem.

However, as with Target Selection, Structural Sufficiency alone requires counter-testing.

---

# Counter-Test of Structural Sufficiency

Suppose the process has examined:

~~~text
Target C
    ↓
Dependency B
~~~

and concludes that B sufficiently explains and supports the judgment concerning C.

The examination appears structurally sufficient.

However, B itself depends on A:

~~~text
A — Hidden Assumption
        ↓
B
        ↓
C
~~~

If examining A could materially change the judgment concerning B and therefore C, stopping at B would be premature.

Thus the process must distinguish:

> **Current Structural Sufficiency**

from:

> **Stable Structural Sufficiency under plausible deeper examination**

This requires an additional judgment.

---

# Expected Structural Change

The same judgment that constrained Target Selection can be applied to Depth Selection:

> **Would deeper backward examination be reasonably expected to produce meaningful structural change in the current recursive judgment?**

The resulting mechanism is:

~~~text
Current Recursive Depth
        │
        ▼
Structurally Sufficient?
        │
        ├── No
        │     ↓
        │  Extend Depth
        │
        └── Yes
              ↓
Would Deeper Examination
Likely Produce Meaningful
Structural Change?
        │
        ├── Yes
        │     ↓
        │  Extend Depth
        │
        └── No
              ↓
        Stop Depth Expansion
~~~

This prevents Structural Sufficiency from becoming a premature stop condition.

---

# Local Stop Judgment

Expected Structural Change previously appeared as part of the broader Stop Judgment governing reasoning convergence.

Within Recursive Depth Selection, it performs a more local function.

The question is not:

> Should the entire reasoning process stop?

Instead:

> **Should backward recursive examination stop expanding?**

Therefore, Recursive Depth contains a localized Stop Judgment.

This does not create a new independent Stop mechanism.

It is an application of an existing judgment principle to the recursive scope problem.

---

# Depth Extension Condition

Depth should continue expanding when at least one earlier dependency remains both:

1. relevant to the active recursive problem
2. reasonably capable of producing meaningful structural change

This can be represented as:

~~~text
Earlier Dependency
        │
        ▼
Relevant to Active Recursive Problem?
        │
        ├── No
        │     ↓
        │  Do Not Extend
        │
        └── Yes
              ↓
Could Examination Materially
Change Current Structural Judgment?
        │
        ├── No
        │     ↓
        │  Do Not Extend
        │
        └── Yes
              ↓
        Extend Recursive Depth
~~~

This keeps recursive examination selective.

---

# Depth Termination Condition

Conversely, backward expansion can terminate when:

- current recursive examination is structurally sufficient
- no unresolved earlier dependency remains materially relevant
- deeper examination is unlikely to produce meaningful structural change

The relationship is:

~~~text
Structural Sufficiency
        +
No Materially Unresolved
Earlier Dependency
        +
Low Expected Structural Change
        ↓
Stop Recursive Depth Expansion
~~~

These should not be interpreted as mechanically independent binary tests.

They represent judgment dimensions supporting a context-sensitive stopping decision.

---

# Anti-Shallow-Recursion Function

Depth Selection protects against stopping too early.

Without adequate Depth judgment, the reasoning process may:

- revisit the visible finding only
- explain the immediate contradiction
- preserve hidden assumptions
- leave structural dependencies unexamined
- falsely conclude that recursive reconsideration is complete

This can produce:

> **Shallow Recursive Resolution**

The reasoning process technically re-enters earlier reasoning but fails to examine enough of the dependency structure to support reliable reconsideration.

Therefore:

> **Re-entry alone does not guarantee adequate recursion.**

Depth must be sufficient relative to the active structural problem.

---

# Anti-Deep-Recursion Function

The opposite failure is unrestricted depth.

Once recursive examination begins, every earlier dependency may appear connected to another earlier dependency.

Without a stopping mechanism, the process may repeatedly expand:

~~~text
Target
  ↓
Dependency
  ↓
Earlier Dependency
  ↓
Earlier Assumption
  ↓
Earlier Context
  ↓
...
~~~

Possible consequences include:

- recursive overextension
- reopening stable reasoning
- excessive reasoning cost
- branch proliferation
- convergence delay
- loss of current-objective focus

Therefore:

> **The existence of an earlier dependency does not by itself justify deeper recursive examination.**

The dependency must remain structurally consequential to the active problem.

---

# Selective Depth as Balance

Recursive Depth therefore regulates two opposite risks:

~~~text
Too Shallow
    │
    ▼
Hidden Structural Dependency
Remains Unexamined

        versus

Too Deep
    │
    ▼
Unnecessary Historical
Reasoning Reopened
~~~

Selective Depth operates between these extremes.

The objective is not:

> minimum depth

or:

> maximum confidence through maximum depth.

The objective is:

> **sufficient recursive depth with bounded structural relevance.**

---

# Recursive Depth Is Trigger-Relative

Depth cannot be determined independently of the trigger that initiated recursive examination.

The same earlier target may require different Depth under different triggers.

For example:

~~~text
Target C

Trigger X
    ↓
Only C requires reconsideration
    ↓
Shallow Depth

Trigger Y
    ↓
C depends on B
and B depends on A
in a structurally relevant way
    ↓
Deeper Depth
~~~

Therefore:

> **Recursive Depth is relative to the active structural consequence, not intrinsic to the target itself.**

A target does not possess a fixed correct Depth.

---

# Recursive Depth Is Context-Sensitive

Depth judgment may depend on:

- the active trigger
- the selected target
- dependency structure
- current objective
- reasoning phase
- stability of earlier findings
- credibility of newly exposed evidence
- expected structural consequence
- unresolved assumptions

Accordingly:

> **Recursive Depth cannot be adequately operationalized as a universal fixed number of backward steps.**

The operational structure identifies the relevant judgment locations.

It does not eliminate context-sensitive reasoning.

---

# Target–Depth Relationship

Having developed Target and Depth separately, the next question is whether they are genuinely distinct operational judgments.

The initial distinction was:

> **Target = Where**

and:

> **Depth = How far**

However, this distinction must be tested because both operate over earlier reasoning states.

---

# Counter-Test of Target–Depth Separation

Consider:

~~~text
A — Assumption
↓
B — Interpretation
↓
C — Finding
↓
D — Current State
~~~

Suppose C is selected as the Recursive Target.

Recursive examination then proceeds:

~~~text
Target C
    ↓
B
    ↓
A
~~~

If examination eventually reaches A, one could argue:

> Was A actually the true Recursive Target?

If so, Target and Depth might merely be two descriptions of the same backward-selection problem.

This possibility requires direct comparison.

---

# Case 1 — Same Target, Shallow Depth

~~~text
A
↓
B
↓
C ← Target
~~~

C is examined.

No earlier dependency is structurally consequential to the active trigger.

Therefore:

> Target = C

and:

> Depth = Target only

The recursive entry point is C.

The examination does not propagate farther backward.

---

# Case 2 — Same Target, Deeper Depth

~~~text
A
↓
B
↓
C ← Target
~~~

C is examined.

Evaluation exposes a materially relevant dependency on B.

B then exposes a materially relevant assumption at A.

Therefore:

> Target = C

while:

> Depth extends through B to A.

The entry point remains unchanged.

The propagation extent changes.

---

# Target ≠ Depth

The comparison shows that:

> **Target Selection determines the entry point of recursive examination.**

while:

> **Depth Selection determines the propagation extent of recursive examination after entry.**

Therefore:

> **Target ≠ Depth**

The fact that recursive examination eventually reaches an earlier state does not retroactively make that state the original target.

This supports maintaining Target and Depth as distinct operational judgments.

---

# Target Influences Depth

Although Target and Depth are distinct, they are not independent.

Selecting a different target can alter the required Depth.

For example:

~~~text
Option 1

Target C
    ↓
B
    ↓
A

Required Depth = deeper


Option 2

Target B
    ↓
A

Required Depth = shallower
~~~

The same structural problem may therefore produce different propagation requirements depending on the selected entry point.

Thus:

> **Target Selection constrains Depth Selection.**

---

# Depth Can Challenge Target

The relationship also operates in the opposite direction.

Suppose a selected target repeatedly requires unexpectedly extensive backward propagation.

This may indicate that the selected target was not actually the most appropriate structurally sufficient entry point.

The process may then need to reconsider Target Selection.

For example:

~~~text
Selected Target C
        ↓
Depth expands to B
        ↓
Depth expands to A
        ↓
Further earlier access still required
        ↓
Question:
Was C an adequate Target?
~~~

Thus:

> **Depth examination can expose inadequacy in Target Selection.**

This creates reciprocal constraint.

---

# Operationally Distinct / Reciprocally Constraining

The relationship can therefore be summarized as:

> **Recursive Target Selection and Recursive Depth Selection are operationally distinct but reciprocally constraining judgments.**

They should not be collapsed into one undifferentiated scope decision.

However, they should also not be treated as unrelated mechanisms.

The relationship is:

~~~text
Target Selection
        │
        ▼
Initial Recursive Entry Point
        │
        ▼
Depth Selection
        │
        ▼
Propagation Examination
        │
        └───────────────┐
                        │
        Target Adequacy Challenged?
                        │
                        ├── No
                        │     ↓
                        │ Continue / Stop Depth
                        │
                        └── Yes
                              ↓
                        Re-evaluate Target
~~~

This reciprocal relationship supports externalizing Target and Depth within the same operational asset.

---

# Why Target and Depth Should Remain in One Asset

Separating Target and Depth into independent assets would preserve their conceptual distinction.

However, it would weaken representation of their operational interaction.

Target affects Depth.

Depth can challenge Target.

Therefore, the relevant mechanism is not simply:

~~~text
Target
then
Depth
~~~

but:

~~~text
Target
  ↓
Depth
  ↓
Possible Target Re-evaluation
  ↓
Depth Recalibration
~~~

The judgments remain distinct while participating in one recursive scope-regulation mechanism.

Accordingly:

> **One asset with explicit internal distinction is more appropriate than two isolated assets.**

---

# Integrated Target–Depth Mechanism

The mechanism developed so far can be represented as:

~~~text
Recursive Re-entry Required
        │
        ▼
Identify Earlier State / State Set
Relevant to Structural Consequence
        │
        ▼
Candidate Recursive Target
        │
        ▼
Structurally Sufficient
as Entry Point?
        │
        ├── No
        │     ↓
        │  Extend / Re-evaluate
        │  Target Scope
        │
        └── Yes
              ↓
Would Earlier Target Extension
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
              │
              ▼
        Begin Recursive Examination
              │
              ▼
Is Current Examination
Structurally Sufficient?
        │
        ├── No
        │     ↓
        │  Identify Relevant
        │  Earlier Dependency
        │     ↓
        │  Extend Depth
        │
        └── Yes
              ↓
Would Deeper Examination
Likely Produce Meaningful
Structural Change?
        │
        ├── Yes
        │     ↓
        │  Extend Depth
        │
        └── No
              ↓
        Stop Depth Expansion
~~~

This is the central operational mechanism of this document.

---

# Recursive Scope

Target and Depth together establish what can be called the:

> **Recursive Examination Scope**

This refers to the bounded portion of earlier reasoning selected for active reconsideration.

The relationship is:

~~~text
Recursive Target
        +
Recursive Depth
        ↓
Recursive Examination Scope
~~~

This term is descriptive.

It does not introduce a new independent operational requirement.

Its purpose is to represent the combined result of Target and Depth judgments.

---

# Recursive Scope Is Not Historical Reconstruction

The resulting Recursive Examination Scope should not be interpreted as a requirement to reconstruct every reasoning state between the target and the deepest dependency.

Only structurally relevant reasoning needs active reconsideration.

For example:

~~~text
Earlier Reasoning Structure

A ────── relevant
│
B ────── irrelevant branch
│
C ────── relevant
│
D ────── current target
~~~

Recursive examination may require:

~~~text
D → C → A
~~~

without reopening B if B is not structurally consequential to the active trigger.

Therefore:

> **Recursive Depth follows structural dependency, not necessarily chronological continuity.**

This preserves selective recursion.

---

# Branch Selectivity

Earlier reasoning may contain branching dependencies.

For example:

~~~text
          A
         / \
        B   C
         \ /
          D ← Target
~~~

A trigger affecting D may require reconsideration of B but not C.

Alternatively, it may require both.

Depth therefore has both:

- extent
- branch selectivity

However, branch selectivity does not require a separate operational mechanism at this stage.

It is governed by the same criterion:

> **Is the earlier dependency structurally consequential to the active recursive problem?**

Thus:

> **Depth is selective across both distance and dependency branches.**

---

# Counter-Test: Backward-Only Assumption

The mechanism developed so far treats Recursive Depth as backward examination.

This assumption requires testing.

Suppose recursive examination reaches Finding B and B is revised:

~~~text
A
↓
B ← Revised
↓
C
↓
D
↓
Current State
~~~

The revision of B may alter:

- C
- D
- the current reasoning state

This appears to require forward examination.

At first glance, Recursive Depth might therefore need to include both backward and forward propagation.

---

# Boundary Analysis of Forward Propagation

The forward effect is real.

However, its operational responsibility differs from Recursive Depth.

Depth asks:

> **How far backward must examination propagate to establish an adequate basis for recursive judgment?**

Forward propagation asks:

> **Once an earlier finding has been preserved or revised, how should the consequence of that judgment propagate through subsequent reasoning?**

These are different problems.

The first concerns:

> recursive examination scope.

The second concerns:

> consequence propagation after Preserve / Revise judgment.

Therefore:

> **Forward Propagation ≠ Recursive Depth**

Forward propagation should not be absorbed into the current mechanism merely because it arises after recursive examination.

---

# Boundary Decision on Forward Propagation

The current document therefore limits Recursive Depth to:

> **the backward extent of structurally relevant examination required to establish an adequate basis for subsequent recursive judgment.**

Possible forward consequences are held for downstream operational analysis.

At this stage, they are not assigned definitively to a specific later mechanism.

They are simply excluded from the responsibility of Recursive Target and Depth.

This prevents Responsibility Mixing.

---

# Revised Depth Definition

Recursive Depth can now be provisionally defined as:

> **The dynamically bounded extent to which recursive examination propagates through structurally relevant earlier dependencies beyond the selected Recursive Target.**

Depth expands while:

- relevant unresolved dependencies remain
- current examination is structurally insufficient
- deeper examination is reasonably expected to produce meaningful structural change

Depth stops when:

- current examination is structurally sufficient
- no materially unresolved earlier dependency remains
- additional backward examination has low expected structural consequence

---

# Revised Target–Depth Relationship

The combined relationship can be stated as:

> **Target selects the structurally sufficient entry point or entry set for recursive examination.**

> **Depth dynamically determines the structurally consequential backward extent of examination after entry.**

Together they establish:

> **a bounded Recursive Examination Scope.**

Their relationship remains:

> **Operationally Distinct / Reciprocally Constraining**

---

# Minimal Operational Form

The Target–Depth mechanism can be compressed into the following form:

~~~text
Recursive Re-entry Required
        │
        ▼
Where should examination begin?
        │
        ▼
Minimal Structurally Sufficient
Target / Target Set
        │
        ▼
Begin Recursive Examination
        │
        ▼
Is Earlier Dependency
Still Structurally Consequential?
        │
        ├── Yes
        │     ↓
        │  Extend Depth
        │     ↓
        │  Re-evaluate
        │
        └── No
              ↓
Would Deeper Examination Likely
Produce Meaningful Structural Change?
        │
        ├── Yes → Extend Depth
        │
        └── No  → Stop Depth Expansion
~~~

This minimal form should be interpreted as an operational scaffold rather than a deterministic algorithm.

---

# Depth Selection — Current Assessment

The examination supports the following finding:

> Recursive Depth should not be predetermined as a fixed historical distance.

Instead:

> Recursive examination should propagate dynamically through earlier dependencies only while those dependencies remain structurally consequential to the active trigger.

The stopping judgment depends on:

- Structural Sufficiency
- unresolved dependency relevance
- Expected Structural Change

This yields:

~~~text
Dependency Relevance
        +
Structural Sufficiency
        +
Expected Structural Change
        ↓
Selective / Dynamically Bounded
Recursive Depth
~~~

The Depth mechanism is therefore sufficiently stable to support final Responsibility and Placement assessment.

---

# Target–Depth Current Assessment

The examination also supports:

> **Target ≠ Depth**

Target determines:

> **where recursive examination begins**

Depth determines:

> **how far structurally relevant examination propagates after entry**

However:

> Target influences required Depth.

and:

> Depth can expose inadequacy in Target Selection.

Therefore:

> **Target Selection and Depth Selection are Operationally Distinct / Reciprocally Constraining.**

This relationship supports their combined externalization within:

`04-recursive-target-and-depth.md`

---

# Transition to Responsibility Fit

The Target and Depth mechanisms have now both undergone:

- candidate formation
- counter-testing
- revision
- boundary examination

No additional Target or Depth variable is required at this stage.

The remaining question before externalization is:

> **Can the combined Target / Depth mechanism remain within the responsibility of this asset without absorbing responsibilities belonging to 03 or 05?**

This is addressed in the final part of this document.

---

# End of Part 2/3

