# Mission 001 — SOAR Selection Rationale

**Mission ID:** RRC-001  
**Target Domain:** SOAR Cognitive Architecture  
**Methodology:** Structural Representation Methodology  
**Operational Stage:** Representative Resource Curation  
**Responsible Role:** Representative Resource Curator  
**Document Type:** Selection Rationale  
**Status:** Resource Selection Frozen  
**Version:** v0.1

---

# Purpose

This document records the rationale for selecting the representative resources used in:

**Mission 001 — SOAR Representative Resource Curation**

The selected resources are:

1. **Primary Representative Resource**  
   John E. Laird, *Introduction to Soar* (2022)

2. **Complementary Representative Resource**  
   *The Soar Architecture*, Soar User's Manual

The purpose of this document is to explain why these resources form an appropriate observational input set for subsequent Structural Representation.

This document does not perform Structural Representation.

---

# Selection Objective

The objective of Representative Resource Curation is not to identify every useful publication about SOAR.

The objective is to identify a minimal set of public resources that:

- represents the overall architecture;
- provides sufficient architectural visibility;
- is publicly traceable;
- remains manageable as an observational input;
- supports subsequent Structural Representation;
- minimizes unnecessary source expansion.

The selection principle is therefore:

```text
Broad Discovery
        ↓
Consistent Evaluation
        ↓
Minimal Representative Set
        ↓
Transparent Selection Rationale
        ↓
Structural Representation Input
```

---

# Selection Decision

Mission 001 adopts a two-resource configuration:

```text
Primary Representative Resource

John E. Laird
Introduction to Soar
2022
        ↓
Research-Level Functional
Architectural Overview

        +

Complementary Representative Resource

The Soar Architecture
Soar User's Manual
        ↓
Official Architecture
Documentation

        ↓
Representative Resource Set
```

The two resources were selected because they provide different but complementary forms of architectural visibility.

---

# Rationale for Primary Resource Selection

## Resource

**John E. Laird — *Introduction to Soar* (2022)**

## Selection Role

**Primary Representative Resource**

## Primary Selection Rationale

This resource was selected as the primary observational input because it provides a coherent and relatively recent overview of the Soar cognitive architecture.

Several properties make it particularly suitable for the present mission.

### 1. Architectural Orientation

The document is explicitly designed to provide a functional overview of Soar.

Its purpose is therefore closely aligned with the needs of Structural Representation Methodology.

The resource is not limited to:

- one experimental application;
- one learning mechanism;
- one implementation problem;
- one isolated subsystem.

Instead, it provides broad architectural coverage.

---

### 2. Integrated Coverage

The document addresses multiple major architectural areas within a single explanatory framework.

Expected observational coverage includes:

- processing;
- memory systems;
- learning mechanisms;
- architectural interfaces;
- knowledge representations;
- decision processes;
- impasses and substates;
- procedural learning;
- reinforcement learning;
- semantic memory;
- episodic memory;
- spatial-visual reasoning.

This integrated coverage makes the resource suitable as the principal observational entry point.

These areas are recorded only as expected structural coverage.

No structural relationships are derived from them at the Representative Resource Curation stage.

---

### 3. Authoritative Authorship

The resource is authored by John E. Laird, a principal developer of the Soar cognitive architecture.

This provides a strong basis for treating the document as an authoritative architectural overview rather than relying primarily on secondary interpretation.

---

### 4. Relative Recency

The resource was released in 2022.

For a cognitive architecture with a long developmental history, a relatively recent overview reduces the risk of using only an early historical description that may not adequately reflect later architectural development.

The document addresses Soar 9.6.

---

### 5. Public Accessibility

The resource is publicly available through arXiv.

This supports:

- independent inspection;
- methodological transparency;
- reproducibility;
- provenance tracking;
- future validation.

---

### 6. Appropriate Abstraction Level

The document provides architectural information without requiring the Representative Resource Curation stage to reconstruct SOAR from source code or low-level implementation documentation.

This makes it appropriate for repository-level structural observation.

---

# Rationale for Complementary Resource Selection

## Resource

**The Soar Architecture — Soar User's Manual**

## Selection Role

**Complementary Representative Resource**

## Complementary Selection Rationale

The official architecture documentation was selected to complement the Primary Resource rather than replace it.

Its principal methodological value is that it provides an official architecture-oriented reference maintained within the Soar documentation environment.

---

### 1. Official Documentation

The resource belongs to the official Soar documentation maintained by the Soar project.

This provides a direct reference point against which architectural descriptions in the Primary Resource may later be examined.

---

### 2. Architecture-Specific Focus

The relevant manual section is specifically concerned with the Soar architecture.

This makes it particularly useful as a complementary source when the subsequent Structural Representation Methodologist needs to inspect architectural definitions more closely.

---

### 3. Maintained Version Context

The current Soar User's Manual documents Soar 9.6.5.

This provides a useful complement to the Primary Resource, which addresses Soar 9.6.

The resources therefore provide closely related but not completely identical version contexts.

---

### 4. Structural Explicitness

Official architecture documentation is expected to provide relatively explicit descriptions of architectural elements and processing behavior.

Potential areas of observational coverage include:

- states;
- operators;
- goals;
- working memory;
- procedural knowledge;
- preferences;
- decision processes;
- operator proposal;
- operator selection;
- operator application.

