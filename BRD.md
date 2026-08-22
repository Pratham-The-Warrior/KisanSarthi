This is the **Business Requirement Document (BRD)** for **KisanSarthi**. It is designed to be the foundational document that aligns stakeholders (investors, founders, and lead engineers) on the "Why" and the "What" before a single line of code is written.

---

# BUSINESS REQUIREMENT DOCUMENT (BRD): KisanSarthi Ecosystem

**Document Version:** 1.0  
**Project Lead:** Founder / Lead Strategist  
**Status:** Draft for Executive Review

---

## 1. EXECUTIVE SUMMARY

### 1.1 Project Vision

To build a digital operating system for Indian agriculture that transitions small, unorganized farmers from "subsistence" to "surplus" by providing high-speed market matching, AI-driven agronomy, and integrated financial support.

### 1.2 The "North Star" Metric

**Total Farmer Net Income Growth:** The primary measure of success is the percentage increase in the annual net profit of an onboarded farmer compared to their historical baseline.

---

## 2. BUSINESS CONTEXT & PROBLEM STATEMENT

### 2.1 The Crisis of the Unorganized Farmer

- **The Spoilage Trap:** Small farmers (holdings <2 hectares) lose 20-30% of perishable produce (tomatoes, onions, green leafy vegetables) due to a lack of immediate buyers post-harvest.
- **Information Poverty:** Scientific farming advice (pest detection, soil health) is expensive or unavailable, leading to high input costs and crop failure.
- **The Middleman Paradox:** While intermediaries provide credit and logistics, their 10-40% commission and lack of price transparency keep farmers in a debt cycle.
- **Quality Subjectivity:** Without standardized grading, buyers default to the lowest price, penalizing farmers who grow high-quality produce.

---

## 3. STAKEHOLDER ANALYSIS

| Stakeholder                | Role           | Key Needs                                                             |
| :------------------------- | :------------- | :-------------------------------------------------------------------- |
| **Small Farmer**           | Primary User   | Higher prices, instant payment, pest solutions, lower input costs.    |
| **B2B Buyer**              | Primary Client | Consistent quality, traceability, reliable supply, digital invoicing. |
| **Village Sarthi (VLE)**   | Facilitator    | Commission-based income, tech-enablement, social status.              |
| **Input Providers**        | Partner        | Direct channel to farmers, data on demand/consumption.                |
| **Financial Institutions** | Partner        | Verified data for lending/insurance, lower default rates.             |

---

## 4. BUSINESS GOALS & OBJECTIVES

### 4.1 Objective 1: Optimize Speed-to-Market

- **Goal:** Reduce the "Time-to-Transaction" (TTT) for perishable crops.
- **Requirement:** Create a marketplace where 80% of listed produce is matched with a buyer within 6 hours of harvest notification.

### 4.2 Objective 2: AI-Driven Risk Mitigation

- **Goal:** Lower the cost of crop failure.
- **Requirement:** Deploy a Computer Vision (CV) tool that identifies 50+ common pests/diseases with >90% accuracy, providing instant remedy recommendations.

### 4.3 Objective 3: Ecosystem Financialization

- **Goal:** Replace high-interest informal debt.
- **Requirement:** Build a "Farmer Trust Score" based on platform activity to facilitate institutional credit at <12% APR.

---

## 5. HIGH-LEVEL SCOPE

### 5.1 In-Scope (Phase 1: The MVP)

1.  **Digital Identity:** Farmer onboarding with land-parcel mapping (via GPS).
2.  **Kisan Sarthi AI:** Image-based disease diagnosis and yield-prediction engine.
3.  **Flash-Market:** A matching engine connecting clusters of farmers to B2B buyers.
4.  **Advisory Bot:** Voice-enabled (regional language) weather and price alerts.
5.  **Quality Grading:** AI-based visual grading of produce (Size, Color, Defects).

### 5.2 Out-of-Scope (Future Phases)

1.  Direct-to-Consumer (B2C) delivery.
2.  Managing a proprietary fleet of trucks (Asset-heavy logistics).
3.  Ownership of cold storage facilities.
4.  International export licensing (initially).

---

## 6. BUSINESS PROCESS FLOW (TO-BE)

1.  **Pre-Sowing:** AI recommends seeds based on soil data + predicted market demand 4 months out.
2.  **Cultivation:** Farmer uploads weekly photos; AI monitors health and triggers "Alerts" if pests are detected in the vicinity.
3.  **Pre-Harvest (The Match):** 10 days before harvest, AI predicts yield volume. System opens a "Forward-Listing" to B2B buyers.
4.  **Harvest & Grade:** Farmer takes a photo of the harvested crate. AI assigns a Grade (A, B, or C).
5.  **Logistics & Settlement:** Buyer accepts the grade/price. Logistics is triggered. Upon digital "Handshake," payment is released via UPI Escrow.

---

## 7. FUNCTIONAL BUSINESS REQUIREMENTS

| ID        | Requirement Name                 | Description                                                                                                       | Priority |
| :-------- | :------------------------------- | :---------------------------------------------------------------------------------------------------------------- | :------- |
| **BR-01** | **Multilingual Voice-Interface** | System must support voice commands in 5 regional languages to accommodate low literacy.                           | P0       |
| **BR-02** | **AI-Grade Certification**       | The system must generate a "Digital Quality Certificate" that is legally binding for the buyer.                   | P0       |
| **BR-03** | **Demand-Supply Matching**       | Algorithm must prioritize matching based on: 1. Proximity, 2. Spoilage risk, 3. Historical buyer reliability.     | P0       |
| **BR-04** | **Credit Scoring**               | A proprietary algorithm to calculate creditworthiness using farming behavior, not just bank history.              | P1       |
| **BR-05** | **Offline Sync**                 | Core advice and listing features must work without active internet, syncing once the farmer reaches a 3G/4G zone. | P1       |

---

## 8. NON-FUNCTIONAL REQUIREMENTS

- **Trust & Reliability:** The AI grading must have less than a 5% dispute rate from buyers.
- **Scalability:** The architecture must support a 10x surge in data during the "Kharif" and "Rabi" harvest windows.
- **Data Privacy:** Farmer land and income data must be encrypted and never shared without explicit consent (DPDP Act compliance).

---

## 9. BUSINESS RISKS & MITIGATION

| Risk                    | Impact | Mitigation Strategy                                                                       |
| :---------------------- | :----- | :---------------------------------------------------------------------------------------- |
| **Quality Disputes**    | High   | Use AI-video capture at the point of loading; retain escrow until buyer OTP verification. |
| **Middleman Backlash**  | Medium | Onboard existing traders as "Sarthi" partners rather than competing with them directly.   |
| **Low Tech Adoption**   | High   | Use the "Human-in-the-Loop" model; the Sarthi performs the tech tasks for the farmer.     |
| **Working Capital Gap** | High   | Partner with NBFCs for invoice discounting so KisanSarthi doesn't carry the debt.         |

---

## 10. SUCCESS CRITERIA (KPIs)

1.  **Wastage Reduction:** <5% spoilage for farmers on the platform.
2.  **Price Delta:** Farmers earn at least 12% more than the local Mandi average.
3.  **Advisory Accuracy:** >90% success rate in pest treatment recommendations.
4.  **Liquidity:** Average time from "Grade Confirmed" to "Payment Received" < 24 hours.

---

## 11. APPROVALS

- **CEO/Founder:** Pratham Sarda
- **Head of Product:** Pratham Sarda
- **Head of Engineering:** Pratham Sarda

---
