# O5 — Mechanical Drawing & Cut Sheet
## Tape Measure Satellite Yagi
**Project:** Tape Measure Satellite Yagi  

**Document:** O5 Mechanical Drawing & Cut Sheet  

**Repository Path:** `docs/cut-sheet.md`  

**Application:** Amateur-Radio Satellite / ISS Operation  

**Bands:** 2 m / 70 cm  

**Design Inputs:** Finalized O3 dimensional baseline and O4 material baseline  

**Design Status:** Pre-Fabrication Mechanical Baseline  

**Revision:** Rev. A  

**Date:** 2026-08-24

---

# 1. Purpose
This document is the formal mechanical drawing and fabrication cut sheet for the Tape Measure Satellite Yagi.

It converts the finalized O3 RF geometry into an unambiguous bench-ready mechanical layout.

This document defines:

- Boom lengths

- Front/rear orientation

- Mechanical datum

- Element cut lengths

- Driven-element half lengths

- Driven-element center gaps

- Absolute boom drilling locations

- Adjacent element spacing

- Element-hole size

- Feedpoint-hole guidance

- Dowel/stiffener cuts

- Dual-boom joint locations

- Operating and storage orientation

- Fabrication tolerances

- Pre-cut and post-cut inspection requirements

- As-built dimensional recording

This document is intended to be used directly during:

- **O6 — Fabrication & Assembly**

- **O7 — Feed & Matching System**

- **O8 — Initial RF Testing & Tuning**

The RF dimensions in this document originate from the finalized O3 baseline. Mechanical convenience dimensions are explicitly identified as O5 mechanical choices.

---

# 2. Authoritative Datum and Orientation
O3 records element positions from the **rear** of each 30.000 in boom.

For fabrication, O5 uses the **front end as the master mechanical datum** because the director end is easier to identify and lay out consistently at the bench.

Define:

**X = 0.000 in at the FRONT end of each boom.**

All O5 drilling dimensions increase toward the rear.

```text

FRONT / DIRECTION OF GAIN                                  REAR

X = 0.000 in

│────────────────────────────────────────────────────────────│

0.000                                                     30.000 in

```

The coordinate conversion from O3 is:

```text

X_front = 30.000 in - X_rear

```

The O3 and O5 coordinates therefore describe the same physical antenna geometry.

---

# 3. Antenna Mechanical Architecture
TM-YAGI-01 uses two separate 30.000 in PVC booms:

- **Boom A:** 2 m Yagi

- **Boom B:** 70 cm Yagi

The booms are mechanically coupled but able to rotate relative to one another.

## 3.1 Operating Configuration
During normal operation:

**2 m element plane and 70 cm element plane = approximately 90° apart**

```text

Looking down the boom axis:

             2 m elements

                  │

                  │

                  │

──────────────────┼────────────────── 70 cm elements

                  │

                  │

```

## 3.2 Storage Configuration
For transport/storage, the booms may be rotated so the element planes are approximately parallel.

The dual-boom joint must permit deliberate rotation without allowing the booms to separate.

---

# 4. Master Cut List
## 4.1 PVC Boom Cuts
| Cut ID | Material | Finished Length | Metric | Qty | Notes |

| --- | --- | ---: | ---: | ---: | --- |

| PVC-2M | 1/2 in Schedule 40 PVC | **30.000 in** | **762.0 mm** | 1 | 2 m boom |

| PVC-70 | 1/2 in Schedule 40 PVC | **30.000 in** | **762.0 mm** | 1 | 70 cm boom |

### Total PVC Used
```text

30.000 + 30.000 = 60.000 in

```

---

# 5. 2 Meter Element Cut Sheet
The 2 m section contains:

- 1 reflector

- 1 split driven element

- 1 director

## 5.1 Passive Elements
| Element ID | Type | Finished Length | Metric | Qty |

| --- | --- | ---: | ---: | ---: |

| 2M-R | Reflector | **41.400 in** | **1051.6 mm** | 1 |

| 2M-D1 | Director 1 | **35.400 in** | **899.2 mm** | 1 |

