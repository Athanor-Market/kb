# Tokenized Promise Agreement (Template)

**Athanor — OTC marketplace & protocol**  
**Last updated:** 23 August 2025

> This is a **contractual agreement** between the **Issuer (Founder SPV)** and the **Investors**. It can be configured as either **Equity** (SAFE‑like or Direct Equity) **or** **Revenue‑Share** — pick one in the **Term Sheet**.  
> **Athanor** operates the OTC protocol and user interface that enable this Agreement to run on‑chain. Athanor is **not** the issuer, broker, adviser, custodian, escrow agent, or fiduciary, and is **not** a party to your economic bargain.  
> **All commercial, legal, and regulatory risks are borne by the Issuer and the Investors.**  
> Athanor’s **Terms of Service** and **Privacy Policy** apply at the platform level and are incorporated by reference; this Agreement uses only **unique** terms specific to the instrument and does not restate those policies.

---

## A) Parties

- **Issuer (Founder SPV)** — the special‑purpose entity that issues the TP Units.
- **Investors** — purchasers and holders of TP Units.
- **Operator — Athanor Market, Inc.** (“Athanor”) — operates the OTC protocol and the **CoA** safety committee during open beta.

---

## B) Key Definitions (essentials used below)

- **TP Units** — on‑chain units that record each Investor’s pro‑rata rights under this Agreement.
    
- **Escrow** — contributed funds not yet released to the Issuer.
    
- **Milestone** — a condition that, once verified, unlocks up to a stated percentage of Escrow.
    
- **Claim** — holder‑initiated **pull‑claim** of available distributions.
    
- **QI** — **Qualified Investor** status (binary: **QI** or **non‑QI**) verified per **Schedule S4**.
    
- **Data Room** — the authenticated project space; some modules are visible to authorized users, others are private (e.g., **Metrics**, **Private Groups**, diligence files).
    
- **Universal Compliance Vehicle (UCV)** — the Agreement’s on‑chain rule set (eligibility, jurisdictions, transfer controls, legends, and optional **Shariah** constraints) configured in the Wizard and summarized in **Schedule S4**.
    
- **Secured Portal** — Issuer‑controlled, password‑protected external repository for sensitive materials, if used.

---

## C) **General Conditions** — fixed rules for all deals

**1) Currency, funding, and wallets**

- Contributions are in **USDT‑TON**; users pay network gas.
- **Transit from exchanges** is allowed. Delivery of TP Units requires a **verified non‑custodial wallet**. If a wallet is not linked and KYC/QI is incomplete, units remain **in‑contract** (non‑transferable). Distributions may accrue but cannot be **claimed** until a verified wallet is linked.

**2) Caps, timing, and pre‑Soft Cap withdrawals**

- **Soft Cap**, **Hard Cap**, and the **Raise Window** are set in **S1 — Term Sheet**.
- **Before Soft Cap** — Investors may **withdraw at any time** (network gas and any incurred platform fees are not returned).

**3) Post‑Soft Cap operations**

- After Soft Cap is reached, **Escrow freezes** pending SPV formation verification.
- **Pre‑legal vendor spend** — up to **20% of gross raised** may be paid **direct‑to‑vendor** (e.g., SPV formation, required setup) if approved by the **Founder + holder threshold** in **S7**; **CoA** performs such payments during open beta.
- Escrow releases occur only on **verified Milestones**.

**4) Milestones and changes**

- Milestones live in **S2** and include title, evidence, deadline, and max unlock %.
- **Change rule** — **Founder consent plus the holder threshold in S7** (default 60% of invested units).
- During open beta, **CoA** implements approved changes and verification triggers; when available, protocol governance and/or oracles may replace or supplement CoA.

**5) Distributions**

- **Revenue‑Share** uses **pull‑claims**; cadence, thresholds, and any holdback are in **S3‑RS**.
- Unclaimed amounts remain claimable.

**6) Fees — single event, allocable**

- **Issuance fee — 2%** on the relevant entry event.
- **Success fee — 7%** on **one** of: (i) **Escrow → Issuer** release **or** (ii) **Revenue → Investors** distribution.
- Each fee is applied **once per event** and can be **allocated** between Founder and Investors so the split **sums to the fee**. The actual split is set in **S6** and enforced on‑chain.

**7) Evidence, requests, and audit**

- Acceptable sources appear in **S5 — Evidence Menu**.
- **CoA** may **request evidence at any time** and conduct a **reasonable audit**. Non‑cooperation may pause releases and can result in **pro‑rata refunds** of remaining Escrow where appropriate.

**8) Refunds on breach**

- **After Soft Cap** — refunds may be made **only** if the Issuer **breaches** (e.g., misses a Milestone beyond the **Cure Window** in **S1**) and then from **remaining Escrow** after applicable fees.

**9) Compliance — UCV on‑chain**

- The contract enforces **UCV** settings from **S4** — QI‑only toggle, jurisdiction blocks, min/max investors, ticket limits, transfer rules, legends, and optional **Shariah** module.
    
