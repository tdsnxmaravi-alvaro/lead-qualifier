# AI-Powered Lead Qualification Engine

### Copilot Studio Multi-Agent System | TD SYNNEX Datech
**Pilot Results & Scale Roadmap — May 2026**

---

## Executive Summary

### Challenge / Opportunity

TD SYNNEX Datech BDMs and their reseller partners carry specialized vendor lines — Newforma and Bricsys — that require deep product and industry knowledge to sell effectively. When a partner identifies a target account, the BDM has no fast, reliable way to validate whether that account is a real opportunity, what specific pain exists, which product fits best, or who the right stakeholder is. Preparation today is manual, inconsistent, and slow — resulting in generic pitches that don't land and partner conversations that stall. At the pace Datech needs to scale these vendor lines, this is a structural blocker.

### Goal

Build an AI-powered qualification tool that instantly generates a **customized opportunity report for any target account** — so every partner conversation and every BDM-led call is grounded in verified, account-specific intelligence. The output must answer: Is this a real opportunity? What is the business case? Which product fits? Who are the key stakeholders? — all backed by cited, publicly verifiable sources.

### What We Did

The solution was built and deployed as a **multi-agent system in Microsoft Copilot Studio**, consistent with TD SYNNEX DART compliance standards. The workflow is designed around how BDMs and partners actually operate:

1. **Partners bring 3–5 target accounts** per cycle — companies they want to pursue with Newforma or Bricsys
2. **The BDM inputs each target** into the Copilot Studio tool by name
3. **The Orchestrator Agent** routes the request to the correct specialized agent based on product — no manual routing required
4. **The specialized agent researches the account** via structured web search across four data tracks (active projects, M&A activity, hiring signals, industry evidence) and applies a vendor-specific scoring matrix
5. **A customized opportunity report is returned** per account, including: active projects and estimated spend, recommended solution with business impact rationale, fit score and tier, and key stakeholders who would benefit
6. **BDM and partner review the reports together** during monthly account mapping calls — turning preparation into a structured, intelligence-driven conversation

| Agent | What It Analyzes | What It Produces |
|---|---|---|
| **Orchestrator** | Routes by vendor, holds conversation context | Seamless experience — no manual agent selection |
| **Newforma Agent** | Construction programs, M&A, facility expansions, document management complexity, CDE competitive signals | Opportunity score, product recommendation (Konekt / Project Center / Constructex), stakeholder map, talking points |
| **Bricsys Agent** | CAD hiring trends, M&A consolidation triggers, manufacturing output, IT infrastructure changes | Opportunity score, BricsCAD edition recommendation (Pro / BIM / Mechanical / Ultimate), key trigger events, talking points |

### Outcome

✅ **Pilot validated — partners confirmed the tool works in the field.**

Kristen shared structured feedback from the reseller enablement teams participating in the pilot:

- **Partners value the in-depth analysis** of how Newforma and Bricsys solutions specifically align with and support their target accounts — intelligence they could not produce on their own at this depth or speed
- **The accuracy of the data has been consistently validated** through pilot engagements; the output is grounded in verifiable, cited sources
- **Partners enter conversations more confidently** — replacing assumption-based pitches with account-specific intelligence tied to real projects and real business situations
- **The tool serves as both a business development resource and an educational tool** — it builds partner expertise on new vendor lines while simultaneously creating pipeline
- **In at least one case, a reseller reviewed the AI-generated report for a current customer and confirmed all information and conclusions were accurate** — directly validating the quality of the output
- While the pilot has not yet produced directly closed deals, the foundational outcomes are in place: **informed conversations, repeatable process, and partner confidence** — the preconditions for revenue

### Key Takeaway

The pilot proved the approach works. Partners now go into account conversations with verified, account-specific intelligence — active projects, estimated spend, recommended solution, business impact, and key stakeholders — instead of generic product knowledge. The tool functions as a force multiplier for both BDMs and partners: it reduces preparation time from days to minutes, builds partner capability on new vendor lines, and elevates every customer conversation. The same Copilot Studio architecture extends to all 5 Datech vendors (Newforma, Bricsys, Unity, DraftSight, Novade) with no infrastructure changes — only new agent prompts.

---

## ROI

AI-powered account qualification vs. traditional BDM preparation — faster, deeper, and scalable across the full partner base and all vendor lines.

| | AI-Powered Tool | Manual Preparation |
|---|---|---|
| **Time per target account** | Minutes | Hours of research per account |
| **Output** | Scored opportunity report: active projects, spend, product fit, stakeholders, talking points — cited sources included | Unstructured notes, anecdotal intel, generic product positioning |
| **Partner enablement** | Builds vendor expertise at scale through every interaction | Requires dedicated training cycles per vendor |
| **Scale** | Same tool, same quality for any account across any vendor line | Grows linearly with BDM headcount |
| **Consistency** | Identical vendor-specific criteria applied to every account | Varies by analyst, by region, by BDM experience level |

---

## Measurement (To-Be)

- \# of partner-identified target accounts qualified per month through the tool
- Time from account submission → first partner-led customer conversation
- Pipeline value attributed to AI-qualified accounts, tracked per vendor per quarter
- Partner adoption rate: % of active partners using the tool in monthly account mapping calls
- MDF secured from Newforma / Bricsys tied to tool-generated pipeline and campaign targets
- Conversion rate: AI-prepared conversations vs. unprepared outreach (A/B baseline)

---

## Next Steps

1. **Scale** — Expand active partner enrollment into monthly account mapping workflow
2. **Extend** — Deploy new specialized agents for Unity, DraftSight, and Novade using the same Copilot Studio architecture
3. **Integrate** — Connect opportunity report output into CRM for pipeline tracking and BDM assignment
4. **Measure** — Establish KPI baseline and begin tracking conversion from AI-qualified accounts vs. historical pipeline
