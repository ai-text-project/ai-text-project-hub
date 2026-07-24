# Shared Markdown Knowledge Layer Design Review

**Design Version:** v1.0 (Provisional)

---

# Purpose

This document records the design considerations that led to the introduction of the Shared Markdown Knowledge Layer within the Research Program.

Whereas the primary document defines the concept itself, this Design Review explains why such a knowledge layer became necessary, how the concept emerged through operational experience, and how subsequent comparison with external ideas helped clarify its role.

The objective is not to introduce a new methodology, but to document the reasoning process behind the architectural decision.

---

# Background

As the Research Program expanded over an extended period of Human–AI collaboration, the number of research assets continuously increased.

Dialogue histories gradually evolved into structured Markdown documents, including:

- Observation Notes
- Case Records
- Methodologies
- Operational Reports
- Research Maps
- Glossaries
- Presentation Assets

Initially, these Markdown documents were created simply to preserve research results.

However, over time they became the primary operational resources shared between human researchers and AI instances.

Rather than repeatedly consulting raw dialogue histories, subsequent research activities increasingly operated on these structured Markdown assets.

This gradual operational transition suggested the existence of a persistent shared knowledge layer.

---

# External Reference

During later discussions, the concept of **LLM-Wiki**, proposed by Andrej Karpathy, was reviewed.

The purpose of this review was not to determine whether the Research Program implemented LLM-Wiki.

Instead, the comparison was intended to determine whether both systems exhibited similar organizational principles.

According to the published description, the LLM-Wiki workflow emphasizes:

- preserving raw source materials
- compiling knowledge into Markdown
- enabling both humans and LLMs to access the same knowledge layer
- continuously refining that shared semantic resource

The emphasis therefore lies on workflow organization rather than on a particular software implementation. :contentReference[oaicite:0]{index=0} :contentReference[oaicite:1]{index=1}

---

# Structural Comparison

Comparison between the two workflows suggested several corresponding characteristics.

| LLM-Wiki | Research Program |
|----------|------------------|
| Raw source materials | Dialogue histories |
| Markdown Wiki | Structured Markdown research assets |
| Shared knowledge layer | GitHub Markdown layer |
| Human + LLM collaboration | Human + AI collaborative research |
| Continuous refinement | Progressive research asset development |

Although developed independently, both workflows appear to organize knowledge around persistent Markdown-based semantic resources.

---

# Interpretation

The comparison does not imply that the Research Program is an implementation of LLM-Wiki.

Rather, it indicates that independently developed research workflows may converge toward similar organizational principles.

Within the present Research Program, GitHub functions not merely as a document repository.

Instead, it serves as a persistent semantic environment in which Markdown assets become the primary medium for long-term Human–AI collaborative research.

The concept of the Shared Markdown Knowledge Layer therefore emerged not from theoretical design, but from repeated operational practice.

The subsequent comparison with LLM-Wiki provided an external conceptual reference that helped clarify this architectural role.

---

# Design Outcome

Based on these observations, the Research Program formally recognizes the Shared Markdown Knowledge Layer as one of its foundational knowledge infrastructures.

This concept provides a common semantic workspace supporting:

- Research Architecture
- Operational Architecture
- Methodology Development
- Paper Assembly
- Presentation Development
- Knowledge Organization
- Long-duration Human–AI collaboration

The accompanying definition is documented separately in:

**00-shared-markdown-knowledge-layer.md**

This document serves as its design rationale and comparative review.

---

# Future Considerations

The present review represents an initial architectural interpretation.

Future studies may further examine:

- persistent semantic systems
- long-duration Human–AI collaboration
- Markdown-based knowledge infrastructures
- dialogue-centered research environments
- comparative studies with emerging Human–AI knowledge management frameworks

as the Research Program continues to evolve.