## 5.2 Driven Element
Final overall tip-to-tip span:

**37.400 in (950.0 mm)**

Center feed gap:

**0.250 in (6.35 mm)**

Combined conductive steel length:

```text

37.400 - 0.250 = 37.150 in

```

Each half:

```text

37.150 / 2 = 18.575 in

```

| Element ID | Type | Finished Conductive Length | Metric | Qty |

| --- | --- | ---: | ---: | ---: |

| 2M-DE-L | Driven left half | **18.575 in** | **471.8 mm** | 1 |

| 2M-DE-R | Driven right half | **18.575 in** | **471.8 mm** | 1 |

### 2 m Net Steel Requirement
```text

41.400 + 35.400 + 18.575 + 18.575

= 113.950 in

= 9.496 ft

```

---

# 6. 70 Centimeter Element Cut Sheet
The 70 cm section contains:

- 1 reflector

- 1 split driven element

- 3 directors

## 6.1 Passive Elements
| Element ID | Type | Finished Length | Metric | Qty |

| --- | --- | ---: | ---: | ---: |

| 70-R | Reflector | **12.900 in** | **327.7 mm** | 1 |

| 70-D1 | Director 1 | **11.900 in** | **302.3 mm** | 1 |

| 70-D2 | Director 2 | **11.900 in** | **302.3 mm** | 1 |

| 70-D3 | Director 3 | **11.700 in** | **297.2 mm** | 1 |

## 6.2 Driven Element
Final overall tip-to-tip span:

**12.600 in (320.0 mm)**

Center feed gap:

**0.250 in (6.35 mm)**

Combined conductive steel length:

```text

12.600 - 0.250 = 12.350 in

```

Each half:

```text

12.350 / 2 = 6.175 in

```

| Element ID | Type | Finished Conductive Length | Metric | Qty |

| --- | --- | ---: | ---: | ---: |

| 70-DE-L | Driven left half | **6.175 in** | **156.8 mm** | 1 |

| 70-DE-R | Driven right half | **6.175 in** | **156.8 mm** | 1 |

### 70 cm Net Steel Requirement
```text

12.900 + 11.900 + 11.900 + 11.700 + 6.175 + 6.175

= 60.750 in

= 5.063 ft

```

---

# 7. Total Tape-Steel Cut Requirement
```text

113.950 + 60.750 = 174.700 in

```

```text

174.700 in / 12 = 14.558 ft

```

**Net finished steel requirement: 174.700 in (14.558 ft)**

This value agrees with O4.

---

# 8. 2 Meter Boom Drill Schedule
All positions are measured from the **FRONT end** of the 30.000 in 2 m boom.

| Station | Element | Position from FRONT | Metric |

| --- | --- | ---: | ---: |

| 2M-D1 | Director 1 | **2.000 in** | **50.8 mm** |

| 2M-DE | Driven Element | **13.500 in** | **342.9 mm** |

| 2M-R | Reflector | **21.500 in** | **546.1 mm** |

## 8.1 2 m Adjacent Spacing Check
```text

13.500 - 2.000 = 11.500 in

```

Director 1 → Driven:

**11.500 in (292.1 mm)**

```text

21.500 - 13.500 = 8.000 in

```

Driven → Reflector:

**8.000 in (203.2 mm)**

These values match O3.

---

# 9. 70 Centimeter Boom Drill Schedule
All positions are measured from the **FRONT end** of the 30.000 in 70 cm boom.

| Station | Element | Position from FRONT | Metric |

| --- | --- | ---: | ---: |

| 70-D3 | Director 3 | **3.500 in** | **88.9 mm** |

| 70-D2 | Director 2 | **9.500 in** | **241.3 mm** |

| 70-D1 | Director 1 | **15.500 in** | **393.7 mm** |

| 70-DE | Driven Element | **18.500 in** | **469.9 mm** |

| 70-R | Reflector | **21.000 in** | **533.4 mm** |

## 9.1 70 cm Adjacent Spacing Check
Director 3 → Director 2:

