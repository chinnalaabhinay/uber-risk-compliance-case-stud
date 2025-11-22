# SOP: Risk Case Handling (Sample)

**Purpose:** To ensure consistent and compliant handling of risk/compliance cases.

**Scope:** All agents handling ride-related customer complaints and risk cases.

**Definitions:**
- Case: An individual ticket logged against a trip.
- Flag: Case classified as high-risk and requiring escalation.
- Verification: Series of checks to confirm transaction/trip authenticity.

**Process Steps:**

1. **Case Intake**
   - Open the case in the operations dashboard.
   - Verify Case_ID, Rider_ID, Driver_ID, and Trip_Amount.

2. **Initial Verification**
   - Check trip logs (start/end GPS), payment receipts, and timestamps.
   - Confirm customer's identity (if required) and driver's details.

3. **Apply Risk Scoring**
   - Review risk factors present in 'Risk_Factors' (e.g., payment_mismatch, multiple_complaints).
   - Calculate Risk_Score using the project scoring logic.
   - Mark Case_Status accordingly:
     - Risk_Score >= 8 → 'Flagged - Escalate'
     - Risk_Score 5–7 → 'Review'
     - Risk_Score <=4 → 'Safe'

4. **Resolution Steps**
   - If 'Safe': Complete verification and close with remarks.
   - If 'Review': Perform deeper analysis, add agent notes, and update status.
   - If 'Flagged - Escalate': Escalate to TL/Risk Ops with full evidence packet.

5. **Documentation & Closure**
   - Always update Agent_Notes with evidence steps taken.
   - Record Resolution_Time_Hrs and final action (refund/penalty/escalation).
   - If escalated, follow up until closure.

**Do's & Don'ts**
- Do follow verification checklist thoroughly.
- Do not close a case without documented evidence.
- Do escalate any suspicious patterns to the TL immediately.

**Escalation Matrix**
- Agent → Team Lead (TL) → Risk Operations → Compliance Manager

**KPIs to monitor**
- % Flagged Cases resolved within SLA
- Average Resolution Time (hrs)
- Repeat complaint rate per Rider/Driver

