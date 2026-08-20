# Examination Boundary

**Research Area:** Recursive Reasoning  
**Mission:** 003 — Independent Examination  
**Asset:** 01 — Examination Boundary  
**Status:** Current Baseline  
**Upstream Asset:** `00-mission-definition.md`  
**Downstream Assets:** `02-independent-instance-protocol.md`, `03-examination-materials.md`, `04-examination-procedure.md`

---

# Purpose

This document defines the boundary conditions that must remain protected for Mission 003 to produce a meaningful Independent Examination of the Recursive Reasoning Protocol Candidate.

Mission 003 does not begin by assuming that the Protocol Candidate will be validated.

It begins by asking whether the Protocol Candidate formed and internally examined in Mission 002 remains structurally coherent when exposed to an independent source of examination.

For that examination to generate meaningful evidence, independence alone is insufficient.

An examination may be highly independent while failing to examine the actual research object.

Conversely, an examination may expose the research object in great detail while conditioning the evaluator so strongly that the resulting judgment can no longer be treated as meaningfully independent.

The examination must therefore protect multiple boundaries simultaneously.

The core structure established for this Mission is:

```text
VALID INDEPENDENT EXAMINATION
                │
     ┌──────────┼──────────┐
     ▼          ▼          ▼
   Object     Judgment   Responsibility
   Validity   Independence  Integrity
```

These three conditions define the Examination Boundary.

They do not yet define the Independent Instance, examination materials, or examination procedure.

Those responsibilities belong to downstream assets.

---

# Primary Boundary Question

The central question of this asset is:

> **What must remain protected for the resulting examination evidence to retain a meaningful claim to independence while still examining the actual Protocol Candidate?**

This question is narrower than the Mission 003 research question.

Mission 003 asks:

> Can the Protocol Candidate remain structurally coherent under independent examination?

This document asks:

> Under what boundary conditions can such an examination legitimately be treated as a meaningful Independent Examination?

---

# Boundary Responsibility

The responsibility of this asset is to define required properties.

It does not operationalize those properties.

Therefore:

```text
01 — Examination Boundary
        ↓
What must remain protected?
```

is distinct from:

```text
02 — Independent Instance Protocol
        ↓
How is an independent
examination source established?
```

and:

```text
03 — Examination Materials
        ↓
What information is exposed?
```

and:

```text
04 — Examination Procedure
        ↓
How is the examination conducted?
```

This separation is necessary because operational choices should be justified by explicit examination boundaries rather than defining those boundaries retrospectively.

---

# Core Boundary Structure

A meaningful Independent Examination requires three analytically distinct conditions:

1. **Object Validity**
2. **Judgment Independence**
3. **Responsibility Integrity**

These conditions are related but not interchangeable.

A failure in any one of them may weaken the evidential meaning of the examination even when the other two remain intact.

Conceptually:

```text
Object Validity
        +
Judgment Independence
        +
Responsibility Integrity
        ↓
Meaningful Independent Examination
```

This does not imply that the three conditions have equal weight in every examination.

It means that each protects a different failure direction.

---

# 1. Object Validity

## Definition

Object Validity requires that the examination meaningfully addresses the actual research object.

For Mission 003, that research object is the Recursive Reasoning Protocol Candidate established in Mission 002.

The examination must therefore expose enough of the Protocol Candidate for the independent reasoning instance to examine the structure that Mission 003 claims is being examined.

Conceptually:

```text
Research Object
        ↓
Sufficient Representation
        ↓
Independent Examination
```

If the representation is insufficient, the examination may remain independent while ceasing to be an examination of the intended object.

---

# Why Object Validity Is Necessary

Independence can be artificially increased by withholding information.

For example:

```text
Very Little Information
        ↓
Very Little Formation Influence
        ↓
Apparently High Independence
```

However:

```text
Very Little Information
        ↓
Insufficient Access
to Protocol Candidate
        ↓
Object Examination Failure
```

