# BOM (فهرست قطعات پیشنهادی)

برای سیستم شما (اینورتر E‑SK4224V1، 4× Mana 600W سری، باتری TITAN 25.6V 100Ah، یک باتری)

1. PV (ورودی خورشیدی)
   - PV DC breaker: 2‑pole DC breaker 20 A, DC rated ≥ 1000 VDC — Qty: 1
   - PV SPD: DC two‑pole, Class II, rated ≥ 600–1000 VDC — Qty: 1
   - PV cable: PV1‑F, 4 mm² (UV resistant, PV rated) — Length: 4.5 m (4 m + 10% margin) — Qty: 1 string (pair)
   - MC4 connectors (male/female) — Qty: as needed (2 per panel)

2. باتری (Battery side)
   - Battery DC isolator / MCCB: 200 A DC, DC‑rated (push‑to‑trip recommended) — Qty: 1
   - Battery cable: 35 mm² tinned copper, length ≈ 1.1 m (1 m + 10% margin) — Qty: 2 (Pos/Neg)
   - Cable lugs (suitable for 35 mm²) — Qty: 4
   - Heat‑shrink tubing, cable glands and insulation materials — assorted

3. AC side
   - AC MCB: 2‑pole, 20 A, Type C, 230 V~, Icn ≥ 6 kA — Qty: 1
   - AC input breaker (for grid/charger): 20 A (if separate) — Qty: 1

4. Communication & monitoring
   - RJ45 CAT6 shielded cable (for BMS) — length as needed (keep separate from power cables) — Qty: 1

5. Mechanical & accessories
   - Junction box for PV SPD and breakers — Qty: 1
   - Earth/PE cable: ≥ 6 mm² — Qty: as needed
   - Mounting hardware, DIN rail accessories, busbars (if needed) — assorted

6. Tools & consumables
   - Crimping tool for 35 mm² lugs
   - Torque wrench (for terminal torque values)
   - Multimeter, clamp meter, insulation tester

توضیحات تکمیلی
- برنامهٔ پیشنهادی در اینورتر:
  • Program02 (Max charge) = 70 A
  • Program05 = LIb (اگر باتری شما RS485 دارد) یا گزینهٔ مطابق با پروتکل BMS (در صورت CAN از گزینهٔ کانال CAN استفاده کنید)
  • Program26 (Bulk) = 28.2 V, Program27 (Float) = 28.8 V, Program29 (Cut‑off) = 21.6 V
- کابل‌ها و تجهیزات DC باید "DC‑rated" باشند (ولتاژ و قطع جریان مناسب)؛ از کابل PV مخصوص (PV1‑F) استفاده شود.
- نصب و راه‌اندازی توسط نصاب واجد شرایط انجام شود.
