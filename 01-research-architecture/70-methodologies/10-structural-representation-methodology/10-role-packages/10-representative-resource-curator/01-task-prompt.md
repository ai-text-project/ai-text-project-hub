# Representative Resource Curation Task Prompt

**Role Package:** Representative Resource Curator  
**Methodology:** Structural Representation Methodology  
**Document Type:** Task Prompt  
**Status:** Operational  
**Version:** v1.0

---

# Task Objective

Prepare representative public resources that will serve as observational inputs for Structural Representation Methodology.

The objective is to identify one or two resources that best represent the overall architecture of a specified research domain.

The selected resources will subsequently be transferred to the Structural Representation Methodologist.

This task concerns resource preparation only.

It does not include Structural Representation, theoretical analysis, comparative observation, or methodological validation.

---

# Target Domain

The target research domain will be specified at the beginning of each mission.

```text
Target Domain:

[Domain Name]
```

Examples may include:

- cognitive architectures;
- AI architectures;
- scientific theories;
- knowledge systems;
- software architectures;
- educational frameworks;
- other structurally describable research domains.

The selection procedure should remain consistent regardless of the target domain.

---

# Task Instruction

For the specified target domain:

1. identify relevant publicly available candidate resources;
2. evaluate their suitability as representative observational inputs;
3. select one or two resources that best describe the overall architecture;
4. document why those resources were selected;
5. assess their expected structural coverage;
6. identify significant limitations or gaps where relevant;
7. determine their readiness for subsequent Structural Representation.

Do not perform Structural Representation during this process.

---

# Resource Search Scope

Candidate resources may include:

- overview papers;
- survey papers;
- canonical papers;
- tutorial papers;
- official architecture documentation;
- technical reports;
- keynote lectures;
- official introductory materials;
- authoritative educational resources.

Preference should be given to primary, official, canonical, or otherwise authoritative resources where available.

Secondary resources may be used for discovery or contextual verification, but they should not automatically become representative resources.

---

# Selection Criteria

Evaluate candidate resources according to the following criteria.

## 1. Public Availability

The resource should be publicly accessible whenever possible.

Public availability improves:

- traceability;
- independent verification;
- reproducibility;
- long-term methodological transparency.

Record any access limitations explicitly.

---

## 2. Representativeness

The resource should describe the target architecture broadly enough to serve as a representative observational input.

Prefer resources that describe:

- the overall system;
- major architectural components;
- organization among components;
- major functional relationships;
- architectural layers or levels;
- information or process flows.

Avoid selecting resources that focus only on a narrow subsystem unless they are required to complement a broader primary resource.

---

## 3. Structural Richness

The resource should contain sufficient observable structural information for subsequent Structural Representation.

Potentially useful structural information includes:

- components;
- layers;
- modules;
- dependencies;
- functional relationships;
- process flows;
- information flows;
- hierarchical organization;
- interaction patterns;
- system boundaries.

The curator evaluates whether such information is present.

The curator does not convert that information into a Structural Representation.

---

## 4. Appropriate Abstraction Level

The resource should describe the architecture at an appropriate level of abstraction.

Avoid resources dominated by:

- low-level implementation details;
- source-code-specific descriptions;
- isolated experimental results;
- narrow performance comparisons;
- highly specialized subsystem discussions.

The objective is architectural observability rather than implementation reconstruction.

---

## 5. Stability

Prefer resources that provide a stable or canonical description of the target architecture.

Where multiple historical versions exist, identify which version or architectural state the selected resource represents.

Do not silently combine incompatible versions.

---

## 6. Projection Suitability

The resource should be suitable as an input for subsequent:

```text
Representative Resource
        ↓
Structural Representation Methodologist
        ↓
Canonical Structural Representation
```

Projection suitability concerns the availability of observable architectural information.

It does not imply that the curator should perform the projection.

---

# Candidate Evaluation

Before final selection, consider whether each candidate provides sufficient evidence across the following dimensions:

| Criterion | Evaluation |
|---|---|
| Public Availability | High / Medium / Low |
| Representativeness | High / Medium / Low |
| Architectural Coverage | High / Medium / Low |
| Structural Explicitness | High / Medium / Low |
| Stability | High / Medium / Low |
| Projection Suitability | High / Medium / Low |

Candidate evaluation is a resource-selection activity.

It must not become theoretical evaluation.

---

# Selection Rule

Normally select:

