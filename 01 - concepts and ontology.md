# Open Meta-Governance Standard – Doc 1  
**Concepts and Ontology (DRAFT)**


## 1. Purpose

This document defines the core concepts and terminology used in the Open Meta-Governance Standard. It describes:

- the actors involved in rule systems,  
- the objects and artefacts associated with rules,  
- the rule environment and rule ecosystem, and  
- the main types of activities and interactions.

It does **not** define lifecycle stages or requirements; those are covered in the lifecycle document.

---

## 2. Actors and roles

### 2.1 Rule user

A **rule user** is any person, group, organisation, process, or technical agent that is subject to rules. Rule users are the entities whose behaviour, decisions, or interactions the rules are intended to influence.

### 2.2 Rule maker

A **rule maker** is any person, group, or organisation responsible for operating the rule system. This includes, for example:

- drafting and updating rules,  
- administering rule operations,  
- monitoring compliance,  
- preparing reports and proposals, and  
- carrying out or coordinating enforcement.

Rule makers act on rules and on rule users, but they are not part of the rule environment (see section 4).

### 2.3 Decision maker

A **decision maker** is any person, group, or organisation with formal authority to approve, reject, suspend, or retire proposed rules. Decision makers act on rule submissions and determine which rules become binding.

Decision makers may be a subset of rule makers, but are defined separately because of their specific authority.

---

## 3. Rule-related artefacts

### 3.1 Rule

A **rule** is a formally adopted statement that constrains or shapes what rule users may, must, or must not do, or how rule resources may be used or configured.

A rule only exists as a rule after a decision maker has approved it (or it has otherwise come into force under the applicable arrangements). Before that point, it is treated as a rule submission.

Rules are understood to be time-bound in practice (they come into force and may later be amended or retired), but this document does not introduce a separate “rule version” concept. Time and change are handled through the lifecycle.

### 3.2 Rule submission

A **rule submission** is a proposal for a new rule or a change to an existing rule that has been prepared by rule makers but has not yet been approved by decision makers.

A rule submission is not binding. It is a pre-approval object that may be:

- approved (becoming a rule),  
- approved with changes,  
- rejected, or  
- sent back for further work.

### 3.3 Rule content

**Rule content** is the information contained within a rule or rule submission. At a minimum, rule content includes:

- which rule users are in scope;  
- which rule resources are in scope;  
- which activities are being targeted;  
- what the rule is trying to achieve in the environment;  
- how enforcement is supposed to work;  
- how the rule itself should be reviewed, amended, or retired.

Later documents specify the structure of rule content in more detail; this document only treats “rule content” as the internal description of a rule.

### 3.4 Meta-rule

A **meta-rule** is a rule whose subject matter is other rules or the operation of the rule system itself. Meta-rules govern, for example:

- who may propose rule submissions;  
- how rule submissions are analysed and decided;  
- how rules are communicated and enforced;  
- how conflicts between rules are handled;  
- how and when rules are reviewed or retired.

In other words, meta-rules are “rules of rules”. The Open Meta-Governance Standard primarily concerns meta-rules and the lifecycle around them.

---

## 4. Environment and ecosystem

### 4.1 Rule resource

A **rule resource** is any non-actor thing that is subject to rules or is relevant to how rules operate. Examples include:

- tools and systems,  
- datasets and models,  
- documents and records,  
- financial assets,  
- physical infrastructure.

Rule users act on or through rule resources; rules may constrain how resources are used or configured.

### 4.2 External factor

An **external factor** is any influence, condition, or actor outside the rule environment that can interact with rule users or rule resources. Examples include:

- wider market conditions,  
- laws and regulations from other regimes,  
- technological shifts,  
- social norms and expectations,  
- physical events (e.g. weather, disasters).

External factors are not part of the rule environment, but they can affect it through external activities.

### 4.3 Rule environment

The **rule environment** is the bounded set of rule users and rule resources that a given rule system is concerned with, and the interactions between them.

Important:

- The rule environment **contains only** rule users and rule resources and their internal interactions.  
- Rule makers and decision makers are **outside** the rule environment. They act on it but do not live inside it.

When we speak of “the environment” in later documents, we mean this rule environment unless otherwise specified.

