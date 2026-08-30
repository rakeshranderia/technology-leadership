# AI Adoption: Governance → Pilot → Adoption → Measurement → Scale

## Context

A professional-services environment of approximately 120 staff was exploring practical use of generative AI across business and technical workflows.

The objective was not simply to introduce an AI product. It was to create a governed way to test where AI could add value, protect organisational information, understand adoption, and make an evidence-based decision about broader scale.

## 1. Governance

The first step was to establish practical guardrails around AI use rather than rely on either unrestricted experimentation or a blanket prohibition.

Controls covered:

- acceptable use;
- organisational data classification;
- privacy and confidentiality;
- data-loss prevention;
- platform suitability and approval;
- Shadow AI risk;
- human review and accountability.

The principle was simple: start with the organisation's existing information-handling rules, then assess whether that information was appropriate for the proposed AI platform and use case.

## 2. Pilot

A governed pilot covered approximately 40 employees within the broader ~120-person organisation.

Use cases included:

- tender and proposal support;
- data analysis and statistical modelling;
- coding assistance;
- quality assurance and review.

The pilot was intended to identify where AI could improve speed, quality or capability while keeping data handling and human oversight visible.

## 3. Adoption

The focus was on useful, repeatable adoption rather than licence assignment or one-off experimentation.

Questions included:

- Are people returning to the tools after initial experimentation?
- Which business use cases are becoming repeatable?
- Where is AI improving productivity or quality?
- Where are users encountering policy, data or platform constraints?
- Are approved tools reducing the incentive to use unmanaged Shadow AI?

Qualitative user feedback remained important because usage telemetry alone does not prove business value.

## 4. Measurement

Microsoft 365 usage reporting was used as part of the adoption-measurement capability.

Using Microsoft Graph and PowerShell, reporting patterns were developed with `Reports.Read.All` and `Invoke-MgGraphRequest`, including CSV extraction from Microsoft 365 usage reports such as:

`getM365AppUserDetail(period='D7')`

The purpose was to create repeatable telemetry that could support questions such as:

- active and repeat usage;
- adoption trends over time;
- Microsoft 365 workload usage;
- whether observed behaviour aligned with the pilot's intended use cases;
- whether broader licensing or rollout could be justified by evidence rather than enthusiasm alone.

This telemetry should be understood as adoption and usage measurement capability. It is not presented as proof of Copilot-specific adoption unless the underlying Microsoft report explicitly supports that conclusion.

## 5. Scale

The intended scale decision combined governance, telemetry and user feedback.

The model was:

- **Expand** use cases showing repeatable value and acceptable risk.
- **Improve controls** where data handling or operating risk needed work.
- **Redesign or stop** low-value or poorly controlled use cases.
- **Measure again** after material changes to platform, users, data, workflow or risk.

## Outcome / Leadership Principle

The core lesson was that AI adoption should be treated as an operating-model problem, not simply a software rollout.

**Success is not the number of licences assigned. It is governed, repeatable usage with evidence of value.**

The approach can be summarised as:

**Governance → Pilot → Adoption → Measurement → Scale**

---

*Rakesh Randeria — practical technology leadership, AI governance and adoption measurement.*
