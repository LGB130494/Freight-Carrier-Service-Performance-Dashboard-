# Freight-Carrier-Service-Performance-Dashboard-

🔹 1. Freight Cost & Damaged Units by Carrier 🚛💸📦
✅ Explanation
This view compares total freight cost against damaged units for each carrier.

Some carriers show lower freight cost but higher damaged units, which increases hidden costs (returns, re‑shipments, customer dissatisfaction).
Other carriers may appear slightly expensive but have very low damage, making them overall cost‑efficient.

✅ Business Insight

“Freight cost alone is not a good decision metric. When damage is included, the true cost per shipment becomes visible.”

✅ Action:

Penalize high‑damage carriers during contract renewals
Shift volume to low‑damage, consistent performers


🔹 2. Load Utilization by Carrier 🚚📦
Output values: 1.04 , 1.01 , 0.98 , 0.98
✅ Explanation
Load utilization indicates how efficiently carrier capacity is used.

Values close to 1 = optimal utilization
>1 = slight over‑utilization (risk of damage or delay)
<1 = under‑utilization (unused capacity → higher cost/unit)

✅ Interpretation

Carriers with 1.04 & 1.01 → Aggressively utilized, efficient but monitor damage & delays
Carriers at 0.98 → Slightly under‑utilized, potential to consolidate loads

✅ Business Insight

“There is an opportunity to rebalance shipments to improve utilization without increasing risk.”

✅ Goal alignment: Fast + Low‑Cost Delivery

🔹 3. Carrier Charges per KG & KM 📏💰
✅ Explanation
This measures freight efficiency normalized by weight and distance, allowing fair comparison across carriers.

High charge per KG/KM = inefficient routing, pricing, or low consolidation
Low charge per KG/KM = cost‑optimized carrier

✅ Business Insight

“Even if two carriers charge similar total freight, their cost per KG/KM can differ significantly — revealing pricing inefficiencies.”

✅ Action:

Renegotiate lanes with high KG/KM cost
Use efficient carriers for long‑haul routes


🔹 4. Average Delays & Late Delivery % ⏱️🚦
✅ Explanation
This combines service reliability metrics:

Average delay days
% of late deliveries

✅ Business Insight

“Some carriers are cost‑efficient but unreliable, while others provide stable lead times.”

✅ Decision Logic

Customer‑critical lanes → prioritize low delay %
Cost‑sensitive lanes → accept minor delays


🔹 5. Units per Shipment 📦📦
✅ Explanation
Measures shipment consolidation.

Higher units per shipment = better utilization, lower cost per unit
Lower units = fragmented shipments, higher logistics cost

✅ Business Insight

“Improving consolidation improves freight efficiency without changing rates.”

✅ Action:

Plan order batching
Improve warehouse dispatch planning


🔹 6. Perfect Order Rate ✅📦
(On‑time + No damage)
✅ Key Output
Perfect Order Rate values:
0.34 , 0.33 , 0.33 , 0.31
✅ Explanation
Only 31–34% of shipments are perfect orders.
That means:

~66% shipments have delay, damage, or both

✅ Executive Insight 🔥

“While cost metrics look reasonable, service reliability is a major improvement opportunity.”

✅ Focus Areas

Carrier discipline
Dock‑to‑dispatch accuracy
Route planning stability


🔹 7. Shipments per Month 📅🚚
Output: 0.34 , 0.33 , 0.33 , 0.31
✅ Explanation
Shipment distribution is nearly balanced, but slight decline indicates:

Seasonal impact, or
Carrier capacity constraints

✅ Business Insight

“Volume is stable, so performance issues are primarily operational — not demand‑driven.”
