# Comparison to other frameworks

!!! abstract "Page Summary"

    This page compares the ARC Framework with prominent AI governance frameworks (NIST AI RMF, ISO/IEC 42001, EU AI Act, Dimensional Governance, OWASP Agentic AI, Google SAIF 2.0) across dimensions including approach, prescriptiveness, agentic coverage, and primary audience. Detailed comparisons highlight key differences in methodology, applicability to agentic systems, and best-fit contexts for each framework.

## Comparison dimensions

The frameworks are evaluated across the following dimensions:

- **Core framing/approach** – Is the framework capability‑based, dimension‑based, threat‑based, procedural, or regulatory?
- **Primary audience** – Who is expected to use the framework (e.g., regulators, developers, security professionals, business leaders)?
- **Unit of analysis** – What is the main governance object (entire organisation, AI system lifecycle, agentic workflows, risk catalogue, etc.)?
- **Prescriptiveness** – Does the framework provide high‑level principles, detailed requirements, or a certifiable standard?
- **Coverage of agentic AI specifics** – How explicitly does it address agentic AI capabilities (planning, autonomy, tool‑use)?
- **Evidence/evaluation** – Does the framework cite empirical research or operational data to justify its guidance?
- **Typical artifacts/outputs** – What deliverables or tools does it produce (risk catalogues, controls, certification processes)?
- **Control selection logic** – How are safeguards selected (tiering, capability thresholds, threat severity)?
- **Verification or testing** – Does it specify how to validate controls (testing protocols, audits, red teaming)?
- **Strengths, gaps & best‑fit context** – Qualitative summary of where the framework excels, its limitations, and where it's best applied.

## Quick comparison summary

| Framework | Approach | Prescriptiveness | Agentic Coverage | Primary Audience |
|-----------|----------|------------------|------------------|------------------|
| **ARC Framework** | Capability-centric | Medium–High | Strong | Org. governance, product & security teams |
| **NIST AI RMF 1.0** | Risk-management | Medium | General AI | AI actors (organizations & individuals) |
| **ISO/IEC 42001** | Management system (PDCA) | High (certifiable) | General AI | Organizations developing/providing/using AI |
| **EU AI Act** | Risk-based legislation | High (legally binding) | Emerging guidance | Providers and users of AI in the EU |
| **Dimensional Governance** | Adaptive governance | Low–Medium | Conceptual | Policymakers, oversight & governance leads |
| **OWASP Agentic AI** | Threat-modeling | Medium–High | Strong | Security engineers, red/blue teams |
| **Google SAIF 2.0** | Principle-led defense-in-depth | Medium | Strong | CISOs, security architects & enterprise builders |

## Detailed framework comparisons

### ARC Framework

<details>
<summary><strong>ARC Framework</strong> – Capability-centric governance for agentic systems</summary>

**Core framing/approach:** Capability‑centric governance; maps capabilities→risks→controls with structured implementation

**Primary audience:** Org. governance plus product & security teams

**Unit of analysis:** Capabilities with components & system design

**Prescriptiveness:** Medium–High: risk→control mapping & checklists

**Coverage of agentic specifics:** Strong: capability lens tailored to powers/autonomy

**Evidence/evaluation:** Conceptual with worked examples; no empirical evaluation yet

**Typical artifacts/outputs:** Risk register, capability profile, control tiers/checklists, sign‑off workflow

**Control selection logic:** By capability profile & context; impact×likelihood threshold→minimum control set

**Verification/testing:** Adversarial testing; logging & traceability

**Strengths:** Holistic, capability‑aware; ties risks to controls; governance workflow

**Gaps:** Needs empirical evaluation

**Best‑fit context:** Org‑level cross‑functional governance for varied agentic systems

</details>

### NIST AI RMF 1.0

<details>
<summary><strong>NIST AI RMF 1.0</strong> – Risk-management framework across AI lifecycle</summary>

**Core framing/approach:** Risk‑management framework with four functions (Govern, Map, Measure, Manage) across AI lifecycle; govern is cross‑cutting

**Primary audience:** AI actors (organizations & individuals designing, developing or deploying AI); voluntary & use‑case agnostic

**Unit of analysis:** AI systems & lifecycle stages; categories & subcategories within functions

**Prescriptiveness:** Medium: voluntary guidance and tasks; not certifiable

**Coverage of agentic specifics:** General AI; does not explicitly address agentic autonomy or tool use

**Evidence/evaluation:** Developed via multi‑stakeholder engagement; living document; no formal evaluation

**Typical artifacts/outputs:** Risk‑management tasks, outcomes, profiles and playbook

**Control selection logic:** Risk‑based: organizations identify context, measure & prioritize risks, then manage them

**Verification/testing:** Measure function includes monitoring & testing; encourages performance evaluation and trustworthiness metrics

**Strengths:** Comprehensive lifecycle risk management; flexible, widely adopted

**Gaps:** Not agentic‑specific; lacks concrete controls and certification

**Best‑fit context:** Entry‑level guidance for organizations to build AI risk‑management processes across sectors

</details>

### ISO/IEC 42001

<details>
<summary><strong>ISO/IEC 42001</strong> – Certifiable AI Management System</summary>

**Core framing/approach:** Plan–Do–Check–Act management system; certifiable AIMS; operational, auditable AI governance

**Primary audience:** Organizations of any size developing/providing/using AI; involves top management

**Unit of analysis:** Artificial‑Intelligence Management System (AIMS); AI processes & lifecycle

**Prescriptiveness:** High: prescriptive and certifiable; mandatory policies & documentation

**Coverage of agentic specifics:** General AI governance; not tailored to agentic autonomy

**Evidence/evaluation:** Based on best practices; emphasises continual improvement; no empirical evaluation

