# TRUECONNECT MASTER PROMPT INDEX

**Version:** 2.0  
**Authority:** This index and `00_MASTER_CONTROLLER.md` govern how the prompt catalog is used. The approved Architecture Constitution remains the highest architecture authority. Prompts are instructions, not approved architecture artifacts.

## How to use this catalog

The numbered files are conditional decision prompts, not a mandatory sequential checklist. Choose only the prompt needed for the current decision and maturity. Use a prototype or technical spike as a learning experiment when it is reversible, bounded, and does not make unsupported product or safety claims. Keep evidence status separate from artifact approval and production readiness.

## Product learning stages

**Discover ↔ Explore ↔ Architect ↔ Validate ↔ Operate and learn**

Evidence and build tracks may run in parallel. New findings can reopen a prior decision through explicit change control. Do not silently override an approved artifact, and do not let an obsolete approved assumption prevent a documented evidence-based revision.

## Numbered architecture catalog

| ID | Prompt | Decision scope | Applicability |
|---|---|---|---|
| 00 | Master Controller | Governance, maturity, decision protocol | Always applies |
| 01 | Architecture Constitution | Mission, durable principles, constraints, change control | Foundational; human approval required |
| 02 | Problem Validation | Problem, users, alternatives, evidence, outcomes | Use for validation claims; discovery prototypes may precede completion |
| 03 | Domain Architecture | Business concepts, capabilities, ownership | When domain boundaries are needed for the product decision |
| 04 | Resource Intelligence | Resource facts, provenance, stewardship | When representing or curating real resources |
| 05 | Verification & Reliability | Trust, freshness, confidence, conflict policy | Before making reliability or verification claims; scale to exposure |
| 06 | Matching Engine | Recommendation policy and user agency | When recommendations are proposed; simple manual/rules experiments may be used earlier |
| 07 | AI Governance | AI role, limitations, oversight | Conditional: only if AI is proposed or materially changed; document “AI not needed” otherwise |
| 08 | Data Architecture | Information ownership, purpose, lifecycle | Before retaining or processing real product data beyond disposable mock data |
| 09 | Security & Privacy | Threats, privacy, safeguards, accountability | Risk-based; required before sensitive data, external exposure, or consequential operation |
| 10 | API Architecture | External/internal interface contracts | Only when a real interface or integration is needed |
| 11 | Performance & Scalability | Measured/forecast workload and service expectations | Only when demand, consequence, or measured constraint justifies it |
| 12 | Infrastructure Architecture | Production operating environment and recovery | Before production operation, not for a disposable local prototype |
| 13 | Application Architecture | Application boundaries and workflows | When a repeatable product workflow merits formalization |
| 14 | Testing & Quality | Evidence that defined behavior meets quality/safety needs | Before user exposure at a level proportionate to risk; production readiness requires appropriate coverage |
| 15 | Delivery & Operations Governance | Change, incidents, support, ongoing stewardship | Before ongoing service operation; lightweight prototype practices may suffice earlier |
| 16 | Final Architecture Review Board | Integrated production-architecture decision | When production architecture is proposed; not a prerequisite to exploration |

## Supporting reviews (not numbered gates)

- `00A_META_EVALUATION_GATE.md`: independent qualitative review of a material artifact.
- `00B_ADVERSARIAL_RED_TEAM_GATE.md`: threat/abuse challenge when exposure or consequence warrants it.
- `00C_ARCHITECTURE_COST_REALITY_GATE.md`: cost and operating burden review for a material commitment.
- `00D_IMPLEMENTATION_FEASIBILITY_GATE.md`: feasibility review before committing to significant delivery.
- `00E_POST_DEPLOYMENT_LEARNING_LOOP_GATE.md`: operating feedback and revision after real use.

Invoke these reviews when they add decision value; do not run them automatically in a fixed chain.

## Authority and status

Only an authorized human can approve an artifact or production decision. “Ready for human review” means reviewable, not approved. Evidence findings use validated / not validated / inconclusive. Prototype-only permission is bounded and does not imply production readiness. Classify unknowns as blocking, learning, implementation, or optimization and state which exact decision an unknown blocks.
