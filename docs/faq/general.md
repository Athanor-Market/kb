# Athanor — General FAQ

_Plain‑language answers about our OTC marketplace & protocol_  
_This FAQ is for convenience only. For binding terms, see the Master ToS, Privacy Policy, and the Tokenized Promise Agreement (TPA)._

---

## 1) What is Athanor?

Athanor is an **over‑the‑counter (OTC)** marketplace and protocol that helps **Founders**, **Investors**, and **Advisors** collaborate using **Tokenized Promises (TPs)** — simple on‑chain agreements for funding and milestone‑based releases or revenue‑sharing. Athanor provides **technical capabilities** and safety workflows. **We do not issue TPs** and we do not provide investment advice.

---

## 2) Who are the main participants and what do they do?

- **Founder** — creates a **Data Room**, Lists the project into **Abyss**, configures TP terms in the **Tokenized Promise Wizard**, and forms an SPV that **issues** the TP.
    
- **Investor** — evaluates opportunities, contributes **USDT‑TON**, and later **claims** any distributions. Investor status in our system is **binary**: **Qualified Investor (QI)** or **non‑QI** — Issuers may gate participation to QI only.
    
- **Advisor** — offers add‑on services directly to Founders through the marketplace.
    
- **CoA (Circle of Alchemists)** — Athanor’s safety committee that, during open beta, can verify evidence, implement approved milestone changes, and perform **security migrations** without changing economics.

---

## 3) What is a Data Room? Who can see it?

A **Data Room** is a project’s workspace inside Athanor that only **authorized (signed‑in)** users can access. Most sections are visible to authorized users; **private** areas — like **Metrics**, **Private Groups**, and certain diligence files — are restricted to the project’s roles.

---

## 4) What exactly is a Tokenized Promise?

A **TP** is an on‑chain agreement issued by the Founder’s **SPV**. It can be configured as either:

- **Equity** — a **SAFE‑like** instrument (post‑money or pre‑money) or a fixed **Direct Equity** percentage; or
- **Revenue‑Share** — a defined percent of **Net Revenue**, with a payment cadence, optional ROI cap, and minimum payout threshold.  
    Funds sit in **Escrow** and are unlocked by **Milestones** that the Founder defines in the Wizard and that CoA or protocol governance verifies.

---

## 5) Does Athanor custody funds or tokens?

No. Athanor is **non‑custodial**. Investors may fund from an **exchange account** directly to the TP address, but TP units are deliverable **only** to a **verified non‑custodial wallet**. If a wallet is not linked, units remain held by the contract in a non‑transferable, claim‑pending state until a wallet is provided.

---

## 6) Which currencies and rails are supported?

- **Platform services** (passes, Advisor orders) — payable in **USD** or **crypto** (e.g., USDT‑TON; other options via conversion services you choose).
- **Investments into TPs** — **USDT‑TON only**.
- **Gas** — always paid by users.

---

## 7) What fees does Athanor charge?

- **Issuance fee — 2%** on the relevant entry event.
- **Success fee — 7%** on **one** of: (i) release of funds from Escrow to the Founder, **or** (ii) distribution of revenue to Investors.
- **Allocation, not duplication** — each fee is applied **once** per event and may be **split** between Founder and Investors in **any proportion** that sums to the fee (for example, a 3% + 4% success split).
- **Advisor marketplace** orders include an **8%** platform fee.

---

## 8) How do refunds work?

- **Before Soft Cap** — Investors can withdraw contributions at any time (minus network gas and already‑incurred fees).
    
- **After Soft Cap** — funds are in Escrow. Refunds are possible if the **Founder breaches** the TPA (for example, missing a milestone beyond the configured **cure window**). Refunds draw from **remaining Escrow** after applicable fees.

---

## 9) Can milestones be changed after launch?

Yes — **with guardrails**. Investors can **request** changes in a **Private Group**. A change takes effect only if **the Founder consents** and the **holder consent threshold** set in the TPA is met (default example: 60% of invested units). During open beta, CoA implements approved changes; later, protocol governance may handle this on‑chain.

---

## 10) What is GemScore and the GemScore Report (GSR)?

**GemScore** is the output of **GemSeeker AI**, our multi‑agentic due‑diligence workflow. GSR provides a **0–100** score built from **10 weighted factors**, with a detailed narrative, factor‑level suggestions, and **version history**. Subscriptions include an **auto‑generated Investor Memo**; enterprise plans add options like **BYOK/VPC self‑host, SSO/SCIM, audit logs, API, and webhooks**. 

---