**Typical artifacts/outputs:** AIMS documentation, policies, risk registers, annex controls & implementation guidance

**Control selection logic:** Risk‑based planning & treatment within management system; PDCA cycle

**Verification/testing:** Performance evaluation & internal/external audits; certification by third parties; continual improvement

**Strengths:** Formal, auditable governance; harmonizes with other ISO standards; ensures accountability & continual improvement

**Gaps:** Resource‑intensive; heavy documentation; lacks agentic‑specific guidance

**Best‑fit context:** Organizations seeking formal certification & compliance in regulated sectors

</details>

### EU AI Act (with agentic guidance)

<details>
<summary><strong>EU AI Act</strong> – Risk-based legislation with emerging agentic guidance</summary>

**Core framing/approach:** Risk‑based legislation categorising AI systems into unacceptable, high, limited & minimal risk; agentic guidance calls for continuous risk management, dynamic guardrails & real‑time monitoring

**Primary audience:** Providers and users of AI in the EU; regulators & compliance officers

**Unit of analysis:** AI systems defined by risk category; high‑risk AI triggers compliance obligations; agentic systems span ecosystems

**Prescriptiveness:** High: legally binding requirements; strict obligations for high‑risk AI; dynamic compliance for agentic AI

**Coverage of agentic specifics:** Emerging guidance: continuous risk management, dynamic guardrails, real‑time interventions & living documentation

**Evidence/evaluation:** Law enacted; standards under development; no formal evaluation; collaborative standard‑setting

**Typical artifacts/outputs:** Technical documentation, conformity assessments, risk management plans, logs & living documentation

**Control selection logic:** Based on risk category & continuous risk assessment; dynamic oversight & guardrails; shared responsibility between provider & deployer

**Verification/testing:** Pre‑market conformity assessments & post‑market monitoring; real‑time auditing & continuous evaluation

**Strengths:** Legally enforceable; ensures accountability, transparency & fundamental rights; adapting to dynamic agentic systems

**Gaps:** Ambiguity in definitions; heavy compliance burden; not fully adapted to agentic autonomy

**Best‑fit context:** Organisations operating in EU; high‑risk & agentic AI requiring regulatory compliance & continuous monitoring

</details>

### Dimensional Governance

<details>
<summary><strong>Dimensional Governance</strong> – Adaptive governance via continuous dimensions</summary>

**Core framing/approach:** Adaptive governance via continuous dimensions and trust thresholds (authority, autonomy, accountability)

**Primary audience:** Policymakers, oversight & governance leads

**Unit of analysis:** Continuous dimensions (decision authority, process autonomy, accountability)

**Prescriptiveness:** Low–Medium: conceptual thresholds; few concrete controls

**Coverage of agentic specifics:** Conceptual focus on governance dynamics & agent autonomy

**Evidence/evaluation:** Conceptual; no empirical evaluation

**Typical artifacts/outputs:** Dimension definitions; threshold guidance; oversight roles

**Control selection logic:** By dimensional thresholds (higher autonomy ⇒ stricter oversight)

**Verification/testing:** Emphasises oversight & accountability; testing not central

**Strengths:** Clear governance lens; adaptive & policy‑friendly; tracks shifting control & accountability

**Gaps:** Less prescriptive; limited implementation detail

**Best‑fit context:** Regulators & oversight bodies; policy design and audits

</details>

### OWASP Agentic AI (Threats & Mitigations)

<details>
<summary><strong>OWASP Agentic AI</strong> – Threat-modeling for agentic attack surfaces</summary>

**Core framing/approach:** Threat‑modeling of agentic attack surfaces (reasoning, memory, tools, identity, oversight, multi‑agent) with mitigations

**Primary audience:** Security engineers, red/blue teams

**Unit of analysis:** Threats/attack surfaces for agent workflows

**Prescriptiveness:** Medium–High: enumerated threats with mitigation strategies

**Coverage of agentic specifics:** Strong: agent‑specific threats (tools, memory, multi‑agent)

**Evidence/evaluation:** Practitioner‑grounded examples; no formal evaluation

**Typical artifacts/outputs:** Threat navigator, threat/mitigation sheets & red‑team prompts

**Control selection logic:** By threat presence (e.g., tool misuse ⇒ sandboxing, least‑privilege)

**Verification/testing:** Threat‑led testing & red‑teaming against agent surfaces

**Strengths:** Security‑grounded; actionable mitigations for engineers

**Gaps:** Thin governance/process coverage

**Best‑fit context:** Security hardening of agent stacks & tools

</details>

### Google Secure AI Agents / SAIF 2.0

<details>
<summary><strong>Google SAIF 2.0</strong> – Principle-led defense-in-depth for enterprise agents</summary>

**Core framing/approach:** Principle‑led defense‑in‑depth; hybrid approach combining deterministic controls & reasoning‑based defenses; emphasises human controllers, limited powers & observable planning/actions

**Primary audience:** CISOs, security architects & enterprise builders

**Unit of analysis:** Principles & control families across the agent lifecycle

**Prescriptiveness:** Medium: principle‑led control families; not full specification

**Coverage of agentic specifics:** Strong: agent‑explicit principles—human controller, limited powers, observability

**Evidence/evaluation:** Policy/engineering narratives; no formal benchmarks

**Typical artifacts/outputs:** Principles & control families; CISO guidance; dynamic least‑privilege & robust logging

**Control selection logic:** By principles (limit powers; ensure observability; human controller) & hybrid defense

**Verification/testing:** Monitoring & observability of plans/actions emphasised; robust logging & auditing

**Strengths:** Enterprise‑aligned principles; guardrails for agent power & visibility; hybrid defense‑in‑depth

**Gaps:** High‑level; few concrete test harnesses/metrics

**Best‑fit context:** Enterprise security & integration of agent platforms within existing security architectures

</details>