- **U.S. investors.** The Issuer must choose a **U.S. path** in **S4**. If **U.S. Exemption = N/A**, the Wizard must: **block U.S. persons**, disable U.S. solicitation, and stamp “**Not offered in the United States**.” The Issuer is solely responsible for any required filings, legending, and QI verification under the chosen path.

**10) Shariah (optional) — Musharakah first**

- If **Shariah Module = ON**, **S8** applies. Default mode is **Musharakah** (joint venture):
    
    - **Profit** shared by agreed ratio; **losses** borne **pro‑rata to contributed capital**, including **documented** non‑cash contributions (e.g., time, services, IP) as valued **ex‑ante**.
    - **No riba, no excessive gharar, no maysir, no prohibited sectors.**
    - **Purification** of incidental non‑compliant income to a disclosed wallet; optional **Shariah Advisor** may issue review notes.
        
- Other optional patterns (e.g., **Mudarabah**, **Murabaha**, **Ijara**, **Wakala**, **Istisna’**) are selectable in **S8**.

**11) Founder covenants and Sensitive‑Access right**

- Issuer covenants: disclosures are **true and not misleading**; releases used **only** as disclosed; **books and records kept**; **material changes** posted in the Data Room; cooperation with verification.
    
- **Sensitive‑Access** — any Investor whose **aggregate ticket** equals or exceeds the threshold in **S7** may request reasonably tailored access to sensitive materials in the **Secured Portal**; Issuer must respond within the **SLA** in **S7**. Watermarking and logging are permitted.
    

**12) Upgrades, risk, and disputes**

- **Upgrades / migrations.** **CoA** may migrate contracts for **security, performance, or maintenance** without changing economics or rights. Any change that **affects economics or rights** requires the **consent thresholds in S7**.
    
- **On‑chain prevails** over off‑chain text unless a competent tribunal orders otherwise.
    
- **Risk.** High risk; no guarantee of conversion, liquidity, or revenue; no insurance fund at launch.
    
- **Governing law; disputes.** **Delaware law**; disputes via **AAA arbitration in Wilmington, Delaware**; class‑action waiver to the extent allowed.
    
- **Notices.** Issuer ↔ Investors via Data Room/email. To Athanor (security/abuse): **[coa@athanor.market](mailto:coa@athanor.market)**.

---

# Schedules

---

## **S1 — Term Sheet**

- **Instrument** — ☐ **Equity** (☐ Direct Equity ☐ SAFE Post‑Money ☐ SAFE Pre‑Money) ☐ **Revenue‑Share**
    
- **Soft Cap / Hard Cap** — [ __ / __ USDT ]
    
- **Raise Window** — open [ISO] → close [ISO]
    
- **Cure Window** — [ 30–90 ] days
    
- **Exchange transit allowed** — ☑ Yes
    
- **Non‑custodial wallet required for unit delivery** — ☑ Yes

---

## **S2 — Milestones & Unlocks**

|ID|Milestone|Evidence|Deadline|Max unlock %|
|---|---|---|---|--:|
|M1|[e.g., SPV formed; bank/wallet attestation]|[formation cert; assignment; bank/wallet proof]|[D+30]|[10%]|
|M2|[…]|[…]|[…]|[…]|

- Unlock % is a **cap** — if Escrow balance is lower, only the available balance is released.
    

---

## **S3 — Instrument Add‑on (pick one)**

### **S3‑EQ — Equity**

- **Direct Equity** — **Equity %**: [ __% ]; share class / rights / information rights; closing mechanics and cap‑table update timing.
    
- **SAFE‑like** — **Type**: [ Post‑Money / Pre‑Money ]; **Valuation Cap**: [ __ ]; **Discount Rate**: [ __% ]; optional Pro Rata Rights: [Yes/No]; optional MFN: [Yes/No]; Conversion Events: next Equity Financing, Liquidity, Dissolution; Capitalization for Cap: [define]. No interest; no maturity; not debt.

### **S3‑RS — Revenue‑Share**

- **Revenue‑Share %**: [ __% ]
- **Payment Frequency**: ☐ Monthly ☐ Quarterly
- **Duration**: [ __ months ] (0 = perpetual)
- **Minimum Payment Threshold** (revenue to start payouts): [ __ USDT ]
- **Cap Multiplier** (aggregate ROI cap, e.g., “3” = 300%): [ __ × ]
- **Holdback**: [ __% for __ days ] to cover refunds/chargebacks (auto‑releases thereafter).
- **Waterfall**: (i) apply **Success fee** on each distribution event; (ii) pay **pro‑rata** to TP Units; (iii) unclaimed funds remain claimable.

---

## **S4 — UCV (Universal Compliance Vehicle)**

