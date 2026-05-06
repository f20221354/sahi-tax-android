
# Sahi Tax: India's First AI Tax Optimizer

Sahi Tax is an automated **Tax-Loss Harvesting (TLH)** platform designed specifically for retail investors in India. By leveraging AI and a deterministic rule engine, it identifies and executes opportunities to save on capital gains tax, a service previously reserved for High Net Worth Individuals (HNIs).

## 🚀 The Problem
* **Awareness Gap:** 99% of retail investors are unaware that Tax-Loss Harvesting exists[cite: 550].
* **Complexity:** Tracking 8-year loss carry-forwards (under Section 74 of the IT Act) across multiple brokers is nearly impossible for manual tracking[cite: 546, 551].
* **Timing Failure:** Traditional CAs file in July, long after the March 31st deadline for tax-saving trades has passed[cite: 552].
* **Cost Gap:** Existing PMS firms charge ₹2-5L/year, making them unaffordable for the 1.5 crore retail investors filing ITR-2[cite: 541, 554, 576].

## ✨ Key Features
* **Automated Tax-Loss Harvesting:** Identifies losing positions to offset booked capital gains[cite: 541].
* **Deterministic Rule Engine:** Encodes Section 74/94 nuances (carry-forwards and stripping rules) with CA-audited logic[cite: 832, 834, 520, 521].
* **AI Explanation Layer:** Uses the Claude API to provide human-friendly explanations for every tax-saving recommendation[cite: 838, 521, 522].
* **One-Tap Execution:** Direct integration with major brokers like Zerodha (Kite Connect) for seamless trades[cite: 711, 833, 522].
* **ITR Ready Reports:** Automatically generates Schedule CG for ITR-2 filings[cite: 618, 802, 834].

## 🛠️ Tech Stack
* **Frontend:** Next.js, Tailwind CSS, shadcn/ui (Mobile-first PWA)[cite: 517].
* **Backend & Rule Engine:** Deterministic Python engine for tax logic[cite: 832, 520].
* **AI Integration:** Claude API for decision explanation[cite: 838, 521, 522].
* Data Parsing:** Python + `pdfplumber` for Consolidated Account Statement (CAS) processing[cite: 709, 518].
* **Data Infrastructure:** Sahamati Framework (via Finvu) for RBI-approved Account Aggregator consent[cite: 710, 519].

## 📈 User Flow
1.  **Connect:** Upload CAS PDF or connect via Account Aggregator/Broker APIs[cite: 620, 692].
2.  **Select:** View flagged tax-saving opportunities and select stocks to liquidate[cite: 621, 633].
3.  **Generate:** Review a dynamic "Tax Optimization Report"[cite: 622, 636, 639].
4.  **Execute & File:** One-tap trade execution and download ITR-ready schedules[cite: 623, 686, 802].

## 🛡️ Trust & Compliance
* **SEBI Compliance:** Designed for SEBI-RIA (Investment Advisor) partnership to ensure legal advisory standards[cite: 724, 726, 835].
* **Security:** Encrypted data handling through RBI-regulated Account Aggregator rails[cite: 710, 519].
* **Auditability:** Core logic is audited by professional CA firms to ensure compliance with the latest Income Tax Act sections[cite: 834, 520].

## 🗺️ Roadmap
* **Phase 1:** CAS PDF Upload for instant coverage[cite: 695, 698].
* **Phase 2:** Account Aggregator (AA) integration for automated tracking[cite: 700, 703].
* **Phase 3:** Direct Broker APIs (Zerodha, Upstox, ICICI) for live execution[cite: 706, 731, 522].
* **Expansion:** Moving beyond TLH to Salary Optimization and continuous AI-driven CFO services[cite: 501, 502, 503].

---
**Developed by Mirnal Gupta (BITS Pilani)**.
