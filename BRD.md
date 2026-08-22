# KisanSarthi Ecosystem

**Project Lead:** Pratham Sarda  
**Core Strategy:** Managed "Pull-Model" Supply Chain  
**Operational Pillar:** Physical Verification by Village Sarthis

---

## 1. THE CORE BUSINESS ENGINE

### 1.1 The "Job Board" (Demand-Driven Signals)

Instead of farmers listing what they have, the platform lists what **Buyers need**.

- **The Almanac Match:** The system uses the crop variety database + the farmer’s land DNA (Soil/Water/Location) to send "Job Alerts" only to farmers who _can_ successfully grow that specific variety.
- **Automated Matching:** When a buyer (e.g., Haldiram) posts an order for 1,000 tons, the software instantly identifies the top-tier clusters of farmers whose land data matches the requirement.

---

## 2. STAKEHOLDER RESPONSIBILITIES

| Stakeholder         | Role                   | Responsibility                                                                      |
| :------------------ | :--------------------- | :---------------------------------------------------------------------------------- |
| **Verified Farmer** | The Producer           | Follows the "SOP Alerts" sent via the app to ensure contract compliance.            |
| **Village Sarthi**  | **The Quality Police** | Conducts **Onsite Physical Checks**. Responsible for final sign-off before loading. |
| **Matching Engine** | The Architect          | Uses Geo-spatial data to cluster farmers and optimize truck routes.                 |

---

## 3. FUNCTIONAL PROCESS FLOW (THE "REAL-WORLD" PATH)

### 3.1 Pre-Season: Land Vetting

- No "Open Signups." Farmers are registered after a Sarthi visits the farm, geofences the boundaries, and takes a soil sample.
- **Land Profile:** The app stores the "Production Capacity" of each farm.

### 3.2 During Season: The Job Alert & SOPs

- **The Signal:** Buyer posts a contract $\rightarrow$ System alerts suitable farmers $\rightarrow$ Farmer accepts.
- **Managed Growth:** The app sends alerts for fertilizer/pesticide cycles. The Sarthi makes mandatory onsite visits at 30/60/90 days to verify the farmer is actually following the protocol.

### 3.3 Harvest: The Onsite Physical Audit

- **Manual Certification:** The Sarthi arrives at the farm during harvest.
- **The Checklist:** Instead of AI, the Sarthi uses a **Physical Quality Kit** (Moisture meter, sizing rings, weighing scale).
- **Digital Sign-off:** The Sarthi enters the physical parameters into the app. This creates the "Digital Pedigree." If the Sarthi lies, they lose their commission and their "Sarthi Status."

### 3.4 Logistics & Payment: The Handover

- **The Cluster Match:** The matching software groups 10–15 farmers into a "Loading Zone" to fill a truck.
- **Geofence Trigger:** The truck arrives. Once the Sarthi marks "Loaded" and the truck’s GPS leaves the farm’s geofenced area, a **UPI Payment** is instantly triggered to the farmer.

---

## 4. SOFTWARE LOGIC (THE "TRUE" TECH MOAT)

The tech focus is shifted from "Computer Vision" to **"Logistics & Data Orchestration"**:

1.  **Suitability Algorithm:**
    `Function: Match(Buyer_Spec, Land_Data, History_Score)`
    _Ensures the "Job" only goes to the farmer most likely to succeed._

2.  **Route Optimization (Clustering):**
    `Function: Cluster(Order_Volume, Farmer_Locations, Harvest_Timing)`
    _The software calculates the most efficient way to pick up 20 tons from 12 different small farms._

3.  **The Geofence Payment Gateway:**
    `Trigger: (Status=Loaded) AND (Location=Outside_Farm_Boundary)`
    _Automates trust. Farmer gets paid the moment the goods leave his gate._

---

## 5. TRADE-OFFS & RISK MANAGEMENT

- **Risk: Sarthi Corruption (The "Human" Problem).**
  - _Solution:_ The "Factory Feedback Loop." If the factory rejects a load that the Sarthi verified, the Sarthi is penalized. Their income is tied to the **Buyer's Acceptance**, not the Farmer's satisfaction.
- **Trade-off: Scalability.**
  - _Reality:_ Because you require physical onsite checks, you cannot scale to 100 million farmers overnight.
  - _Strategy:_ You scale village-by-village, building "Elite Clusters." This is slower but **profitable and sustainable.**
- **Risk: Side-Selling.**
  - _Solution:_ The "Instant Payment." Farmers sell to Mandis because they need cash. By paying via UPI the _second_ the truck pulls away, you remove the farmer's primary reason to cheat the contract.

---

## 6. WHY THIS WORKS WHERE OTHERS FAIL

1.  **DeHaat fails** because they try to be everywhere; quality becomes "average." **KisanSarthi wins** by being a "Managed Club" where a Sarthi’s physical signature is a guarantee of quality.
2.  **Pure marketplaces fail** because of the "Trust Gap." **KisanSarthi wins** by using the "Pull Model"—the sale is guaranteed _before_ the seed is in the ground.
3.  **Manual contract farming fails** because of logistics costs. **KisanSarthi wins** by using a **Matching Engine** to cluster small farmers into "one big virtual farm" for the truck.

---