```text

9.500 - 3.500 = 6.000 in

```

**6.000 in (152.4 mm)**

Director 2 → Director 1:

```text

15.500 - 9.500 = 6.000 in

```

**6.000 in (152.4 mm)**

Director 1 → Driven:

```text

18.500 - 15.500 = 3.000 in

```

**3.000 in (76.2 mm)**

Driven → Reflector:

```text

21.000 - 18.500 = 2.500 in

```

**2.500 in (63.5 mm)**

These values match O3.

---

# 10. 2 Meter Boom Layout Drawing
Not to scale.

```text

FRONT / GAIN →

X=0

0        2.000                 13.500              21.500             30.000

│----------│----------------------│--------------------│------------------│

           │                      │                    │

         2M-D1                  2M-DE                2M-R

        35.400                 37.400               41.400

       Director                Driven              Reflector

           <------11.500-------><------8.000------->

```

Rear handle/clearance from reflector station to boom end:

```text

30.000 - 21.500 = 8.500 in

```

**Rear boom clearance: 8.500 in (215.9 mm)**

---

# 11. 70 Centimeter Boom Layout Drawing
Not to scale.

```text

FRONT / GAIN →

X=0

0      3.500      9.500      15.500   18.500  21.000                  30.000

│--------│-----------│-----------│--------│-------│------------------------│

         │           │           │        │       │

       70-D3       70-D2       70-D1    70-DE   70-R

       11.700      11.900      11.900   12.600   12.900

      Director    Director    Director   Driven Reflector

         <--6.000--><--6.000--><-3.000-><-2.500->

```

Rear boom clearance from reflector station to boom end:

```text

30.000 - 21.000 = 9.000 in

```

**Rear boom clearance: 9.000 in (228.6 mm)**

---

# 12. Element Through-Hole Specification

Baseline element-station holes:

**7/16 in diameter**

The hole passes through the PVC boom approximately perpendicular to the boom centerline and should be centered through the boom cross-section as consistently as practical.

## 12.1 2 m Element Stations — Stiffener Method

At the three long 2 m element stations, the **3/8 in nonconductive dowel/fiberglass stiffener passes through the 7/16 in boom hole**. The tape-measure element is centered on the boom and secured to the stiffener on both sides with small cable ties.

This follows the baseline W6NBC-style mechanical concept: the stiffener carries the long flexible element near the boom and reduces wind-induced bending.

Requirements:

- One 3/8 in stiffener through each 2 m element station
- Tape steel centered symmetrically about the boom
- Tape element secured to the stiffener on both sides of the boom
- Cable ties tightened enough to prevent sliding without crushing or sharply deforming the tape
- Driven-element left and right halves must retain the specified 0.250 in center gap
- No conductive stiffener may be substituted without design review

## 12.2 70 cm Element Stations — Direct Tape Method

At the 70 cm stations, the narrow tape-measure steel may pass directly through the 7/16 in boom hole, provided the actual purchased blade fits without destructive force and is not excessively loose.

## 12.3 Number of Main Element-Station Holes

### 2 m boom

- 3 total through-holes

### 70 cm boom

- 5 total through-holes

### Total

**8 main element-station through-holes**

## 12.4 Hole Fit Verification

Before drilling all stations:

1. Drill one practice 7/16 in hole in scrap PVC.
2. Test-fit the actual 3/8 in stiffener material.
3. Test-fit the actual 70 cm tape steel.
4. Confirm the intended 2 m stiffener/tape attachment can be assembled without forcing or damaging the parts.
5. Confirm the 70 cm tape passes through without destructive force and is not excessively loose.

If the purchased materials do not fit the baseline geometry, **stop and revise the mechanical interface rather than enlarging every hole blindly**.

---

# 13. Driven-Element Feedpoint Geometry
Each driven element is split at the boom centerline.

Nominal center gap:

**0.250 in (6.35 mm)**

## 13.1 2 m Driven Element
```text

LEFT HALF                  GAP                  RIGHT HALF

18.575 in                 0.250 in                18.575 in

<------------------->      <-->      <------------------->

=====================                =====================

                         BOOM

```