### 4.4 Rule ecosystem

The **rule ecosystem** is the larger system that includes:

- the rule environment (rule users, rule resources, and their interactions), and  
- the rule makers and decision makers, and the activities they perform around rules.

In short:

> Rule ecosystem = rule environment **plus** the governance actors and their activities.

External factors interact with the rule ecosystem from outside. The Open Meta-Governance Standard is concerned with how governance actors manage rules within this ecosystem.

---

## 5. Activities and flows

### 5.1 Activity

An **activity** is any action or interaction involving rule users, rule resources, rule makers, decision makers, or external factors.

Activities can be:

- observed and described, and  
- linked to rules (as targets, triggers, or enforcement objects).

Different types of activities are distinguished below.

---

### 5.2 Environment activities

**Environment activities** are all activities and interactions that happen **within the rule environment** between things in that environment. This includes:

- a rule user interacting with another rule user;  
- a rule user interacting with a rule resource;  
- a rule resource interacting with another rule resource.

Environment activities represent the full internal dynamics of the rule environment.

---

### 5.3 User activities

**User activities** are the subset of environment activities where rule users are actively doing things. This includes:

- a rule user interacting with another rule user (for example, approving a request, transferring something, making an offer);  
- a rule user interacting with a rule resource (for example, updating a record, deploying a model, operating a system).

All user activities are environment activities, but not all environment activities need to be described as user activities (for example, where a resource behaves in a way not directly controlled by a user at that moment).

---

### 5.4 Rule activities

**Rule activities** are the subset of user activities that are actually affected by rules.

- Not every user activity is covered by rules.  
- Rule activities are those user activities that a rule is explicitly designed to constrain, shape, or enable.

In other words:

> Rule activities ⊂ user activities ⊂ environment activities.

The distinction between user activities and rule activities is important when analysing what the rule system does and does not currently govern.

---

### 5.5 External activities

**External activities** are activities where external factors interact with the rule environment. This includes, for example:

- an external factor interacting with a rule user;  
- an external factor interacting with a rule resource.

Examples:

- A regulator or court outside the environment issuing a decision that changes how a rule user must act.  
- A market shock or physical event changing how a rule resource behaves or is used.

External activities are “outside-in” influences on the rule environment. They can drive environment change and may trigger rule changes.

---

### 5.6 Enforcement activities

**Enforcement activities** are activities where rule makers act directly on rule users in order to increase alignment between user activities and the requirements of rules.

Examples include:

- checking or investigating what rule users did;  
- issuing guidance or warnings in response to non-compliance;  
- imposing sanctions or corrective requirements;  
- requiring remediation or changes in behaviour.

Enforcement activities always involve interaction between rule makers and rule users, and they are oriented toward changing or correcting user activities (in particular, rule activities).

---

### 5.7 Administrative activities

**Administrative activities** are activities that are part of operating the rule system itself. This includes, for example:

- drafting and updating rules;  
- maintaining rule registers and documentation;  
- monitoring user activities and external activities;  
- analysing environment activities and evidence;  
- preparing and submitting rule submissions;  
- coordinating decisions;  
- communicating rules;  
- enforcement activities.

In this framework:

> Enforcement activities are a **subset** of administrative activities.

All direct actions taken by rule makers to align behaviour with rules, or to maintain and operate the rule system, are considered administrative activities.

---

### 5.8 Summary of subset relationships

For clarity:

- **Environment activities**: all internal interactions between rule users and rule resources.  
- **User activities**: all environment activities in which a rule user is actively doing something.  
- **Rule activities**: all user activities that fall under one or more rules.

So:

> Rule activities ⊂ user activities ⊂ environment activities.

And:

- **Enforcement activities** are part of **administrative activities**.  
- Administrative activities span the work that rule makers and decision makers do around rules; enforcement is the part of that work that directly targets rule users’ behaviour.

---

© Kelvin Chau, 2025  
This work is part of the [Open Meta-Governance Standard (DRAFT)](https://github.com/kfkchau/Open-Meta-Governance-Standard/).  
Licensed under [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/)  
For attribution, citation, or inquiries, please refer to:  
🔗 [https://au.linkedin.com/in/kfkchau](https://au.linkedin.com/in/kfkchau)

