# Mission 001 — SOAR Representative Resource List

**Mission ID:** RRC-001  
**Target Domain:** SOAR Cognitive Architecture  
**Methodology:** Structural Representation Methodology  
**Operational Stage:** Representative Resource Curation  
**Responsible Role:** Representative Resource Curator  
**Document Type:** Representative Resource List  
**Status:** Resource Set Frozen  
**Version:** v0.1

---

# Purpose

This document records the representative public resources selected for:

**Mission 001 — SOAR Representative Resource Curation**

The purpose of this document is to establish a clear and traceable record of the observational inputs that will subsequently be transferred to the Structural Representation Methodologist.

This document does not perform Structural Representation.

It records the resources from which subsequent Structural Representation may begin.

---

# Target Domain

**SOAR Cognitive Architecture**

The selected resources are intended to provide a representative observational basis for the architecture of Soar.

The resource set is intentionally limited.

The objective is not to create an exhaustive SOAR bibliography.

The objective is to identify a minimal and defensible set of public resources with sufficient architectural coverage for subsequent Structural Representation.

---

# Representative Resource Set

Mission 001 uses the following two-resource configuration:

| Priority | Resource | Resource Type | Public Availability |
|---|---|---|---|
| Primary | John E. Laird, *Introduction to Soar* (2022) | Authoritative Architectural Overview / Preprint | Public |
| Complementary | *The Soar Architecture*, Soar User's Manual | Official Architecture Documentation | Public |

The resource set is frozen for the present mission.

---

# Resource 01 — Primary Representative Resource

## Basic Information

**Title:** *Introduction to Soar*  
**Author:** John E. Laird  
**Year:** 2022  
**Publication Date:** May 8, 2022  
**Resource Type:** Authoritative Architectural Overview / Preprint  
**Selection Priority:** Primary  
**Target Version:** Soar 9.6  
**Public Availability:** Public

## Public Access

**arXiv Record:**  
https://arxiv.org/abs/2205.03854

**arXiv PDF:**  
https://arxiv.org/pdf/2205.03854

---

# Resource Role

This resource serves as the primary architectural overview for Mission 001.

It is intended to provide a coherent research-level introduction to the functional architecture of Soar.

The resource explicitly presents itself as recommended initial reading for a functional overview of Soar 9.6.

Its coverage includes architectural structure at the level of:

- processing;
- memory systems;
- learning modules;
- interfaces among architectural components;
- knowledge representations;
- decision making;
- impasses and substates;
- procedural learning;
- reinforcement learning;
- semantic memory;
- episodic memory;
- spatial-visual reasoning.

These items are recorded here as expected areas of observational coverage.

No Structural Representation is derived from them at this stage.

---

# Why It Is the Primary Resource

The resource is assigned Primary status because it combines several properties relevant to Representative Resource Curation:

1. it is authored by John E. Laird;
2. it provides an explicit overview of the Soar cognitive architecture;
3. it addresses Soar 9.6 rather than only an early historical version;
4. it covers multiple architectural systems within a single coherent document;
5. it is publicly accessible;
6. it is specifically intended as introductory reading for understanding Soar's functional architecture.

The detailed methodological rationale for selection is documented in:

`02-selection-rationale.md`

---

# Resource 02 — Complementary Representative Resource

## Basic Information

**Title:** *The Soar Architecture*  
**Parent Resource:** *The Soar User's Manual*  
**Responsible Organization:** Soar Group / University of Michigan  
**Resource Type:** Official Architecture Documentation  
**Selection Priority:** Complementary  
**Documented Version:** Soar 9.6.5  
**Public Availability:** Public

## Public Access

**Official Architecture Documentation:**  
https://soar.eecs.umich.edu/soar_manual/02_TheSoarArchitecture/

**Soar User's Manual:**  
https://soar.eecs.umich.edu/soar_manual/

---

# Resource Role

This resource serves as the complementary official architecture reference for Mission 001.

The Soar User's Manual documents the current Soar architecture, and its architecture chapter provides an explicit description of the architecture independently of programming syntax.

