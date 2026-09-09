# KisanSarthi — Business Requirements Document (BRD)

**Project:** KisanSarthi  
**Lead:** Pratham Sarda  
**Overview:** A direct B2B agricultural platform connecting farmers directly to bulk buyers (food processors, supermarket chains). It removes middlemen through an automatic crop-matching system, local storage centers (silos), and same-day farmer payments.

---

## 1. How It Works

1. **Farmer Verification:** A local field partner (Village Sarthi) visits the farm to record land boundaries, test the soil, and verify yield limits.
2. **Farmer Lists Produce:** The farmer lists ready or upcoming crops (variety, quantity, harvest date, quality).
3. **Automatic Order Matching (Primary Core):** The system automatically matches listed crops with active bulk buyer orders, pooling supply from multiple small farms to fulfill large orders.
4. **Live Order Board (Additional Feature):** An optional screen where farmers can also manually browse open buyer requests, check prices, and pledge crops.
5. **Local Delivery & Sorting:** The farmer delivers to a nearby local storage center (Silo, within 6 km) for electronic weighing and machine sorting.
6. **Same-Day Payment:** The farmer receives **75% payment instantly** via UPI at the weighbridge. The remaining **25%** is paid upon factory delivery.

---

## 2. Core Features

### 1. Farmer Land Profile
- Digital profile with verified government ID, bank/UPI details, GPS field boundaries, and soil test results.
- Caps listing quantity to the verified farm size to prevent fake listings.

### 2. Farming Guidance & Pre-Harvest Audits
- Recommends high-demand crop varieties before planting.
- Sends regular reminders for fertilizers, pest control, and watering.
- Pre-harvest field checks 10–14 days before harvest to verify quality and moisture.

### 3. Crop Listing & Automatic Matching (Primary Core)
- Farmers list crop type, expected tons, ready date, and quality readings.
- System automatically matches and bundles farmer lots into buyer orders using 4 rules:
  - Exact variety and quality match.
  - Local silo area (<6 km).
  - Quantity bundling with a 10% safety buffer.
  - Fair rotation among farmers.
- Generates an instant digital **Silo QR Gate Pass** with drop-off time slot.

### 4. Live Order Board ("Job Board for Crops" — Additional Feature)
- Optional screen in the app displaying open buyer purchase orders as cards.
- Shows crop variety, required grade, fixed price per kg, and live quota fill bar.
- Allows farmers to manually browse and pledge surplus harvest.

### 5. Local Storage & Sorting Centers (Regional Silos)
- Physical facilities placed every 100 sq km (within 6 km of farms).
- Features: Electronic weighbridge, roller sorting machines, ventilated holding bays (48–72h storage), 25 kg plastic crates, and heavy truck loading docks.

### 6. Two-Step Transport
- **Step 1 (Farm to Silo):** Farmer brings crops to the local silo using their tractor or pickup.
- **Step 2 (Silo to Factory):** Graded, crated produce is moved directly to buyer factories in large trucks with GPS tracking.

### 7. Escrow Protection & Same-Day Payout
- Buyer deposits 100% of order payment into escrow before dispatch.
- **75% instant payout:** Sent to the farmer's bank account via UPI within 2 minutes of passing the silo weighbridge.
- **25% final payout:** Released when the shipment reaches the buyer's factory.

### 8. Advance Purchase Contracts (Optional)
- Pre-season agreements locking prices 3–6 months ahead.
- Guaranteed floor price + **50% bonus sharing** if open market prices rise higher at harvest.

### 9. Seed & Fertilizer Credit
- Low-interest bank loans (12–15% per year) for farming inputs.
- Delivered as seeds and fertilizers from verified local dealers (not cash), repaid automatically from harvest payouts.

### 10. WhatsApp Notifications
- Delivers match alerts, gate passes, reminders, and payment receipts via WhatsApp for farmers without smartphones.
-as we have all his profile we can alert him about weather , future crop opprtunities for his farm

---

## 3. Stakeholders & Responsibilities

| Stakeholder | Role | Main Benefit | Safeguard |
| :--- | :--- | :--- | :--- |
| **Farmer** | Grows quality crops, delivers to local silo | 8–12% higher profit, same-day payment | Defaulters lose platform access |
| **Village Sarthi** | Onboarding, field audits, silo supervision | Commission per ton accepted by buyer | 15% commission held in reserve; paid only on buyer acceptance |
| **Buyer** | Places bulk orders, funds escrow | Consistent grade, traceable supply, 24–72h delivery | Must deposit 100% escrow before dispatch |
| **KisanSarthi** | Runs matching system, manages silos & transport | 3–6% transaction margin + handling fees | Underwrites fulfillment and quality |

---

## 4. Unit Economics (Per Kg of Potato)

| Item | Amount |
| :--- | :--- |
| Buyer Purchase Price | ₹20.00 / kg |
| Net Farmer Payout | ₹16.50 / kg *(8–12% higher than mandi net)* |
| Mandi Middleman Cuts Avoided | ₹1.80 / kg |
| Silo Handling & Storage | ₹0.60 / kg |
| Transport & Crating | ₹1.40 / kg |
| **KisanSarthi Margin** | **₹1.50 / kg (7.5%)** |