Overall span:

**37.400 in**

## 13.2 70 cm Driven Element
```text

LEFT HALF                  GAP                  RIGHT HALF

6.175 in                  0.250 in                 6.175 in

<------->                  <-->                  <------->

=========                                        =========

                         BOOM

```

Overall span:

**12.600 in**

---

# 14. Feed-Screw Hole Guidance

The exact feed-screw holes should be **match-drilled during O6/O7 assembly after the driven-element halves are installed, centered, and the 0.250 in feed gap is established**.

Reason:

- The actual purchased tape width and final stiffener/tape stack-up may vary slightly.
- Match-drilling places each feed screw through the intended driven-element half at the actual assembled feedpoint.
- It reduces the chance of a pre-drilled hole missing the conductive steel or disturbing the specified center gap.

Baseline fastener:

**#6-32 × 1/2 in machine screw**

Recommended clearance-hole starting point:

**approximately 5/32 in**

The actual clearance must be verified against the purchased #6-32 hardware.

## 14.1 Feed-Screw Geometry

The #6-32 feed screws are **local feedpoint attachment hardware**, not transverse bolts intended to pass completely through the full 0.840 in outside diameter of the PVC boom.

During O6/O7, the final local screw path and nut/terminal arrangement should be established from the actual assembled feedpoint while preserving the O3/O5 driven-element geometry.

Each feed screw must:

- Electrically contact only one driven-element half
- Remain electrically isolated from the opposite driven half
- Provide secure attachment for the appropriate coax conductor terminal
- Provide attachment for the 2 m hairpin end where applicable
- Avoid splitting, crushing, or excessively weakening the PVC
- Preserve the **0.250 in center feed gap**
- Avoid becoming the dimensional reference used to locate the driven element

Do not drill a full transverse hole across the entire boom solely to accommodate the 1/2 in feed screw.

The driven-element overall span, equal half lengths, boom station, and center gap remain authoritative.

---

# 15. 2 Meter Hairpin Cut
The O7 matching system requires:

| Part | Material | Cut Length | Metric | Qty |

| --- | --- | ---: | ---: | ---: |

| 2M-HP | #12 AWG solid copper | **8.500 in** | **215.9 mm** | 1 |

This is the **initial pre-tuning length**.

Do not shorten the hairpin during fabrication.

Any change belongs to the O8 tuning record.

---

# 16. Dowel / Stiffener Cut Sheet

The three long 2 m elements receive nonconductive stiffening at the boom.

Baseline stock:

**3/8 in × 36 in hardwood dowel or fiberglass rod**

Recommended initial cuts:

| Stiffener ID | Initial Length | Metric | Qty | Station |
| --- | ---: | ---: | ---: | --- |
| ST-1 | **12.000 in** | **304.8 mm** | 1 | 2M-D1 |
| ST-2 | **12.000 in** | **304.8 mm** | 1 | 2M-DE |
| ST-3 | **12.000 in** | **304.8 mm** | 1 | 2M-R |

These are **mechanical starting lengths**, not RF-critical dimensions.

## 16.1 Installation Method

At each 2 m element station:

1. Pass the 3/8 in nonconductive stiffener through the corresponding 7/16 in boom hole.
2. Center the stiffener approximately equally on both sides of the boom.
3. Center the tape-measure element on the same station.
4. For the reflector and director, secure the tape element to the stiffener on both sides of the boom using small cable ties.
5. For the split driven element, position the left and right tape halves symmetrically and maintain the **0.250 in center feed gap**.
6. Secure each driven half to the stiffener without allowing either half to shift across the center gap.
7. Verify the tape element remains straight, centered, and approximately perpendicular to the boom.

The stiffener should support the flexible steel near the boom without becoming part of the RF circuit.

The initial 12 in stiffeners may be shortened during O6 if required for:

- Fit
- Clearance
- Portability
- Better element support

Any shortened final length should be recorded in the O6 as-built notes.