The architecture documentation includes observable material concerning areas such as:

- the overall architecture;
- states;
- operators;
- goals;
- working memory;
- procedural knowledge;
- preferences;
- decision processes;
- operator proposal and selection;
- operator application;
- architectural processing.

These items are recorded as expected areas of observational coverage.

No structural model is constructed from them in this document.

---

# Why It Is the Complementary Resource

The official architecture documentation complements the Primary Resource by providing a maintained architecture-oriented reference from the Soar project itself.

The two resources therefore perform different functions:

```text
Primary Resource
Laird (2022)
        ↓
Coherent Functional Overview
of Soar 9.6

        +

Complementary Resource
Official Soar Architecture Documentation
        ↓
Maintained Official Architecture Reference
for Soar 9.6.5

        ↓
Representative Resource Set
```

The complementary resource is not intended to replace the Primary Resource.

Its role is to strengthen architectural traceability and provide an official reference point for subsequent structural observation.

---

# Resource Relationship

The two selected resources are intentionally complementary.

## Primary Resource Function

The Primary Resource provides:

- a coherent architectural overview;
- research-level explanation;
- broad functional coverage;
- a relatively recent integrated description of Soar.

## Complementary Resource Function

The Complementary Resource provides:

- official documentation;
- maintained architectural reference;
- architecture-specific descriptions;
- additional support for interpretation of the Primary Resource.

Together they provide a stronger observational basis than either resource alone.

---

# Version Alignment

The selected resources are closely aligned but not identical in version scope.

```text
Laird (2022)
        ↓
Soar 9.6

Official Soar Manual
        ↓
Soar 9.6.5
```

This distinction should remain visible during subsequent Structural Representation.

The Structural Representation Methodologist should not silently assume that every architectural statement in the two resources is necessarily identical across version boundaries.

Where a meaningful difference appears, it should be documented rather than automatically harmonized.

---

# Public Traceability

Both selected resources are publicly accessible.

This supports the methodological requirements of:

- source transparency;
- independent inspection;
- reproducibility;
- provenance tracking;
- later methodological validation.

The intended provenance chain is:

```text
SOAR Cognitive Architecture
        ↓
Representative Resource Curation
        ↓
Resource 01
Laird (2022)

        +

Resource 02
Official Soar Architecture Documentation
        ↓
Representative Resource Package
        ↓
Structural Representation Methodologist
```

---

# Resource Selection Boundary

The existence of other SOAR resources is acknowledged.

Potential additional materials include:

- books;
- tutorials;
- historical papers;
- implementation documentation;
- research articles;
- application-specific SOAR studies.

These resources are not part of the frozen Representative Resource Set for Mission 001.

They may be consulted later only if a documented structural ambiguity or source limitation requires supplementary evidence.

Such supplementation should be explicitly recorded rather than silently incorporated into the observational basis.

---

# Frozen Resource Set

The Representative Resource Set for Mission 001 is:

```text
PRIMARY

John E. Laird
Introduction to Soar
2022
Soar 9.6

        +

COMPLEMENTARY

The Soar Architecture
Soar User's Manual
Soar Group / University of Michigan
Soar 9.6.5
```

**Resource Set Status:** FROZEN

No additional representative resource should be added without a documented reason.

---

# Relationship to Subsequent Documents

This resource list establishes what has been selected.

The subsequent documents establish why the resources were selected and whether they are ready for downstream use.

```text
01-representative-resource-list.md
        ↓
WHAT was selected

02-selection-rationale.md
        ↓
WHY it was selected

03-resource-readiness-assessment.md
        ↓
WHETHER it is ready

04-handover-package.md
        ↓
WHAT is transferred downstream
```

---

# Current Status

```text
Target Domain
    SOAR Cognitive Architecture

Representative Resources
    2

Primary Resource
    SELECTED

Complementary Resource
    SELECTED

Public Availability
    CONFIRMED

Resource Set
    FROZEN

Structural Representation
    NOT STARTED
```

---

# End of Representative Resource List