- **QI‑only toggle** — ☐ On ☐ Off
- **QI verification** — ☐ third‑party letter ☐ documentary review ☐ platform verification
- **U.S. posture** — ☐ **4(a)(2)** ☐ **Reg D 506(b)** ☐ **Reg D 506(c)** ☐ **Reg D 504** ☐ **Reg S** ☐ **Reg A T1** ☐ **Reg A T2** ☐ **Reg CF via registered portal** ☐ **N/A (block U.S.)**
    - **If “N/A”** — Wizard must set: **Jurisdiction Block: United States**; **Marketing: no U.S. solicitation**; **Legends: “Not offered in the United States.”**
        
- **Jurisdiction blocks / allowlists** — [ ISO country codes ]
    
- **Min / Max Investors** — [ __ / __ ]
    
- **Min / Max Ticket** — [ __ USDT / __ USDT ]
    
- **Transfer rules** — whitelisted wallets only; KYC/QI for transfers; any lock‑ups [ __ ]
    
- **Legends to stamp** — [ strings shown on receipts and unit legends ]
    
- **Shariah Module** — ☐ OFF ☐ **Musharakah** ☐ Mudarabah ☐ Other (Murabaha / Ijara / Wakala / Istisna’)
    
- **Secured Portal** — URL [ __ ] • password policy [ __ ]

> **Issuer actions for compliance.** You are solely responsible for: verifying QI where required; delivering any required offering materials; state filings and blue‑sky notices; distribution‑compliance legends for Reg S; maintaining purchaser questionnaires for 506(b); and verification evidence for 506(c). If **Reg CF** is selected, **all U.S. sales must occur on a FINRA‑registered funding portal or broker‑dealer**; do **not** accept U.S. purchases on Athanor — import cap‑table entries post‑close if needed.

---

## **S5 — Evidence Menu**

- **Revenue & Finance** — processor payouts; bank statements; MRR/ARR workbook; refund logs.
    
- **Product & Code** — repository tags/releases; CI/CD logs; artifact hashes; IaC plans.
    
- **Usage & Growth** — analytics dashboards; activation funnels; cohort retention.
    
- **Reliability & Security** — uptime/latency dashboards; incident reports.
    
- **Customer Proof** — signed case studies; NPS; anonymized support transcripts.
    
- **Signed Attestations** — executive certifications for facts not otherwise verifiable.
    
- **Other** — project‑specific sources listed here: [ __ ].

---

## **S6 — Fee Allocation**

- **Issuance 2%** — Founder [ __% ] + Investors [ __% ] = **2%**
    
- **Success 7%** — Founder [ __% ] + Investors [ __% ] = **7%**
    
- **Gas fees** — [ Users / Issuer / Split ]
    
- **Notes** — [ __ ]

---

## **S7 — Governance, Thresholds, and Sensitive‑Access**

- **Milestone Change** — requires **Founder consent** **and** ≥ **[ 60 ]%** of invested TP Units _(default)_
    
- **Economic changes** (e.g., rev‑share %, SAFE cap/discount) — ≥ **[ 66⅔ ]%** of outstanding units _(suggested)_.
    
- **Sensitive‑Access ticket** — **[ __ USDT ]** aggregate grants the right to request sensitive information via the **Secured Portal**; Issuer must provide access or a reasoned written response within **[ __ ] business days**.
    
- **Voting / quorum mechanics** — [ on‑chain vote or off‑chain + CoA execution during beta ].
    
- **CoA migrations** — CoA may migrate for **security/performance/maintenance**; no change to economics without the consents above.

---

## **S8 — Shariah Module (if ON)**

**Mode** — ☐ **Musharakah** (default) ☐ Mudarabah ☐ Other (Murabaha / Ijara / Wakala / Istisna’)

**Musharakah defaults**

- **Contributions** — cash and **non‑cash** (time, services, IP, assets) valued **ex‑ante** and **documented**: [ valuation method ].
    
- **Profit ratios** — Founder [ __% ] • Investors (collective) [ __% ] (Investor‑level split pro‑rata to capital unless stated otherwise).
    
- **Loss** — strictly **per capital shares** (including agreed value of non‑cash contributions). No capital/return guarantee.
    
- **Prohibited** — **riba, maysir, excessive gharar**, and the following sectors: [ list ].
    
- **Purification** — non‑compliant income donated to **Purification Wallet** [ address ]; events and amounts posted in the Data Room.
    
- **Managing partner** — [ Founder / JV board ]; scope [ __ ]; fee (if any) [ formula ]; no interest‑like charges.
    
- **Exit / buyout valuation** — [ independent valuation / formula / book value ]; no guaranteed par redemptions.
    
- **Shariah Advisor (optional)** — [ name ], scope, and annual review cadence.

---

## Signature & Acceptance

- **Issuer acceptance** — by deploying this Agreement and Schedules via the Wizard.
    
- **Investor acceptance** — by contributing funds to the Agreement and, where applicable, claiming units to a **verified non‑custodial wallet**.
    
- **Operator acknowledgement** — by enabling deployment, Athanor acknowledges only its **operator** role as defined in the ToS.

---

**End of Template**