Therefore:

> **Less exposure does not automatically produce stronger examination evidence.**

The independent reasoning instance must receive sufficient access to the research object to form a judgment about that object.

---

# Object Validity Is Not Judgment Independence

Object Validity and Judgment Independence can fail independently.

For example:

```text
Actual Protocol Candidate
sufficiently represented
        ↓
Object Validity
        ✓
```

while simultaneously:

```text
Formation History
+
Expected Interpretation
+
Leading Guidance
        ↓
Judgment Independence
        ✗
```

The reverse is also possible:

```text
Formation Influence
minimized
        ↓
Judgment Independence
        ✓
```

while:

```text
Protocol Candidate
insufficiently represented
        ↓
Object Validity
        ✗
```

Therefore the two conditions must remain analytically distinct.

---

# Representation Fidelity

Object Validity includes the requirement that the representation presented for examination remains sufficiently faithful to the intended research object.

For example:

```text
Canonical Protocol Candidate
        ↓
Highly Compressed Summary
        ↓
Independent Examination
```

may unintentionally substitute a secondary representation for the actual Protocol Candidate.

The problem is not that summaries are inherently invalid.

The problem is that:

```text
Examination of Summary
```

must not silently become equivalent to:

```text
Examination of Canonical Protocol Candidate
```

without sufficient justification.

Representation Fidelity is therefore treated as a subordinate concern within Object Validity rather than as a separate fourth boundary.

---

# Object Substitution Risk

Object Substitution occurs when the material examined is materially different from the research object that the Mission claims was examined.

Potential forms include:

```text
Canonical Protocol
        ↓
Interpretive Summary
        ↓
Summary becomes
effective examination object
```

or:

```text
Protocol Candidate
        ↓
Selective Extraction
        ↓
Only preferred components
are examined
```

or:

```text
Protocol Candidate
        ↓
Reformulated Version
        ↓
Reformulation examined
instead of original object
```

The exact materials required to avoid Object Substitution are not defined here.

That responsibility belongs to `03-examination-materials.md`.

---

# Object Validity Boundary

The Object Validity boundary can therefore be expressed as:

> **The examination must expose the Protocol Candidate sufficiently and faithfully enough that the resulting judgment can reasonably be interpreted as a judgment about the intended research object.**

This asset does not determine the exact exposure mechanism.

It defines the requirement that the later material design must satisfy.

---

# 2. Judgment Independence

## Definition

Judgment Independence requires that the independent reasoning instance's examination not be overdetermined by reasoning inherited from the Protocol Candidate's original formation process or by guidance that precommits the expected outcome.

The central concern is not absolute informational isolation.

The concern is excessive conditioning.

Conceptually:

```text
Research Object Exposure
        ↓
Independent Reasoning
        ↓
Independent Judgment
```

should not silently become:

```text
Research Object
+
Formation Reasoning
+
Expected Interpretation
        ↓
Judgment Reconstruction
        ↓
Apparent Independent Judgment
```

---

# Independence Is Not Absence of Information

Judgment Independence does not require the reasoning instance to know nothing about the Protocol Candidate.

Such a requirement would conflict with Object Validity.

The problem is therefore not:

```text
Information
```

versus:

```text
No Information
```

The relevant distinction is:

```text
Information Necessary
to Examine the Object
```

versus:

```text
Information Likely to
Overdetermine Judgment
```

Mission 003 must preserve enough information for valid examination while limiting unnecessary transfer of formation-derived influence.

---

# Formation Leakage

Formation Leakage is a primary Failure Mode under Judgment Independence.

It occurs when the reasoning that originally produced the Protocol Candidate is transferred into the independent examination environment to such an extent that the evaluator may reconstruct rather than independently examine the prior judgment.

Conceptually:

```text
Mission 002
Formation Reasoning
        ↓
Transferred to
Independent Instance
        ↓
Original Reasoning
Reconstructed
        ↓
Apparent Confirmation
```

