# Human–AI Research Practice

**Status:** Provisional / Visitor-facing Observation

このページでは、AI Text ProjectのResearch Spaceにおいて、Humanと複数のAI Instanceがどのような関係で研究活動を行っているのかを、簡潔な観察例として紹介します。

これは、新しいMulti-Agent Architectureや一般的なHuman–AI Collaboration Modelを提案するものではありません。

ここで示すのは、このResearch Spaceにおいて実際に観察されているResearch Practiceです。

---

## How Is Research Conducted in This Research Space?

このResearch Spaceでは、研究活動は必ずしも一つのAI Instanceとの継続的な対話だけで進められているわけではありません。

複数のAI Instanceが異なるRoleを担当し、同じResearch Taskを異なる責任から扱う場合があります。

例えば、論文制作では次のようなRoleが利用されます。

- Terminologist
- Strategist
- Refiner
- Editor
- Reviewer
- Refine-Executor

重要なのは、これらのAI Instanceが通常、自律的に相互調整しているわけではないことです。

Humanが、それぞれのRoleとの対話を通じて、次にどのRoleへ進むか、どのArtifactを引き渡すか、どのOutputを採用するかを判断します。

---

## Human–AI Dialogue Structure

この関係を単純化すると、次のように表すことができます。

```text
                         Human Researcher
                               │
                  Dialogue / Mediation / Judgment
                               │
             ┌─────────────────┼─────────────────┐
             │                 │                 │
             ▼                 ▼                 ▼
        AI Instance A     AI Instance B     AI Instance C
         Role: Editor      Role: Reviewer    Role: Strategist
             │                 │                 │
             │                 │                 │
             └─────────────────┼─────────────────┘
                               │
                               ▼
                       Research Artifacts
                               │
                               ▼
                         Research Space
```

Humanは単なるMessage Relayではありません。

観察されている範囲では、HumanはRoleの選択、判断、Routing、承認、Contextの再設定などを担っています。

---

## How AI Instances Are Indirectly Connected

AI Instance同士は通常、直接対話していません。

しかし、それぞれの研究活動が完全に独立しているわけでもありません。

あるInstanceのOutputがResearch Artifactとして外部化され、Humanによる選択やHandoverを通じて、別のInstanceのInputになることがあります。

```text
       AI Instance A
             │
             │  Output
             ▼
      Research Artifact
             │
             ▼
       Human Mediation
             │
       Select / Judge / Route
             │
             ▼
       AI Instance B
             │
             │  New Output
             ▼
      Research Artifact
             │
             ▼
        Research Space
```

このため、直接的なAgent-to-Agent Communicationがなくても、複数のAI Instanceによる研究活動は、HumanとArtifactを介して間接的に接続されます。

---

## Four Observable Characteristics

現在のResearch Practiceから、少なくとも次の4つの特徴を観察できます。

### 1. Multiple AI Instances

複数のAI Instanceが、より長期的なResearch Processに参加します。

### 2. Role Specialization

AI Instanceには、それぞれ異なるBounded Responsibilityが与えられます。

同じResearch Taskであっても、Editor、Reviewer、Strategistなど、異なる機能的位置から扱われることがあります。

### 3. Human Mediation

HumanはInstance間のResearch Activityを自動化されたAgent Coordinationに委ねるのではなく、選択、判断、Routing、Handoverなどを担います。

### 4. Externalized Research Space

研究成果は個々のAI Conversationだけに留まらず、Markdown、Paper、Figure、Methodology、Observation RecordなどのResearch Artifactとして外部化され、Research Spaceへ配置されることがあります。

---

## Research Space as Persistent Context

外部化されたResearch Artifactは、単なる保存物とは限りません。

後の研究活動において、Humanが過去のArtifactを選択し、別のAI Instanceへ引き渡すことで、時間的・会話的に分離された研究活動を接続できます。

```text
 Human–AI Dialogue
        │
        ▼
 Role-specific Activity
        │
        ▼
 Research Artifact
        │
        ▼
   Research Space
        │
        ▼
 Subsequent Observation
        │
        ▼
 Further Research
```

この意味でResearch Spaceは、異なる時点・異なるInstanceで行われた研究活動を接続するPersistent External Contextとして機能する可能性があります。

また、Research Spaceに蓄積されたArtifactやその構造自体が、後に新たなObservationの対象となることがあります。

---

## Relationship to Research Space Observation

このページが示しているのは、

> **How is research practiced within this Research Space?**

という観察です。

Research Spaceそのものにどのような構造変化が観察されたのかについては、別のEntry Assetで実例を見ることができます。

### → [Research Space Structural Change Example](./06-research-space-structural-change-example.md)

この二つのObservationは関連していますが、Human–AI Research Practiceが特定の構造変化を直接引き起こしたことを、このページだけから結論づけることはできません。

---

## Evidence Boundary

このページは、現在観察されているHuman–AI Research PracticeをVisitor向けに簡略化して示したものです。

ここで示した関係は、次のことを確立するものではありません。

- 新しいMulti-Agent Architectureが成立していること
- AI Instance同士が自律的にCoordinationしていること
- Research Spaceが自律的に進化していること
- Human–AI InteractionだけがResearch Spaceの構造変化を引き起こしていること
- このResearch Practiceが他のHuman–AI Research Environmentにも一般化できること