Do not replace the stiffeners with metal without design review and subsequent RF revalidation.

---

# 17. Dual-Boom Joint Detail

The V1 mechanical joint is intentionally simple and uses **long UV-resistant cable ties as rotating collars** around the two adjacent PVC booms.

No separate hinge or metallic pivot hardware is required for Rev. A.

Because two nominal 1/2 in Schedule 40 PVC booms have an outside diameter of approximately 0.840 in each, a nominal 4 in tie is too short to reliably encircle both booms and engage its locking head.

**Joint-tie requirement:**

- **8 in UV-resistant black cable ties preferred**
- **6 in UV-resistant cable ties minimum**
- Quantity: **2 installed, plus spares recommended**

The 4 in ties already used elsewhere in the BOM may remain useful for element/stiffener attachment but are not the Rev. A dual-boom collar ties.

## 17.1 Joint Locations

Measured from the common FRONT end:

| Joint ID | Position from FRONT | Metric |
| --- | ---: | ---: |
| J1 | **4.500 in** | **114.3 mm** |
| J2 | **22.500 in** | **571.5 mm** |

These are **O5 mechanical dimensions**, not RF element-spacing dimensions.

## 17.2 Joint Construction

At each joint:

- Place the two PVC booms directly beside one another.
- Install one 8 in preferred / 6 in minimum UV-resistant cable tie around both booms.
- Tighten only enough to retain the booms together while still permitting deliberate relative rotation.
- Trim only excess tail that is clearly unnecessary; retain enough engagement for a secure lock.
- Verify the tie does not migrate into an antenna element station.
- Verify the tie does not pinch or interfere with the coax routing.
- Verify the booms can rotate from the storage position to approximately 90° operating position without separating.

The cable ties act as **rotating collars**, not rigid clamps.

## 17.3 Operating Position

Set:

**2 m element plane ≈ 90° from 70 cm element plane**

## 17.4 Storage Position

Rotate the booms until the element planes are approximately parallel.

## 17.5 O4 BOM Impact

O4 should be revised in its next revision so the joint hardware reflects the actual O5 mechanical design:

- Retain BOM-011 4 in UV-resistant ties for smaller attachment duties.
- Redefine or replace BOM-018 as **dual-boom rotating-collar cable ties — UV-resistant, 8 in preferred / 6 in minimum**.
- Separate hinge or metallic pivot hardware is **not required** for O5 Rev. A.

If a more sophisticated hinge or pivot is later adopted, that becomes a mechanical-design revision.

---

# 18. Coax Choke Mechanical Allowance
O7 requires:

## 2 m
**6 turns of RG-58 around the 2 m boom**

## 70 cm
**4 turns of RG-58 around the 70 cm boom**

Exact turn pitch and final axial position should be adjusted during O7 assembly so the choke:

- Remains close to the corresponding feedpoint

- Does not overlap an antenna element

- Does not interfere with the rotating joint

- Does not prevent storage folding

- Does not sharply kink the coax

The O5 cut sheet does not define choke turn pitch as an RF-critical fixed dimension.

---

# 19. Element Alignment Requirements
Within each individual band:

- All passive elements should be parallel.

- Driven-element halves should lie in the same plane as the parasitic elements.

- Each continuous element should be centered through the boom.

- Split driven halves should be symmetrical around the boom centerline.

- Element twist should be minimized.

## 19.1 Centering Method
For a continuous element:

```text

Left projection = Right projection

```

Target centering error:

**≤ 1/8 in on 2 m**

**≤ 1/16 in on 70 cm**

where practical.

---

# 20. Fabrication Tolerances
## 20.1 2 m Elements
Element-length target:

**±1/8 in (±3.2 mm) or better**

Boom-position target:

**±1/8 in (±3.2 mm) or better**

## 20.2 70 cm Elements
Element-length target:

**±1/16 in (±1.6 mm) or better**

Boom-position target:

**±1/16 in (±1.6 mm) or better**

## 20.3 Driven-Element Gap
Target:

**0.250 in**

Preferred tolerance:

**±1/32 in (±0.8 mm)**

## 20.4 Boom Length
Target:

**30.000 in**

Recommended tolerance:

**±1/16 in**

Boom-end squareness should be adequate for repeatable datum measurement.

---

# 21. Recommended Marking Procedure
For each boom:

1. Cut to 30.000 in.

2. Square/deburr both ends.

3. Choose one end as FRONT.

4. Permanently mark:

   - `FRONT`

   - Arrow indicating direction of gain

   - `2 M` or `70 CM`

5. Draw a longitudinal reference line.

6. Measure every station independently from FRONT.

7. Mark station with a fine-point marker.

8. Label station ID.

9. Re-measure every station before drilling.

Do **not** locate later holes by measuring from the previous hole.

Use absolute dimensions from FRONT to avoid accumulated error.

---

# 22. Pre-Drill Verification Tables
## 22.1 2 m Boom
Before drilling, initial each verified location.

| Station | Target X | Verified |

| --- | ---: | :---: |

| 2M-D1 | 2.000 in | [ ] |

| 2M-DE | 13.500 in | [ ] |

| 2M-R | 21.500 in | [ ] |

| J1 | 4.500 in | [ ] |

| J2 | 22.500 in | [ ] |

## 22.2 70 cm Boom
| Station | Target X | Verified |

| --- | ---: | :---: |

| 70-D3 | 3.500 in | [ ] |

| 70-D2 | 9.500 in | [ ] |

| 70-D1 | 15.500 in | [ ] |

| 70-DE | 18.500 in | [ ] |

| 70-R | 21.000 in | [ ] |

| J1 | 4.500 in | [ ] |

| J2 | 22.500 in | [ ] |

The joint positions do not require drilling under the Rev. A cable-tie collar design.

They are marked only for assembly placement.

---

# 23. Master Bench Cut Checklist
## PVC
- [ ] Cut 2M boom to 30.000 in

- [ ] Cut 70CM boom to 30.000 in

- [ ] Mark both FRONT datums

- [ ] Mark both band IDs

- [ ] Deburr all PVC cuts

## 2 m Steel
- [ ] 2M-R = 41.400 in

- [ ] 2M-D1 = 35.400 in

- [ ] 2M-DE-L = 18.575 in

- [ ] 2M-DE-R = 18.575 in

- [ ] Deburr all steel ends

- [ ] Label every cut

## 70 cm Steel
- [ ] 70-R = 12.900 in

- [ ] 70-D1 = 11.900 in

- [ ] 70-D2 = 11.900 in

- [ ] 70-D3 = 11.700 in

- [ ] 70-DE-L = 6.175 in

- [ ] 70-DE-R = 6.175 in

- [ ] Deburr all steel ends

- [ ] Label every cut

## Hairpin
- [ ] #12 solid copper = 8.500 in

- [ ] Do not trim during O5/O6

## Dowel
- [ ] ST-1 = 12.000 in

- [ ] ST-2 = 12.000 in

- [ ] ST-3 = 12.000 in

---

# 24. Master Drill Checklist
## 2 m Boom
- [ ] 7/16 in hole at 2.000 in

- [ ] 7/16 in hole at 13.500 in

- [ ] 7/16 in hole at 21.500 in

## 70 cm Boom
- [ ] 7/16 in hole at 3.500 in

- [ ] 7/16 in hole at 9.500 in

- [ ] 7/16 in hole at 15.500 in

- [ ] 7/16 in hole at 18.500 in

- [ ] 7/16 in hole at 21.000 in

## Feedpoint
- [ ] Do not pre-drill feed-screw holes until driven halves are installed

- [ ] Verify actual #6-32 clearance-bit fit before drilling

---

# 25. As-Built Dimensional Record
Complete after O6 mechanical assembly and **before O8 RF tuning**.

## 25.1 2 m As-Built
| Parameter | Design | As-Built | Deviation |

| --- | ---: | ---: | ---: |

| Boom length | 30.000 in | _____ | _____ |

| 2M-D1 length | 35.400 in | _____ | _____ |

