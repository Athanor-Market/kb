# Athanor Knowledge Base (KB) — Docs & Specs

**OTC marketplace & non‑custodial protocol for milestone‑based funding and revenue‑share.**
**Networks:** **Custom Tokenized Promises at any networks**
**Why:** tech transport only; we prioritize **lower fees**, **faster execution**, and **less crowded networks** first.

[![OTC](https://img.shields.io/badge/OTC-marketplace-black)](#)
[![Non‑custodial](https://img.shields.io/badge/Non‑custodial-yes-brightgreen)](#)
[![Open Beta](https://img.shields.io/badge/Status-open%20beta-orange)](#)

This public repository is the **canonical documentation** for **Athanor Market, Inc.** It covers legal terms, product guides, and role‑specific FAQs. Smart‑contract specifications and addresses will be published here as they roll out.

* Docs live at: `docs/`
* FAQs (by role): `docs/faq/`
* Smart‑contract specs: `spec/` *(scaffolded; empty for now)*

---

## What is Athanor (one‑liner)

**Athanor is an OTC, non‑custodial protocol for funding startups via Tokenized Promises (equity SAFE/SAFT/direct or revenue‑share), with milestone‑based escrow unlocks, an on‑chain compliance layer (UCV), and AI due diligence (GemScore Report).**

---

## Networks & Roadmap

* **Current:** **TON**

  * **Why TON first:** low transaction fees, fast finality, mature USDT‑TON rail, and room to innovate without congestion.
  * **Transport‑only stance:** the chain is implementation infra — Athanor remains a **non‑custodial OTC protocol**, not an exchange or broker.

* **Planned 2025:** **Solana** and **EVM (Ethereum‑compatible chains / L2s)**

  * **Selection criteria:** fee efficiency, throughput/latency, wallet availability, stablecoin rails, reliability, and ecosystem risk.
  * **Scope:** new TPs can be deployed on supported networks as they come online. Existing TPs remain on their original chain; any cross‑network migration would require explicit governance/consent and security review.
  * **Goal:** preserve the same **TPA semantics**, **UCV gating**, and **milestone logic** across networks.

> Dates and chain list are targets, not promises. Final support depends on security, stability, and legal reviews.

---

## Repository structure

```
docs/
├─ faq/
│  ├─ advisor.md
│  ├─ ambassador.md
│  ├─ founder.md
│  ├─ general.md
│  └─ investor.md
├─ ambassador_tos.md
├─ nda.md
├─ privacy_policy.md
├─ tos.md
└─ tpa_template.md
spec/
.gitignore
```

---

## Start here (quick links)

### Legal & Platform

* **Terms of Service (ToS):** [`docs/tos.md`](docs/tos.md)
* **Privacy Policy:** [`docs/privacy_policy.md`](docs/privacy_policy.md)
* **Global Platform NDA:** [`docs/nda.md`](docs/nda.md)
* **Ambassador Program Terms:** [`docs/ambassador_tos.md`](docs/ambassador_tos.md)

### Funding Instruments

* **Tokenized Promise Agreement — Template (TPA v2.0):** [`docs/tpa_template.md`](docs/tpa_template.md)
  *Supports Revenue‑Share, SAFE/SAFT, Direct Equity; Milestones; UCV; optional Shariah (Musharakah).*

### FAQs (role‑specific)

* **General FAQ:** [`docs/faq/general.md`](docs/faq/general.md)
* **Founder FAQ:** [`docs/faq/founder.md`](docs/faq/founder.md)
* **Investor FAQ:** [`docs/faq/investor.md`](docs/faq/investor.md)
* **Advisor FAQ:** [`docs/faq/advisor.md`](docs/faq/advisor.md)
* **Ambassador FAQ:** [`docs/faq/ambassador.md`](docs/faq/ambassador.md)

### Smart contracts

* **Specs & addresses (rolling):** [`spec/`](spec/) *(published progressively; empty scaffold now)*

---

## Key concepts & keywords

* **Athanor Market** • **OTC marketplace** • **non‑custodial protocol**
* **Networks:** **TON (live)** • **Solana (planned)** • **EVM / Ethereum L2s (planned)**
* **USDT–TON** rail • **gas fees** • **fast finality**
* **Tokenized Promise (TP)** • **Escrow** • **Milestones & unlocks** • **Pull‑Claim**
* **Instruments:** **Revenue‑Share**, **SAFE** (pre/post‑money), **SAFT**, **Direct Equity**
* **GemScore Report (GSR)** — AI due diligence, **0–100** across **10 weighted factors**; report price **\$39** (subject to in‑app pricing)
* **UCV — Universal Compliance Vehicle**: **QI gating**, **jurisdiction blocks**, **min/max investors**, **min/max tickets**, **transfer rules**, **legends**, **Shariah modules (Musharakah)**
* **CoA — Circle of Alchemists** (open‑beta safety ops)
* **Regions:** not offered where prohibited (incl. Russian Federation, North Korea, Iran)
* **Dispute venue:** Delaware (AAA arbitration)

---

## Safety, compliance & regions

* **Non‑custodial:** users hold their own wallets; investments in **USDT–TON** on TON today; users pay gas.
* **Escrow & verification:** releases only on **objective, verified Milestones**; **CoA** can verify and perform security migrations in open beta.
* **UCV (on‑chain rules):** QI‑only toggle; U.S. posture (e.g., Reg D 506(b)/(c), Reg S, Reg A, Reg CF via portal, or **N/A** to block U.S.); geo blocks; min/max investors & tickets; transfer controls; legends; optional **Shariah Musharakah**.
* **Restricted regions:** platform unavailable in certain jurisdictions; Issuers may add more blocks.
* **High risk:** early projects and digital assets can result in **total loss**; no insurance fund at launch; no guarantee of conversion, liquidity, or distributions.

---

## Contributing

We welcome **issues/PRs** for clarity, typos, and structure.

* Don’t include confidential or personal data.
* Legal wording may be reviewed by counsel; we may decline changes that diverge from the live product.
* **Security reports:** do **not** open a public issue — email **[coa@athanor.market](mailto:coa@athanor.market)** (VDP safe harbor applies).

---

## License & contacts

* Content © **Athanor Market, Inc.** — all rights reserved unless a file states otherwise.
* **Security:** `coa@athanor.market`
* **Legal:** `legal@athanor.market`

---

## JSON‑LD 

```json
{
  "@context": "https://schema.org",
  "@type": "Organization",
  "name": "Athanor Market, Inc.",
  "url": "https://github.com/Athanor-Market/kb",
  "description": "OTC, non-custodial protocol for milestone-based funding and revenue-share via Tokenized Promises. Live on TON; Solana and EVM support targeted for 2025.",
  "knowsAbout": [
    "TON blockchain",
    "Solana",
    "EVM",
    "Ethereum L2",
    "Tokenized Promise",
    "Revenue-Share",
    "SAFE",
    "SAFT",
    "UCV compliance"
  ],
  "contactPoint": [
    { "@type": "ContactPoint", "email": "legal@athanor.market", "contactType": "legal" },
    { "@type": "ContactPoint", "email": "coa@athanor.market", "contactType": "security" }
  ]
}
```

**SoftwareApplication (GemScore):**

```json
{
  "@context": "https://schema.org",
  "@type": "SoftwareApplication",
  "name": "GemScore Report",
  "operatingSystem": "Web",
  "applicationCategory": "BusinessApplication",
  "offers": { "@type": "Offer", "price": "39", "priceCurrency": "USD" },
  "description": "AI due diligence (0–100 across 10 weighted factors) with milestone suggestions; used to list projects in Abyss."
}
```
