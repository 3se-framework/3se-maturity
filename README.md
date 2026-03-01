# 3SE Engineering Maturity Model

The 3SE engineering maturity model provides organizations a roadmap to transition from unstructured system, safety and security engineering activities to fully integrated and continuously evolving engineering activities.
It consists of the following 6 stages:

---

## Stage 1 — Ad hoc (Engineering 0.0)

The organization has no formalized activities in system engineering, safety engineering, or cybersecurity engineering.

**Business gains of being here**
* None. This stage offers no sustainable competitive or compliance advantage.

**Business consequences of staying here**
* Engineering decisions rely on individual expertise and informal communication.
* There is no shared understanding of risks, requirements, or system boundaries. This leads to:
  * Unpredictable project costs and schedules
  * Recurring defects that are discovered late
  * Near-total inability to demonstrate compliance to customers or regulators
* Onboarding new engineers is slow and knowledge walks out the door when people leave.

---

## Stage 2 — Document based (Engineering 1.0)

The organization has a description of activities in system engineering, safety engineering, or cybersecurity engineering that relies on document versioning and baselining.

**Business gains of being here**
* Ability to demonstrate a baseline level of compliance to customers or regulators.
* Engineering decisions and rationale are traceable over time, reducing dependency on individual memory.
* A shared reference exists for teams to align on scope, requirements, and responsibilities.

**Business consequences of staying here**
* Documents are notoriously hard to keep synchronized.
* A change in one document rarely propagates correctly to related documents, creating silent inconsistencies between system specifications, safety analyses, and security assessments.
* Teams spend significant effort in review meetings reconciling conflicting documents.
* Compliance demonstrations are labor-intensive, and the effort must largely be repeated for each project or product variant.

---

## Stage 3 — Requirement based (Engineering 2.0)

The organization has a description of activities in system engineering, safety engineering, or cybersecurity engineering based on requirement versioning and baselining. However, these engineering disciplines are not integrated together, leading to risk opacity.

**Business gains of being here**
* Requirements management tools (such as DOORS or Polarion) provide traceability within each discipline.
* Impact analysis of changes becomes possible within a single discipline, reducing the risk of regressions.
* Compliance evidence is more structured and easier to produce for audits and certifications.

**Business consequences of staying here**
* A change in a system requirement may invalidate a safety argument without anyone noticing.
  * The links between system requirements, safety requirements, and security requirements remain informal or nonexistent.
* Risk assessments from safety and security teams are produced in separate silos and cannot be easily consolidated into a holistic picture.
  * This makes it difficult to answer the fundamental question: *are we building a safe and secure system?*
* Decision-makers lack visibility, and late-stage integration issues remain common.

---

## Stage 4 — Model based (Engineering 3.0)

The organization has a description of activities in system engineering, safety engineering, or cybersecurity engineering based on model element versioning and baselining. Processes are integrated together at the level of activities, but lack consistency in vocabularies and taxonomies, leading to risk opacity.

**Business gains of being here**
* Models (SysML, AADL, STPA, TARA, etc.) are used across disciplines.
* Activities are noticeably more integrated, enabling earlier detection of cross-discipline issues.
* Simulation and automated analysis become possible, reducing the cost of late design changes.
* Product variants and configurations can be managed more efficiently through model reuse.

**Business consequences of staying here**
* Each discipline has its own modeling conventions, naming schemes, and risk taxonomies.
  * A "hazard" in the safety model may not map cleanly to a "threat" in the security model, and neither may align clearly with a system "failure mode."
  * This means risk cannot be consolidated and reasoned about as a whole.
* Teams spend time translating between models rather than engineering.
* Automated consistency checks remain limited because the semantic foundation is missing.

---

## Stage 5 — Semantic based (Engineering 4.0)

The organization has a description of activities in system engineering, safety engineering, or cybersecurity engineering based on semantic versioning and baselining. Processes are integrated together at the level of vocabulary, leading to risk-centric engineering. However, knowledge is not yet managed at the organizational level.

**Business gains of being here**
* The organization can reason about risk in a unified, consistent way across system, safety, and security engineering.
* Cross-discipline reviews become faster and more productive.
* Compliance artifacts can be generated more automatically because concepts are formally defined and linked.
* A single change propagates consistently across all disciplines, eliminating silent inconsistencies.

**Business consequences of staying here**
* This semantic foundation lives within individual programs or teams rather than being shared across the organization.
* Each new project must rebuild or rediscover parts of the knowledge base.
* Lessons learned do not accumulate systematically.
* The organization cannot yet leverage its full engineering history to make better decisions on future programs.

---

## Stage 6 — Knowledge based (Engineering 5.0)

The organization has a description of activities in system engineering, safety engineering, or cybersecurity engineering based on knowledge facts and rules versioning and baselining. Processes are integrated together at the level of the organization's infrastructure, enabling continuous integration and deployment of new facts and rules.

**Business gains of being here**
* Validated engineering patterns are reused across programs, significantly reducing ramp-up time on new projects.
* New regulatory requirements or technological changes are integrated with minimal disruption, as the knowledge base evolves continuously.
* Lessons learned are captured and deployed organizationally, turning experience into a lasting competitive advantage.
* AI-assisted engineering and automated compliance become achievable, further reducing the cost and effort of certification.
* The organization as a whole learns and improves, rather than relying solely on the memory and availability of individual experts.
