# Open Meta-Governance Standard – Doc 0  
**Intent, Scope, and Design Rationale (DRAFT)**

---

## 1. Purpose and positioning

The Open Meta-Governance Standard (OMGS) is a **domain-agnostic kernel** for governing rules themselves.

It is not a sector-specific framework, and it is not a catalogue of “best-practice policies”. Instead, it defines:

- a shared **conceptual vocabulary** for rules, actors, environments, and activities;  
- a **rule lifecycle model** that specifies how rules are proposed, adopted, implemented, and revised.

OMGS is designed to sit **underneath** existing sectoral frameworks (e.g. laws, regulations, AI standards, organisational policies) and provide a consistent “rules-of-rules” backbone they can all plug into.

Doc 0 explains **why OMGS exists**, what problems it addresses, and what is distinctive about its approach. The detailed ontology and lifecycle are specified in:

- **Doc 1 – Concepts and Ontology**  
- **Doc 2 – Rule Lifecycle Model**

---

## 2. Problem: slow rule metabolism

Across domains, many systems suffer from **slow rule metabolism**:

- **Rule accretion** – new rules are added on top of old ones, rarely retired.  
- **Retirement failure** – obsolete or conflicting rules remain in force by default.  
- **Enforcement drift** – what is enforced no longer matches written rules or the reality on the ground.  
- **Crisis-driven updates** – rules only change after visible failures or scandals.

The underlying pattern is the same:

- the **rule environment** (what rule users and rule resources actually do)  
- and **external activities** (what is happening around them)

change faster than the mechanisms for updating and retiring rules.

Most governance regimes **talk** about being “dynamic”, “evidence-based”, and “adaptive”, but:

- they lack a clear, shared **ontology** of what is being governed;  
- they lack an explicit, domain-agnostic **lifecycle** for rule change;  
- they treat monitoring and review as occasional exercises, not continuous functions.

OMGS addresses this by specifying:

- **what exists** in any rule system (Doc 1), and  
- **what must happen** to rules over time (Doc 2).

---

## 3. Gaps in current approaches

Existing literatures and practices address parts of the problem but leave important gaps.

1. **Meta-governance / meta-regulation theory**  
   - Talks about “governance of governance” and “rules of rules”.  
   - Useful conceptually, but often **high-level and descriptive**, without a portable, implementable lifecycle kernel.

2. **Policy / regulation lifecycle models**  
   - Common diagrams show cycles such as “problem → analysis → decision → implementation → evaluation”.  
   - These are often **sector-specific** and lack:
     - a neutral ontology of actors, environments, and activities;  
     - a clean separation of **rule-change proposal** vs **rule implementation** flows.

3. **Institutional analysis frameworks**  
   - Rich thinking about rules, actors, and outcomes (e.g. institutional analysis traditions).  
   - Typically aimed at **analysing** institutions, not at providing a **standardised lifecycle** for how rules should evolve operationally.

4. **Legal / regulatory ontologies and rule languages**  
   - Focus on expressing obligations, permissions, and controls in structured, sometimes machine-readable form.  
   - Rarely define a cross-domain **lifecycle** for rule creation, revision, communication, and enforcement.

In practice, this means:

- every sector reinvents its own meta-governance logic;  
- rule systems are hard to reason about across domains;  
- automation and tooling must guess at lifecycle and context.

---

## 4. Design goals for OMGS

OMGS is designed to fill these gaps with a **minimal, portable kernel** guided by the following goals:

1. **Domain-agnostic**  
   - No assumptions about sector, technology, or jurisdiction.  
   - Works wherever there are rule users, rule resources, and rules.

2. **Universal across rule layers (vertical)**  
   - Applicable from constitutional / foundational rules through:
     - statutes and regulations,  
     - organisational policies and standards,  
     - procedures and playbooks,  
     - machine-executable controls or configurations.

3. **Universal across subject domains (horizontal)**  
   - Applicable to rules governing:
     - health and care,  
     - social services and welfare,  
     - migration, borders, and visa systems,  
     - consumer and financial services,  
     - education and training,  
     - labour and employment,  
     - digital platforms, data, and AI-mediated services,  
     - energy, transport, and critical infrastructure,  
     - and other domains where rule users act on rule resources.