These items are not converted into a Structural Representation in this document.

They are recorded only as indicators of resource suitability.

---

### 5. Complementary Function

The Primary Resource provides an integrated research-level overview.

The official documentation provides a more direct architecture-oriented reference.

The relationship can therefore be expressed as:

```text
Integrated Overview
        +
Official Architecture Reference
        ↓
Stronger Observational Basis
```

---

# Why Two Resources Were Selected

A single resource could potentially provide sufficient information to begin Structural Representation.

However, Mission 001 intentionally retains two resources because they serve different methodological functions.

```text
Laird (2022)
        ↓
Coherent Integrated Overview

Official Soar Documentation
        ↓
Architecture-Specific Official Reference

        ↓
Cross-Supported Observational Input
```

The purpose of the second resource is not to increase the quantity of source material.

Its purpose is to improve the quality and traceability of the observational basis.

---

# Why Additional Resources Were Not Selected

SOAR has a substantial body of literature, including:

- books;
- historical architecture papers;
- tutorials;
- application studies;
- implementation documentation;
- learning-specific studies;
- domain-specific SOAR research.

These resources may contain valuable information.

However, including them in the initial Representative Resource Set would increase the size and complexity of the observational input without necessarily improving representation of the overall architecture.

The present mission therefore applies the principle:

```text
Sufficient Coverage
        +
Minimal Source Set
        >
Exhaustive Resource Collection
```

Additional resources should not be incorporated automatically.

They should be introduced only when a specific structural ambiguity, version issue, or source limitation requires supplementary evidence.

---

# Selection Criteria Assessment

The selected resources were evaluated according to the criteria defined for Representative Resource Curation.

| Criterion | Laird (2022) | Official Soar Documentation |
|---|---|---|
| Public Availability | High | High |
| Architectural Orientation | High | High |
| Overall Representativeness | High | High |
| Structural Explicitness | High | High |
| Appropriate Abstraction Level | High | High |
| Source Authority | High | High |
| Relative Recency | High | High |
| Expected Projection Suitability | High | High |
| Selection Role | Primary | Complementary |

This table represents a resource-selection assessment.

It does not constitute Structural Representation or theoretical evaluation.

---

# Version Consideration

The selected resources describe closely related but slightly different version contexts.

```text
Primary Resource
Laird (2022)
        ↓
Soar 9.6

Complementary Resource
Official Soar Manual
        ↓
Soar 9.6.5
```

This difference is not considered a reason to reject the two-resource configuration.

Instead, it should remain explicitly visible as part of source provenance.

If subsequent Structural Representation identifies a meaningful architectural difference between the two version contexts, that difference should be documented rather than silently reconciled.

---

# Selection Limitations

The selected resource set has several deliberate limitations.

## Not Exhaustive

The resource set does not attempt to represent the complete SOAR literature.

## Not Historical

The mission does not attempt to reconstruct the full historical evolution of SOAR.

## Not Implementation-Centric

Low-level implementation details are not the primary selection target.

## Not Application-Specific

Individual SOAR applications are not used as representative architectural sources unless later evidence demonstrates a specific need.

## Not Comparative

The resources were not selected because they resemble:

- ACT-R;
- Transformer architectures;
- World Models;
- other cognitive architectures.

The selection was made independently on the basis of their ability to represent SOAR itself.

---

# Protection Against Comparison Bias

Mission 001 exists upstream of Comparative Observation.

Therefore, representative resources must not be selected in order to maximize expected similarity with another target architecture.

The methodological sequence must remain:

```text
SOAR
        ↓
Representative Resource Selection
        ↓
Structural Representation
        ↓
Canonical Structural Representation

ONLY AFTER THIS

        ↓
Comparative Observation
```

This separation reduces the risk that later comparison objectives influence the initial representation of SOAR.

---

# Structural Neutrality Principle

The Representative Resource Curator does not determine in advance:

- what the major SOAR layers are;
- what the canonical modules are;
- which components are structurally central;
- what dependencies exist;
- what topology SOAR exhibits;
- whether SOAR corresponds to another architecture.

Those questions belong to Structural Representation and subsequent Comparative Observation.

The present resource-selection process establishes only that the selected sources appear sufficiently rich and authoritative to support those later observations.

---

# Final Selection Rationale

The final selection can be summarized as:

```text
SOAR Cognitive Architecture
        ↓
Need for Representative Observational Input
        ↓

Primary
Laird (2022)
Integrated + Authoritative + Recent Overview

        +

Complementary
Official Soar Architecture Documentation
Official + Maintained + Architecture-Specific

        ↓
Minimal Two-Resource Configuration
        ↓
Sufficient Expected Architectural Coverage
        ↓
Public Traceability
        ↓
Suitable Input Candidate
for Structural Representation
```

---

# Selection Decision

**Representative Resource Set:** APPROVED

**Primary Resource:** APPROVED

**Complementary Resource:** APPROVED

**Additional Representative Resources:** NOT REQUIRED AT PRESENT

**Resource Selection:** FROZEN

**Structural Representation:** NOT STARTED

---

# Next Step

The next document is:

`03-resource-readiness-assessment.md`

Its purpose is not to reconsider the resource selection.

Its purpose is to determine whether the frozen two-resource configuration is sufficiently ready to cross the handover boundary into Structural Representation.

---

# End of Selection Rationale