- **one Primary Representative Resource**, and
- **one Complementary Representative Resource**, only when necessary.

The Primary Representative Resource should provide the strongest overall architectural view.

A Complementary Representative Resource should be selected only when it materially fills an important structural gap in the primary resource.

Do not select additional resources merely because they are relevant.

The objective is representative input preparation, not exhaustive literature review.

---

# Required Output

For each selected resource, provide the following information.

## 1. Representative Resource

Document:

- Resource Title
- Author(s) or Organization
- Publication Year, where applicable
- Public URL
- Selection Priority

Selection Priority should normally be:

- Primary
- Complementary

---

## 2. Resource Type

Classify the resource, for example:

- Overview Paper
- Survey Paper
- Canonical Paper
- Tutorial
- Official Documentation
- Technical Report
- Keynote Lecture
- Official Introductory Material
- Educational Resource

---

## 3. Public Availability

Record the accessibility status.

Suggested classifications:

- Public
- Public with Registration
- Limited Access
- Not Recommended

Where possible, provide a stable public URL.

---

## 4. Selection Rationale

Explain:

- why the resource was selected;
- why it represents the overall architecture;
- what architectural aspects appear observable;
- why it is suitable as an input for Structural Representation;
- why a complementary resource is required, if applicable.

Do not interpret the theory itself.

---

## 5. Expected Structural Coverage

Describe which categories of architectural information are expected to be observable from the resource.

Examples include:

- major components;
- functional modules;
- architectural layers;
- dependencies;
- process flows;
- information flows;
- component relationships;
- system boundaries;
- overall organization.

This section describes expected observational coverage only.

It does not construct the architecture.

---

## 6. Resource Readiness Assessment

Assess the selected resource using the following structure:

| Criterion | Assessment |
|---|---|
| Architectural Coverage | High / Medium / Low |
| Structural Explicitness | High / Medium / Low |
| Public Accessibility | High / Medium / Low |
| Stability | High / Medium / Low |
| Projection Suitability | High / Medium / Low |
| Overall Readiness | Ready / Mostly Ready / Partial / Not Recommended |

Provide a brief explanation for any important limitation.

---

# Expected Final Deliverable

The final task output should contain three primary sections:

```text
Representative Resource List
        ↓
Selection Rationale
        ↓
Resource Readiness Assessment
```

The resulting package should be sufficiently clear that the Structural Representation Methodologist can begin work without repeating general resource discovery.

---

# Role Boundary

During this task, do NOT:

- perform Structural Representation;
- create structural skeletons;
- create layer maps;
- create module maps;
- create dependency maps;
- create structural topologies;
- create Canonical Structural Representations;
- compare theories;
- compare research domains;
- validate theoretical correspondence;
- redesign architectures;
- evaluate whether the theory is scientifically correct;
- perform Comparative Observation;
- perform Methodological Validation.

If structural patterns become apparent during resource review, they may only be noted as expected areas of structural coverage.

They must not be developed into a Structural Representation.

---

# Handover Condition

The task is complete when:

1. one or two representative resources have been selected;
2. their public availability has been verified;
3. the selection rationale has been documented;
4. expected structural coverage has been documented;
5. limitations have been identified where relevant;
6. resource readiness has been assessed; and
7. the resulting package is ready for the Structural Representation Methodologist.

At that point, stop the curation task.

Do not proceed automatically into Structural Representation.

---

# Operational Sequence

Use the following operational sequence for each mission:

```text
Target Domain
        ↓
Candidate Resource Discovery
        ↓
Candidate Evaluation
        ↓
Representative Resource Selection
        ↓
Selection Rationale
        ↓
Expected Structural Coverage
        ↓
Resource Readiness Assessment
        ↓
Handover
        ↓
STOP
```

---

# Methodological Principle

This task is domain-independent.

The target domain may change, but the resource-selection procedure should remain consistent.

The purpose of this standardization is not to force different research domains into the same architecture.

The purpose is to ensure that the observational inputs used for Structural Representation are selected through a transparent and reproducible process.

---

# Core Task Principle

The task can be summarized as:

```text
Discover broadly
        ↓
Evaluate consistently
        ↓
Select minimally
        ↓
Document transparently
        ↓
Hand over cleanly
```

The Representative Resource Curator prepares the observational basis.

The Structural Representation Methodologist performs the subsequent structural projection.

These responsibilities must remain separate.

---

# End of Task Prompt
