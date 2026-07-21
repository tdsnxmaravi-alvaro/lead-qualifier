# Newforma Reseller Qualification — Executive Summary

**TD Synnex Datech | AEC Business Unit | April 2026**

---

## Challenge / Opportunity

TD Synnex Datech carries **Newforma** — the #1 AEC project information management platform (4.5M users, 20M projects, 1B emails managed) — but has no systematic way to identify which resellers in the existing 2,000+ partner base can actually sell it. These resellers transact through other TD Synnex business units, not Datech. Their end users — hospitals, fabs, airports, campuses — are running multi-billion-dollar construction programs and managing RFIs, submittals, and project documents through email and SharePoint. That's exactly where Newforma wins. Traditional qualification is manual, slow, and anecdotal — resulting in missed cross-sell and unfocused BDM outreach across a $9.8B+ reseller universe.

---

## Goal

Qualify the top 50 resellers (by net sales) for Newforma partnership potential using evidence-backed scoring — identifying which accounts have end users with active construction programs, document management pain, and CDE displacement opportunities — and deliver BDM-ready intelligence per account: scored profiles, Newforma product recommendations (Konekt/Project Center/Constructex), competitive landscape (Aconex, ProjectWise, Procore, SharePoint), and personalized talking points citing specific end-user projects by name.

---

## What We Did

A Python pipeline processes each reseller through LARA (TD Synnex AI platform) via API. LARA hosts a **Newforma-specific AI agent** with a structured qualification prompt that researches each reseller's end-user base, identifies active construction programs, maps document management pain to Newforma products, detects competing CDE vendors already in play, scores Newforma fit across five weighted dimensions, and generates a BDM talking point per account. Output is a structured Excel with 17 columns per reseller, delivered in automated batches with full audit logs.

| Dimension | Weight | Top Score Signal |
|---|---|---|
| End-User AEC Project Activity | 30% | Named construction programs >$100M with verified details |
| Document Management Pain | 25% | End users on SharePoint/email/Aconex for project docs; Doc Control job postings |
| Reseller AEC Capability | 20% | Already sells Autodesk, Bluebeam, Procore, or has AEC practice |
| Competitive Displacement | 15% | Aconex→displace · Procore→complement · SharePoint→upgrade |
| Program Scale & Complexity | 10% | Multi-billion, multi-site, multi-GC programs (hospitals, fabs, airports) |

| Tier | Score | Action | Profile |
|------|-------|--------|---------|
| **A** | 80–100 | Immediate outreach | AEC-ready: named customers, tech partnerships, active markets |
| **B** | 60–79 | Validate specific products | Strong signals but needs validation on specific portfolio fit |
| **C** | 40–59 | Single-product entry | No AEC practice, but end users with active construction justify a focused entry |
| **D** | 0–39 | Archive | No evidence of AEC potential |

---

## Outcome — 50-Reseller Run

✅ **4 B-Tier identified** — resellers whose end users have exceptional construction evidence; ready for BDM validation and Newforma enablement.
✅ **15 C-Tier validated** — pure IT VARs with owner-side entry points; end users running active multi-billion-dollar capital programs.
✅ **Dominant pattern confirmed:** the pitch is not "sell CDE software" — it's "your end users are drowning in email-based project coordination on billion-dollar programs — Newforma fixes that, and you're already their IT partner."
✅ **Product signal:** Newforma Konekt (Info Track + CA Track) recommended 50/50 as universal owner-side entry.
✅ **Priority accounts for immediate BDM outreach:** Logicalis, Sayers, Mark III, Computacenter.

| Tier | Count | % |
|------|-------|---|
| **B (60-79)** | 4 | 8% |
| **C (40-59)** | 15 | 30% |
| **D (0-39)** | 31 | 62% |

### B-Tier Highlights

| Reseller | Score | Net Sales | Key End-User Evidence |
|---|---|---|---|
| **Logicalis** | 64 | $607M | Intel $20B+ Ohio fabs; Cleveland Clinic Neurological Institute |
| **Sayers** | 63 | $152M | Southern Company Vogtle nuclear (largest US nuclear build); United Airlines ORD21 airport |
| **Mark III** | 62 | $203M | Mayo Clinic "Bold Forward" campus (Foster+Partners); Houston Methodist Centennial Tower |
| **Computacenter** | 61 | $972M | Ford BlueOval City EV/battery mega-program; AstraZeneca ~$1B Singapore facility; HDR (A/E firm) |

### Top C-Tier Highlights

| Reseller | Score | Net Sales | Key End-User Evidence |
|---|---|---|---|
| **Agilant** | 57 | $108M | NYC H+H $923M RBG Hospital; Miami-Dade EPA consent decree water/sewer CIP |
| **Trafera** | 56 | $173M | CCSD 15 "Moving 15 Forward" district-wide capital program |
| **EchoStor** | 52 | $368M | Eversource Revolution Wind offshore; Beth Israel Lahey $600M+ Klarman Building |
| **Technologent** | 49 | $413M | Micron $100B New York megafab + $15B Boise R&D fab |
| **WWT** | 43 | $2.23B | Google multi-site, multi-billion data center construction program |

---

## Key Takeaway

The pilot validated both the methodology and the Newforma opportunity. Every B-Tier and C-Tier reseller has at least one end user with an active, named, multi-million-dollar construction program — yet none currently sells a single CDE product. The end users (Intel, Mayo Clinic, Southern Company, Kaiser, Google, Micron) are managing project documents through email and SharePoint — exactly where Newforma Konekt displaces. Zero A-Tier is expected: these are IT VARs, not AEC resellers; B-Tier broke through on exceptional end-user evidence alone. The AI pipeline turns a weeks-long manual research process into hours and delivers intel precise enough for a cold call. Ready to scale to the remaining 1,950.

---

## ROI

AI-powered Newforma qualification vs. traditional channel development — faster identification, evidence-backed prioritization, BDM-ready output, scalable to 2,000+ resellers at the same marginal cost.

| | AI Pipeline | Manual |
|---|---|---|
| **50 resellers** | 2.5 hrs / ~$50 | 25-50 hrs / $1,875-$3,750 |
| **Output** | 17-col Excel + talking points + cited sources | CRM notes, unstructured |
| **Scale to 2,000** | Same marginal cost | 6+ months of BDM calendar |

---

## Measurement (To Be)

- # of Newforma resellers recruited with active pipeline within 90 days
- Time from qualification output to first reseller engagement
- Revenue attributed to accounts identified through this process
- MDF secured from Newforma for targeted recruitment campaigns