## 11) Is the GSR investment advice?

No. GSR is **informational** — an AI‑assisted opinion to help you think. It is **not** a recommendation or guarantee, and it can be wrong or outdated. Always do your own diligence.

---

## 12) What is the Universal Compliance Vehicle (UCV)?

UCV is an **on‑chain policy layer** that enforces the Issuer’s settings: **QI‑only** gating, jurisdiction blocks, min / max investors, ticket limits, transfer rules, legends, and optional **Shariah** constraints. If the Issuer sets **U.S. Exemption = N/A**, U.S. persons are automatically **blocked** and U.S. solicitation must be disabled.

---

## 13) Do you support Shariah‑compliant structures?

Yes — optional **Shariah Module**. The default mode is **Musharakah** (joint venture): profits share by an agreed ratio; **losses follow capital shares**; **no riba, no excessive gharar, no maysir**, and excluded sectors can be specified. Non‑compliant incidental income is **purified** to a disclosed wallet. Other patterns (Mudarabah, Murabaha, Ijara, Wakala, Istisna’) are available if the Issuer enables them.

---

## 14) Where is Athanor available?

Athanor is **not** available in certain **prohibited jurisdictions** (including the Russian Federation, North Korea, and Iran) and may be further restricted by an Issuer’s UCV settings or by law. You are responsible for confirming local eligibility.

---

## 15) What KYC / AML checks are required?

- **Founders** — required to list and configure a TP.
    
- **Investors** — required to invest and to claim distributions.
    
- **Advisors** — required to publish services.  
    Checks are handled through integrated providers. If verification fails or risk is detected, access may be paused or denied.

---

## 16) How are Advisor services handled?

Advisors contract **directly** with Founders. Athanor facilitates discovery, payment, and delivery but is **not** a party to the engagement. Advisors must keep **non‑public** materials confidential.

---

## 17) What happens if something goes wrong — a bug, exploit, or outage?

We operate an incident‑response process. For material security events, we provide prompt user notice when lawful and may **pause features** or **migrate contracts** to protect users. Report vulnerabilities to **[coa@athanor.market](mailto:coa@athanor.market)** (safe‑harbor terms apply in our VDP).

---

## 18) Is there an insurance fund?

No — there is **no insurance fund** at launch. We may explore a reserve mechanism later, but today you should assume **full risk**.

---

## 19) What are passes, tiers, and what do I actually get with a GemScore Pass?

A **GemScore Pass** runs one **full 10‑factor analysis** for a project with **version history**, **factor‑level fixes**, **external enrichment**, and **encryption in transit / at rest**. Subscriptions add an **Investor Memo** and more passes per month; enterprise plans add **API / webhooks** and security options such as **BYOK / VPC / self‑host, SSO / SCIM, audit logs, and SLA**. Check the in‑app purchase pages for current pricing and limits.

---

## 20) How do I request sensitive information from a Founder?

Issuers can set a **Sensitive‑Access ticket threshold** in the TPA. Investors whose **aggregate ticket** meets or exceeds that number gain a contractual right to request reasonable, deal‑related access to a **Secured Portal**. The Issuer must respond within the stated SLA.

---

## 21) What are common risks I should understand before using Athanor?

Digital assets and early projects carry **high risk** — including **total loss**. Smart‑contract bugs, validator or network failures, exchange or stablecoin issues, inaccurate evidence, and Founder under‑performance are all possible. There is **no guarantee** of conversion, liquidity, milestone unlocks, or revenue distributions.

---

## 22) Can I transfer or trade my TP units?

**Secondary transfers** are disabled at launch. If enabled later, transfers will require KYC / QI checks and may be limited to **whitelisted wallets** under the UCV rules.

---

## 23) How do disputes get resolved?

The TPA uses **Delaware law** and **binding arbitration** (AAA) in **Wilmington, Delaware**. Either party may seek temporary injunctive relief to preserve the status quo pending arbitration.

---

## 24) Who do I contact for help or legal notices?

- **Support & general** — in‑app chat or email noted on your account.
- **Security & abuse** — **[coa@athanor.market](mailto:coa@athanor.market)**.
- **Legal notices** — **[legal@athanor.market](mailto:legal@athanor.market)** and our registered address (see ToS).

---

## 25) Any final reminders?

- Athanor is **experimental — open beta**. Features can change, and some actions run via CoA until fully automated.
    
- Athanor is **not** a broker, adviser, exchange, or custodian — we provide **tools**, not recommendations.
    
- Read the **ToS**, **Privacy Policy**, and **TPA** before participating.