したがって、このページはFormal Architectureや一般理論ではなく、**Visitor-facing Observation**として位置づけられています。

---

## Further Exploration

AI Text Project全体とResearch Spaceについては、Research Overviewから探索できます。

### → [Research Overview](./04-research-overview.md)

すべてのResearch Assetを読む必要はありません。

このResearch Practiceについて必要な範囲を観察した時点で、ここで探索を終えていただいて構いません。

---

# Human–AI Research Practice

**Status:** Provisional / Visitor-facing Observation

This page provides a concise observational view of how a Human and multiple AI instances participate in research activity within the AI Text Project Research Space.

It does not propose a new Multi-Agent Architecture or a general model of Human–AI Collaboration.

Instead, it illustrates a Research Practice currently observed within this Research Space.

---

## How Is Research Conducted in This Research Space?

Research activity within this Research Space does not necessarily proceed through sustained dialogue with a single AI instance.

Multiple AI instances may take differentiated Roles and work on the same Research Task from different responsibilities.

For example, paper production may involve Roles such as:

- Terminologist
- Strategist
- Refiner
- Editor
- Reviewer
- Refine-Executor

Importantly, these AI instances do not normally coordinate autonomously with one another.

Through dialogue with the different Roles, the Human decides which Role should act next, which Artifact should be transferred, and whether an Output should be accepted or revised.

---

## Human–AI Dialogue Structure

A simplified representation of this relationship is:

```text
                         Human Researcher
                               │
                  Dialogue / Mediation / Judgment
                               │
             ┌─────────────────┼─────────────────┐
             │                 │                 │
             ▼                 ▼                 ▼
        AI Instance A     AI Instance B     AI Instance C
         Role: Editor      Role: Reviewer    Role: Strategist
             │                 │                 │
             │                 │                 │
             └─────────────────┼─────────────────┘
                               │
                               ▼
                       Research Artifacts
                               │
                               ▼
                         Research Space
```

The Human is more than a simple message relay.

Within the observed practice, the Human performs functions including Role selection, judgment, routing, authorization, and re-contextualization.

---

## How AI Instances Are Indirectly Connected

AI instances do not normally communicate directly with one another.

Their research activities, however, are not completely isolated.

An Output produced by one instance may be externalized as a Research Artifact and later become an Input to another instance through Human selection and handover.

```text
       AI Instance A
             │
             │  Output
             ▼
      Research Artifact
             │
             ▼
       Human Mediation
             │
       Select / Judge / Route
             │
             ▼
       AI Instance B
             │
             │  New Output
             ▼
      Research Artifact
             │
             ▼
        Research Space
```

Multiple AI instances can therefore become indirectly connected through Human mediation and transferred Artifacts without requiring direct Agent-to-Agent Communication.

---

## Four Observable Characteristics

At least four characteristics can currently be observed in this Research Practice.

### 1. Multiple AI Instances

Multiple AI instances participate in the longer Research Process.

### 2. Role Specialization

AI instances are assigned differentiated Bounded Responsibilities.

Even within the same Research Task, different Roles such as Editor, Reviewer, or Strategist may examine or transform the research object from different functional positions.

### 3. Human Mediation

Rather than delegating coordination entirely to autonomous Agent mechanisms, the Human performs selection, judgment, routing, and handover between research activities.

### 4. Externalized Research Space

Research outputs are not confined to individual AI conversations.

They may be externalized as Research Artifacts such as Markdown documents, Papers, Figures, Methodologies, and Observation Records and placed within the Research Space.

---

## Research Space as Persistent Context

Externalized Research Artifacts are not necessarily only stored outputs.

In subsequent research activity, the Human can select an earlier Artifact and provide it to another AI instance, connecting research activities that are separated across time and conversations.

```text
 Human–AI Dialogue
        │
        ▼
 Role-specific Activity
        │
        ▼
 Research Artifact
        │
        ▼
   Research Space
        │
        ▼
 Subsequent Observation
        │
        ▼
 Further Research
```

In this sense, the Research Space may function as Persistent External Context connecting research activities conducted at different times and with different AI instances.

Accumulated Artifacts and their organization may also later become objects of further observation.

---

## Relationship to Research Space Observation

This page addresses the question:

> **How is research practiced within this Research Space?**

A separate Entry Asset provides an observable example of how the visible structure of the Research Space changed over time.

### → [Research Space Structural Change Example](./06-research-space-structural-change-example.md)

These two observations may be related, but this page alone does not establish that the Human–AI Research Practice directly caused any particular structural change.

---

## Evidence Boundary

This page is a simplified Visitor-facing representation of a currently observed Human–AI Research Practice.

The relationship described here does not establish that:

- a new Multi-Agent Architecture has been formed;
- AI instances autonomously coordinate with one another;
- the Research Space evolves autonomously;
- Human–AI Interaction alone causes structural changes in the Research Space; or
- this Research Practice generalizes to other Human–AI Research Environments.

This page should therefore be understood as a **Visitor-facing Observation**, rather than as a Formal Architecture or general theory.

---

## Further Exploration

For a broader view of the AI Text Project and its Research Space, visit the Research Overview.

### → [Research Overview](./04-research-overview.md)

There is no requirement to read every Research Asset.

You may stop exploring when you have reached the level of context relevant to your interests.
