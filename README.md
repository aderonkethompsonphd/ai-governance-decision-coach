# AI Governance Decision Coach

AI Governance Decision Coach is a practical learning project for making proportionate, evidence-based decisions about organisational AI use. It guides a learner to assess a scenario before reviewing a structured analysis, governance actions and escalation finding.

The project is designed for AI governance, risk, compliance, procurement, privacy, information-security and technology professionals. It is a learning and preliminary-assessment resource, not legal advice, compliance certification or final organisational approval.

## What the coach assesses

Each exercise examines eight dimensions:

1. Purpose and necessity
2. Affected people
3. Data
4. Autonomy and human oversight
5. Possible harms
6. Governance and regulatory exposure
7. Third-party dependency
8. Reversibility

The coach requires the learner to decide first. It then distinguishes:

- inherent risk;
- control design;
- evidence that controls operate;
- residual risk; and
- uncertainty.

## Decision outcomes

The available outcomes are:

- approve;
- approve with conditions;
- restricted pilot;
- pause for evidence;
- redesign;
- escalate; or
- reject.

High-impact, rights-affecting, safety-related or materially uncertain uses are flagged for appropriate specialist review and an accountable organisational decision owner.

## Case studies

### AI applicant screening

A fictional multi-country organisation proposes an AI system that analyses, ranks and automatically excludes job applicants. The completed assessment identifies high inherent risk, missing evidence and weak oversight. It recommends pausing for evidence and redesigning the workflow before any restricted pilot.

[View the completed recruitment assessment](case-studies/recruitment-ai/completed-assessment.pdf)

### Internal meeting-note summarisation

An organisation proposes an AI tool that summarises internal, non-confidential meeting notes without making decisions or triggering actions. The assessment recommends approval with conditions because the use is bounded and assistive, while requiring evidence for human review, data restrictions, vendor assurance, correction and exit controls.

[View the completed meeting-summary assessment](case-studies/meeting-summarisation/completed-assessment.pdf)

## Why the two cases are paired

The comparison demonstrates proportional governance. Employment screening can affect access to opportunity and requires stronger safeguards and escalation. Meeting summarisation is lower impact and more reversible, but it is not risk-free. The appropriate response depends on purpose, affected people, data, consequences, control evidence and uncertainty—not merely on whether a system uses AI.

[Read the proportional-governance comparison](comparison/proportional-governance-reflection.md)

## Repository structure

```text
ai-governance-decision-coach/
├── README.md
├── LICENSE
├── CITATION.cff
├── CONTRIBUTING.md
├── methodology/
│   └── decision-assessment-framework.md
├── case-studies/
│   ├── recruitment-ai/
│   │   ├── scenario.md
│   │   └── completed-assessment.pdf
│   └── meeting-summarisation/
│       ├── scenario.md
│       └── completed-assessment.pdf
└── comparison/
    └── proportional-governance-reflection.md
```

## How to use the framework

1. Read a scenario without opening its completed assessment.
2. Answer the eight assessment questions and make a provisional decision.
3. Identify which statements are verified evidence, user-provided information, assumptions or missing evidence.
4. Separate inherent risk from proposed safeguards.
5. Open the completed assessment and compare the reasoning.
6. Record overlooked risks, evidence needs and changes to the initial decision.

## Evidence discipline

The project uses four evidence labels:

| Label | Treatment |
|---|---|
| Verified evidence | Supported by an authoritative supplied source or validated record |
| User-provided information | Used provisionally but not treated as independently verified |
| Assumption | Stated explicitly and tested when it could change the decision |
| Missing evidence | Assigned for verification before risk acceptance or approval |

Proposed or undocumented safeguards do not automatically reduce risk. Residual risk should be concluded only after relevant controls are implemented and their operation is evidenced.

## Licence

The project is released under the [MIT License](LICENSE). Case-study scenarios are fictional and provided for learning.

## Author

Dr Aderonke Thompson