This differs from:

```text
Canonical Protocol Candidate
        ↓
Independent Instance
        ↓
Independent Examination
```

Formation Leakage therefore weakens the interpretation of resulting evidence as independently generated.

---

# Formation Leakage Is Not Binary

The presence of any historical context does not automatically invalidate independence.

Likewise, the absence of the complete Mission 002 history does not automatically guarantee independence.

The relevant question is whether formation-derived information materially conditions the independent judgment.

Therefore:

```text
Some Prior Context
        ≠
Automatic Independence Failure
```

and:

```text
Fresh Instance
        ≠
Automatic Independence Success
```

Judgment Independence must be assessed structurally rather than through a single superficial indicator.

---

# Judgment Steering

Judgment Steering is another Failure Mode under Judgment Independence.

It occurs when the examination framing itself suggests the preferred answer.

For example, an instruction structurally equivalent to:

```text
Confirm that the Protocol
remains coherent.
```

creates a different examination condition from:

```text
Examine whether the Protocol
remains coherent and identify
material reasons for preservation,
revision, or rejection.
```

The first framing contains an expected direction.

The second permits multiple outcomes.

Judgment Steering can therefore occur even when Formation History is completely withheld.

This is why Formation Leakage and Judgment Steering are distinct Failure Modes but belong under the same higher-order condition:

> **Judgment Independence**

---

# Outcome Precommitment

Mission 003 must not structure the examination around a required positive result.

The following direction is incompatible with the Mission boundary:

```text
Protocol Candidate
        ↓
Independent Examination
        ↓
Expected Confirmation
```

The intended structure is:

```text
Protocol Candidate
        ↓
Independent Examination
        ↓
Evidence
        ↓
Preserve?
Revise?
Reject?
Other?
```

The exact result categories remain provisional.

The important boundary is that the examination must remain capable of producing materially different outcomes.

---

# Human Steering

Human participation may also affect Judgment Independence.

Human involvement is not itself a boundary violation.

However, intervention becomes relevant when it materially redirects the independent reasoning instance's judgment.

For example:

```text
Independent Examination
        ↓
Human Correction
        ↓
Re-examination
        ↓
Human-preferred Direction
```

may no longer represent the same evidential relation as uninterrupted independent examination.

The exact permissible form of Human–AI interaction is not determined here.

The boundary requirement is simply:

> **Human involvement must not silently become a mechanism for overdetermining the independent judgment.**

Operational treatment belongs to later Mission assets.

---

# Judgment Independence Boundary

The Judgment Independence boundary can therefore be expressed as:

> **The examination must permit the reasoning instance to form a materially independent judgment rather than primarily reconstructing formation-derived reasoning or following an expected evaluative direction.**

This condition does not require absolute isolation.

It requires meaningful independence of judgment.

---

# 3. Responsibility Integrity

## Definition

Responsibility Integrity requires that Independent Examination remain distinguishable from other research responsibilities.

Most importantly:

```text
Independent Examination
        ≠
Protocol Redevelopment
```

Mission 003 may discover weaknesses requiring later revision.

However, detecting the need for revision and performing the revision are not the same responsibility.

---

# Why Responsibility Integrity Is Necessary

Suppose an independent reasoning instance receives the instruction:

```text
Examine the Protocol Candidate,
identify weaknesses,
and redesign the Protocol
to resolve them.
```

The resulting output may contain:

```text
Examination Evidence
        +
Revision Judgment
        +
New Protocol Design
```

These layers become difficult to separate.

The examination may then cease to provide a clean answer to:

> What did the independent examination reveal about the existing Protocol Candidate?

Instead, it begins answering:

> What Protocol would the independent reasoning instance prefer to construct?

These are different research questions.

---

# Examination Before Redevelopment

Mission 003 therefore preserves the sequence:

```text
Existing Protocol Candidate
        ↓
Independent Examination
        ↓
Evidence Preservation
        ↓
Assessment
```

