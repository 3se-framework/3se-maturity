# 3SE Engineering Maturity Model

The 3SE engineering maturity model provides organizations a roadmap to transition from unstructured system, safety and security engineering activities to fully integrated and continuously evolving engineering activities.
It consists of the following 6 stages:

---

## Stage 1 — Ad hoc (Engineering 0.0)
The organization has no formalized activities in system engineering, safety engineering, or cybersecurity engineering.

> Decisions rely entirely on individuals. No shared understanding of risks, requirements, or boundaries.

**Business gains**
* None. This stage offers no sustainable competitive or compliance advantage.

**Consequences of staying**
* Unpredictable project costs and schedules.
* Recurring defects that are discovered late.
* Inability to demonstrate compliance to stakeholders.
* Onboarding new engineers is slow.
* Knowledge walks out the door when people leave.

---

## Stage 2 — Document based (Engineering 1.0)

The organization has a description of activities in system engineering, safety engineering, or cybersecurity engineering that relies on document versioning and baselining.

> Engineering decisions and rationale become traceable through shared documents.

**Business gains**
* Ability to demonstrate a baseline compliance to stakeholders.
* Decisions and rationale are traceable over time, reducing dependency on individual memory.
* Shared reference exists for teams to align on scope, requirements, and responsibilities.

**Consequences of staying**
* Silent inconsistencies between system specifications, safety analyses, and security assessments.
* Significant effort spent reconciling conflicting documents.
* Compliance demonstrations are labor-intensive and must largely be repeated for each project or variant.

---

## Stage 3 — Requirement based (Engineering 2.0)

The organization has a description of activities in system engineering, safety engineering, or cybersecurity engineering based on requirement versioning and baselining. 
However, these engineering disciplines are not integrated together, leading to risk opacity.

> Traceability within each discipline — but disciplines remain siloed, leading to risk opacity.

**Business gains**
* Traceability within each discipline via ALM tools.
* Change impact analysis possible within a single discipline, reducing the risk of regressions.
* More structured compliance evidence for audits and certifications.

**Consequences of staying**
* A system change may silently invalidate a safety or a security argument.
* Risk assessments produced in separate silos — no holistic picture.
* Late-stage integration issues remain common.
* Decision-makers lack visibility.

---

## Stage 4 — Model based (Engineering 3.0)

The organization has a description of activities in system engineering, safety engineering, or cybersecurity engineering based on model element versioning and baselining. 
Processes are integrated together at the level of activities, but lack consistency in vocabularies and taxonomies, leading to risk opacity.

> Activities are integrated across disciplines — but inconsistent vocabularies preserve risk opacity.

**Business gains**
* Models (SysML, AADL, STPA, TARA...) are used across disciplines.
* Earlier detection of cross-discipline issues.
* Simulation and automated analysis reduce the cost of late design changes.
* Variants and configurations managed more efficiently through model reuse.

**Consequences of staying**
* "Hazard", "threat", "failure mode" don't map to each other — risk can't be consolidated.
* Teams spend time translating between models rather than engineering.
* Automated consistency checks remain limited — the semantic foundation is missing.

---

## Stage 5 — Semantic based (Engineering 4.0)

The organization has a description of activities in system engineering, safety engineering, or cybersecurity engineering based on semantic versioning and baselining. 
Processes are integrated together at the level of vocabulary, leading to risk-centric engineering. However, knowledge is not yet managed at the organizational level.

> One vocabulary across all disciplines enables truly risk-centric engineering.

**Business gains**
* Unified, consistent reasoning about risk across all three disciplines.
* Faster and more productive cross-discipline reviews.
* Compliance artifacts generated more automatically from formally defined concepts.
* A single change propagates consistently — no more silent inconsistencies.

**Consequences of staying**
* Semantic foundation lives within programs — not the organization.
* Each new project must rebuild or rediscover parts of the knowledge base.
* Lessons learned don't accumulate — full engineering history is not leveraged.

---

## Stage 6 — Knowledge based (Engineering 5.0)

The organization has a description of activities in system engineering, safety engineering, or cybersecurity engineering based on knowledge facts and rules versioning and baselining. 
Processes are integrated together at the level of the organization's infrastructure, enabling continuous integration and deployment of new facts and rules.

> Continuous integration of engineering knowledge at the organizational level.

**Business gains**
* Validated engineering patterns reused across programs - fast ramp-up on new projects.
* New regulatory requirements integrated with minimal disruption.
* Lessons learned become a lasting organizational competitive advantage.
* AI-assisted engineering and automated compliance become achievable.
* The organization learns and improves beyond individual expert memory.

**Consequences of staying**
This stage represents the current frontier of engineering maturity. No known business consequence of reaching it.

---
Copyright (c) 2022 Regis Casteran

![CC_BY-NC-ND](https://www.3se.info/CC_BY-NC-ND.png)
