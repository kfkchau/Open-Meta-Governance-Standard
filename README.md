# Open Meta-Governance Standard (OMGS) — Working Draft

The **Open Meta-Governance Standard (OMGS)** is a domain-agnostic, sector-agnostic **kernel for governing rules themselves**.

This repository is the **canonical home for the OMGS draft documents**:

- the shared **concepts and ontology** for rule systems  
- the **rule lifecycle model** (how rules change over time)  
- the surrounding **intent, scope, and design rationale**

OMGS is designed to sit **underneath** existing legal, policy, and technical frameworks (laws, regulations, standards, internal policies, technical controls) and provide a common “**rules-of-rules**” backbone they can all plug into.

> OMGS focuses on **meta-governance**: the governance of **rule governance**, not the substantive content of any specific rule set.

---

## 1. Naming and history

The underlying ideas in OMGS have been developed and refined over several iterations. The **conceptual core**—the rule ecosystem view and lifecycle understanding—has been in place since 2021. What has changed over time is mostly **language, packaging, and publication intent**, not the core logic.

### 1.1 2021 – “Governance Lifecycle Framework”

- The first complete version of the framework was developed in 2021 under the working name **Governance Lifecycle Framework**.  
- At this stage:
  - the concepts of a **rule ecosystem**,  
  - the **lifecycle view** of how rules evolve, and  
  - a first-principles understanding of how the rule ecosystem works

  were already fully thought through.

- The terminology and framing, however, were tuned more for internal use and expert readers. The language and labels were precise but **not always easily accessible to a wider audience**, which limited how quickly people could “see” the underlying structure.

### 1.2 Late 2025 – “Universal Governance Lifecycle Standard (UGLS)”

- In late 2025, the lifecycle was tightened and published as the **Universal Governance Lifecycle Standard (UGLS)** in the `gov-lifecycle` repository.  
- The focus in this phase was on:
  - sharpening the lifecycle wording, and  
  - improving the writing format towards something closer to a standard.

- UGLS made the structure clearer than the original Governance Lifecycle Framework, but feedback showed that **many readers still found the language dense and demanding**—it required working through the text quite carefully to access the ideas.

- In this period, the author also gained a clearer view of:
  - the **global pain points** across different rule systems, and  
  - the **strategic value** of having a single, portable rule-governance kernel that could sit beneath many domains and sectors.

### 1.3 Early 2026 – “Open Meta-Governance Standard (OMGS)”

- After further reflection, it became clear that the work had effectively become a **new, universal standard** for governing rules themselves.  
- The decision was made to:
  - re-express the same underlying concepts in a way that aligns with **standard publication intent**, and  
  - make the ontology and lifecycle **clearer and more reusable** across domains and institutions.

- The result is the **Open Meta-Governance Standard (OMGS)**:
  - The **content is continuous** with the Governance Lifecycle / UGLS era:  
    - the rule ecosystem view,  
    - the lifecycle stages, and  
    - the first-principles understanding of how rule systems operate  
    are the same ideas, expressed with new language.
  - The terminology, document structure, and explanations have been **reworked to be more legible and standard-like**, while staying faithful to the original reasoning.

UGLS can be seen as an earlier snapshot of the same kernel. OMGS is the current, standard-oriented expression of that kernel.

---

## 2. What’s in this repository

This repo is the **source of truth for OMGS drafts**. The main documents are:

- **Doc 0 – Intent, Scope, and Design Rationale**  
  `00-intent-scope-rationale.md`  
  - Explains **why** OMGS exists.  
  - Describes the problem of slow rule metabolism, gaps in current practice, and the design goals (domain-agnostic, environment-anchored, operational, tool-ready).  
  - Summarises how OMGS relates to existing work (policy cycles, meta-regulation, institutional analysis, legal ontologies) and what is distinctive about OMGS.

- **Doc 1 – Concepts and Ontology**  
  `01-concepts-and-ontology.md`  
  - Defines the **type system** for OMGS:  
    - actors: rule users, rule makers, decision makers, external factors  
    - artefacts: rules, rule submissions, rule content  
    - spaces: rule environment, rule ecosystem  
    - activities: environment activities, user activities, rule activities, external activities, administrative activities, enforcement activities  
  - Makes explicit distinctions such as:  
    - rule environment vs rule ecosystem vs external factors  
    - rule activities ⊂ user activities ⊂ environment activities  
    - enforcement activities as a subset of administrative activities.