| 2M-D1 position | 2.000 in | _____ | _____ |

| 2M-DE overall span | 37.400 in | _____ | _____ |

| 2M-DE gap | 0.250 in | _____ | _____ |

| 2M-DE position | 13.500 in | _____ | _____ |

| 2M-R length | 41.400 in | _____ | _____ |

| 2M-R position | 21.500 in | _____ | _____ |

| Hairpin length | 8.500 in | _____ | _____ |

## 25.2 70 cm As-Built
| Parameter | Design | As-Built | Deviation |

| --- | ---: | ---: | ---: |

| Boom length | 30.000 in | _____ | _____ |

| 70-D3 length | 11.700 in | _____ | _____ |

| 70-D3 position | 3.500 in | _____ | _____ |

| 70-D2 length | 11.900 in | _____ | _____ |

| 70-D2 position | 9.500 in | _____ | _____ |

| 70-D1 length | 11.900 in | _____ | _____ |

| 70-D1 position | 15.500 in | _____ | _____ |

| 70-DE overall span | 12.600 in | _____ | _____ |

| 70-DE gap | 0.250 in | _____ | _____ |

| 70-DE position | 18.500 in | _____ | _____ |

| 70-R length | 12.900 in | _____ | _____ |

| 70-R position | 21.000 in | _____ | _____ |

## 25.3 Joint / Orientation
| Parameter | Design | As-Built |

| --- | ---: | ---: |

| J1 position | 4.500 in | _____ |

| J2 position | 22.500 in | _____ |

| Operating relative angle | Approx. 90° | _____ |

| Storage configuration functional | Yes | Yes / No |

---

# 26. Cut-Sheet Change Control
Before fabrication begins, any change to an RF-critical dimension requires:

1. O3 review

2. O5 revision

3. Revision number increment

4. Reason documented in Git history

After fabrication begins:

- Measured dimensional differences belong in **As-Built**

- Tuning changes belong in **As-Tuned / O8**

- Do not silently rewrite the original design dimensions

---

# 27. O5 Acceptance Checklist
O5 may be considered complete when:

- [x] 2 m element cut lengths are defined

- [x] 70 cm element cut lengths are defined

- [x] Driven-element half lengths are defined

- [x] Driven-element gaps are defined

- [x] Two 30.000 in boom cuts are defined

- [x] 2 m absolute drilling positions are defined

- [x] 70 cm absolute drilling positions are defined

- [x] Adjacent spacing agrees with O3

- [x] Main element-hole diameter and 2 m stiffener interface are defined

- [x] Feed-screw match-drilling method and local attachment geometry are defined

- [x] 2 m hairpin cut length is defined

- [x] Dowel/stiffener initial cuts are defined

- [x] Dual-boom joint locations and long-tie requirements are defined

- [x] Operating orientation is defined

- [x] Storage orientation is defined

- [x] Fabrication tolerances are defined

- [x] As-built recording tables are provided

- [x] O5 dimensions agree with O3

- [x] O5 material assumptions agree with O4

- [ ] O5 has been committed to the GitHub repository

---

# 28. Revision Control
| Revision | Date | Description |

| --- | --- | --- |

| Rev. A | 2026-08-24 | Initial formal O5 mechanical drawing and cut sheet using finalized O3 dimensions; dual-boom V1 joint defined using cable-tie rotating collars |

Future revisions should preserve prior history.

---

# 29. Engineering Intent
O5 exists to remove fabrication ambiguity.

The operator should not need to calculate antenna geometry while standing at the workbench.

The intended workflow is:

```text

O3 RF DIMENSIONS

        ↓

O5 CUT / DRILL SHEET

        ↓

O6 PHYSICAL FABRICATION

        ↓

AS-BUILT DIMENSIONS

        ↓

O8 RF MEASUREMENT

        ↓

AS-TUNED CONFIGURATION

```

A successful O5 document means every critical cut and layout dimension can be traced back to the design baseline and later compared against the physical antenna.

---

**End of O5 Mechanical Drawing & Cut Sheet**