before any separate responsibility transition toward:

```text
Revision
```

or:

```text
Redevelopment
```

If revision becomes necessary, that requirement should first be preserved as an examination result.

The Mission must not silently revise the object during the process and then treat the revised object as though it were the object originally examined.

---

# Responsibility Mixing

Responsibility Mixing occurs when different research functions become inseparable within the examination process.

Potential forms include:

```text
Examination
+
Protocol Development
```

```text
Independent Output
+
Post-hoc Interpretation
```

```text
Evidence Capture
+
Validation Claim Formation
```

or:

```text
Independent Judgment
+
Human Revision
```

These combinations are not necessarily forbidden across the broader research process.

The problem occurs when they are collapsed into a single evidential layer.

---

# Evidence–Interpretation Separation

A particularly important Responsibility Integrity requirement concerns the separation between:

```text
Independent Examination Output
```

and:

```text
Post-examination Interpretation
```

Mission 003 should preserve the ability to distinguish:

1. what the independent reasoning instance actually produced;
2. what was subsequently interpreted from that output;
3. what comparative assessment was later performed.

Conceptually:

```text
Original Protocol Candidate
        ↓
Independent Examination
        ↓
Independent Output
        ↓
Post-examination Assessment
```

These layers should remain traceable.

Otherwise later Validation judgments may rely on interpretations that are incorrectly attributed to the independent examination itself.

---

# Responsibility Integrity Boundary

The Responsibility Integrity boundary can therefore be expressed as:

> **Independent Examination must remain identifiable as an examination responsibility and must not silently absorb Protocol redevelopment, post-hoc interpretation, or other downstream research responsibilities into the evidence-producing process.**

This boundary protects evidential traceability.

---

# Three-condition Relationship

The three core conditions protect different properties.

```text
Object Validity
        ↓
Are we examining
the intended object?
```

```text
Judgment Independence
        ↓
Is the judgment meaningfully
independent of formation-derived
or outcome-directing influence?
```

```text
Responsibility Integrity
        ↓
Is the examination still
an examination rather than
a mixed research process?
```

Together:

```text
             VALID INDEPENDENT EXAMINATION
                          │
             ┌────────────┼────────────┐
             ▼            ▼            ▼
          Object       Judgment    Responsibility
          Validity     Independence   Integrity
             │            │            │
       Intended       Independent    Examination
       object is      judgment is    remains
       examined       protected      traceable
```

---

# Non-reducibility of the Three Conditions

The three conditions should not be collapsed into one another.

## Object Validity without Judgment Independence

```text
Correct Object
        ✓

Independent Judgment
        ✗
```

The intended object may be examined, but the judgment may be strongly conditioned.

---

## Judgment Independence without Object Validity

```text
Independent Judgment
        ✓

Correct Object
        ✗
```

The judgment may be independent, but it may concern an insufficient or substituted representation.

---

## Object Validity and Judgment Independence without Responsibility Integrity

```text
Correct Object
        ✓

Independent Judgment
        ✓

Examination / Redevelopment Separation
        ✗
```

The instance may independently understand the correct object but produce an evidentially mixed output.

Therefore:

> **No single condition can substitute for the other two.**

---

# Information Exposure Tension

Mission 003 contains an unavoidable tension.

```text
Too Little Exposure
        ↓
Object Validity weakens
```

while:

```text
Too Much Formation Exposure
        ↓
Judgment Independence may weaken
```

Therefore the goal is not maximum information restriction or maximum information disclosure.

The goal is:

> **Sufficient object exposure without unnecessary formation-derived conditioning.**

This relationship is central to the Mission 003 examination design.

It will become operationally relevant in:

- `02-independent-instance-protocol.md`;
- `03-examination-materials.md`;
- and `04-examination-procedure.md`.

This document does not resolve the tension operationally.

It defines the boundary that those later assets must respect.

---