- **Doc 2 – Rule Lifecycle Model**  
  `02-rule-lifecycle-model.md`  
  - Defines **what happens to rules over time** using the Doc 1 ontology.  
  - Distinguishes two coupled cycles:  
    - **Rule change proposal cycle**  
      1. Environment change (condition)  
      2. Monitoring (ongoing observation of environment and external activities)  
      3. Analysis (evidence-based understanding and design of candidate rule activities and rules)  
      4. Reporting (converting analysis into rule submissions)  
    - **Rule implementation cycle**  
      5. Decision (acting on rule submissions; creating rules)  
      6. Announcement (formal notification of rule status and timing)  
      7. Communication (making rule content understandable and actionable for rule users)  
      8. Enforcement (aligning rule activities with rule content; feeding back into monitoring)

Additional documents (e.g. rule content schema, lifecycle requirements, domain profiles) may be added as **Doc 3+** in future iterations.

---

## 3. Scope and generality of OMGS

OMGS is designed as a **universal kernel for rule systems**:

- **Vertical coverage (rule layers)**  
  OMGS applies across the layers of rule systems, including:  
  - constitutional principles and foundational charters  
  - statutes and regulations  
  - organisational policies and standards  
  - procedures, playbooks, and workflows  
  - embedded and machine-executable controls

- **Horizontal coverage (subject domains)**  
  OMGS is intended to work across domains such as:  
  - health and care  
  - social services and welfare  
  - migration, borders, and visa systems  
  - consumer and financial services  
  - education and training  
  - labour and employment  
  - digital platforms, data, and AI-mediated services  
  - energy, transport, and other critical infrastructure

- **Sector coverage (institutional settings)**  
  OMGS is sector-agnostic and can be used in:  
  - public-sector policy and administration  
  - private-sector firms and corporate governance  
  - research institutions and ethics frameworks  
  - civil-society and professional bodies  
  - household and family rule systems

OMGS does **not** prescribe any specific substantive rule content (e.g. what “fairness” means in AI, or what eligibility rules should be in welfare). It standardises **how rules and rule changes are managed**, not what the rules say.

---

## 4. Relationship to earlier work (UGLS) and other efforts

### 4.1 UGLS (Universal Governance Lifecycle Standard)

- Earlier lifecycle drafts and materials live in the **UGLS repository**:  
  - `https://github.com/kfkchau/gov-lifecycle/`
- OMGS **supersedes and generalises** UGLS at the conceptual level:  
  - UGLS focused on the lifecycle;  
  - OMGS adds a clearer ontology (Doc 1), a more explicit two-cycle lifecycle (Doc 2), and a framing as an open meta-governance standard (Doc 0).

For lifecycle and ontology reference going forward, OMGS should be treated as the primary expression of the kernel.

### 4.2 OGS and CGL (orientation only)

There are related but distinct ideas and repositories:

- **OGS — Open Governance Standard (umbrella concept)**  
  - A broader effort to organise **language, lifecycle, tasks, and orchestration** for governance.  
  - OMGS can be seen as the **meta-governance kernel** underneath the wider OGS vision.

- **CGL — Common Governance Language**  
  - A shared logical / syntactic layer for expressing rule logic and governance constraints (e.g. in machine-readable form).  
  - OMGS is compatible with CGL or other rule languages but does **not depend** on a specific one.

This repository focuses **only** on OMGS: the concepts and lifecycle kernel for governing rule systems.

---

## 5. License

- **Spec / doc text in this repo:** CC BY 4.0 (see `LICENSE.md`).  

You are free to:

- share — copy and redistribute the material in any medium or format;  
- adapt — remix, transform, and build upon the material for any purpose, even commercially;

under the terms of the **Creative Commons Attribution 4.0 International** license, provided you give appropriate credit.

---

© Kelvin Chau, 2025  
This work is part of the [Open Meta-Governance Standard (DRAFT)](https://github.com/kfkchau/Open-Meta-Governance-Standard/).  
Licensed under [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/)  
For attribution, citation, or inquiries, please refer to:  
🔗 [https://au.linkedin.com/in/kfkchau](https://au.linkedin.com/in/kfkchau)