4. **Sector-agnostic (institutional settings)**  
   - Works for:
     - public-sector policy and administration,  
     - private-sector firms and corporate governance,  
     - research institutions and ethics rules,  
     - civil-society and professional bodies,  
     - household or family rule systems.

5. **Operational, not only conceptual**  
   - Defined at a level where:
     - processes can be implemented,  
     - responsibilities can be assigned,  
     - evidence flows can be designed,  
     - and auditability is possible.

6. **Environment-anchored**  
   - All lifecycle stages are explicitly tied to:
     - **environment activities** (what happens inside the rule environment), and  
     - **external activities** (how external factors interact with the environment).  
   - Rule change is always **about** changes in those activities, not abstract slogans.

7. **Behaviourally specific**  
   - Rules are explicitly linked to **rule activities** (the subset of user activities they govern).  
   - This allows clear answers to: “What behaviour exactly is this rule shaping?”

8. **Continuous, not episodic**  
   - Monitoring and analysis are defined as **ongoing administrative activities**, not occasional evaluations.  
   - The kernel assumes **continuous sensing and reconsideration**, not one-off reviews.

9. **Tool-ready and formalisation-ready**  
   - Concepts and lifecycle stages are designed to be:
     - representable in formal rule languages,  
     - integrated into governance platforms and workflows,  
     - compatible with human oversight and automation.

---

## 5. OMGS kernel overview

OMGS consists of two core pieces:

### 5.1 Concepts and Ontology (Doc 1)

Doc 1 defines the **type system** for OMGS. It introduces:

- **Actors**  
  - rule users, rule makers, decision makers, external factors.

- **Rule artefacts**  
  - rules, rule submissions, rule content.

- **Spaces**  
  - rule environment (rule users + rule resources and their internal interactions),  
  - rule ecosystem (rule environment + rule makers + decision makers and their activities).

- **Activities**  
  - environment activities (all internal interactions in the rule environment),  
  - user activities (environment activities where rule users act),  
  - rule activities (the subset of user activities actually governed by rules),  
  - external activities (external factors interacting with the environment),  
  - administrative activities (everything rule makers and decision makers do around rules),  
  - enforcement activities (the subset of administrative activities where rule makers act directly on rule users to align behaviour with rules).

This ontology is **neutral**: it does not assume any particular sector or rule content.

### 5.2 Rule Lifecycle Model (Doc 2)

Doc 2 defines **what happens to rules over time**, using only the concepts from Doc 1.

It distinguishes two coupled cycles inside the rule ecosystem:

- **Rule change proposal cycle**  
  1. Environment change (condition)  
  2. Monitoring (ongoing observation of environment activities and external activities)  
  3. Analysis (evidence-based understanding and design of candidate rule activities and rule content)  
  4. Reporting (converting analysis into rule submissions)

- **Rule implementation cycle**  
  5. Decision (deciding on rule submissions; creating rules)  
  6. Announcement (formal notification of rule status and timing)  
  7. Communication (making rule content understandable and actionable for rule users)  
  8. Enforcement (aligning rule activities with rule content)

Together, these cycles define a **complete rule-change metabolism**:

- changes in environment activities and external activities  
  → are observed (monitoring),  
  → understood and translated into candidate changes (analysis),  
  → proposed formally (reporting → rule submissions),  
  → decided (decision → rules),  
  → made visible (announcement),  
  → made understandable (communication),  
  → and made real in user behaviour (enforcement).

Outputs of implementation (especially enforcement and observed behaviour) flow back as inputs into monitoring and analysis.

---

## 6. Scope and intended use

OMGS is intended for:

- **Designers of governance frameworks**  
  - e.g. regulators, policy designers, corporate governance architects, standards bodies, system owners.  

- **Implementers of rule systems**  
  - e.g. compliance teams, operations leads, product/program owners, infrastructure/system operators.

- **Tool and language designers**  
  - e.g. those building rule engines, policy-as-code systems, governance platforms, and AI governance tools.

The kernel can be used to:

- design or evaluate **governance architectures** in new domains (such as AI systems);  
- benchmark existing rule systems against a **consistent lifecycle**;  
- drive the specification of **further documents** (e.g. rule content schema, lifecycle requirements, domain-specific profiles).

---

