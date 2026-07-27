# Projection Unit Specification

**Architecture Version:** v0.1 (Provisional)

---

# Purpose

This document defines the architectural role of the Projection Unit within the Research-to-Society Projection Architecture.

The objective is not to specify communication content itself, but to define the transition point between the Research Space and the subsequent Phase Transformation process.

---

# Position within the Projection Workflow

The Projection Unit is positioned between the Research Package and Phase Transformation.

```text
Research Package
      │
      ▼
Projection Unit
      │
      ▼
Phase Transformation
```

The Projection Unit serves as the architectural handover point between these two operational stages.

---

# Definition

A Projection Unit is the architectural unit that connects a Research Package to the Phase Transformation process.

It represents the transition from research assets maintained within the Research Space to communication-oriented transformation.

The Projection Unit itself is not a communication product.

---

# Architectural Role

Within the Projection Workflow, the Projection Unit has three responsibilities.

- Connect the Research Package to the Projection Layer.
- Provide a consistent handover to the Phase Transformation process.
- Preserve the structural continuity between research assets and communication activities.

---

# Role Boundary

The Bridge-Layer Strategist is responsible for preparing the Projection Unit.

The Projection Unit is then transferred to the Phase Transformation process.

The creation of Medium Articles and X Posts is outside the responsibility of this specification.

---

# Relationship to Other Documents

This document should be interpreted together with:

- 10-projection-workflow.md

Subsequent documents describe how the Projection Unit is utilized after the architectural handover defined here.

---

# Summary

The Projection Unit is the architectural connection between the Research Space and the Phase Transformation process.

Its purpose is to establish a consistent and traceable transition from Research Packages to communication-oriented transformation while maintaining the integrity of the overall Research Architecture.
