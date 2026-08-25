# O6 — Fabrication & Assembly

## Tape Measure Satellite Yagi

**Project:** Tape Measure Satellite Yagi  
**Document:** O6 Fabrication & Assembly Procedure  
**Repository Path:** `docs/fabrication.md`  
**Application:** Amateur-Radio Satellite / ISS Operation  
**Bands:** 2 m / 70 cm  
**Design Inputs:** O3 Antenna Design & Dimensions, O4 Bill of Materials & Sourcing, O5 Mechanical Drawing & Cut Sheet  
**Design Status:** Pre-Fabrication Build Procedure  
**Revision:** Rev. A  
**Date:** 2026-08-24

---

# 1. Purpose

This document defines the formal fabrication and mechanical assembly procedure for the Tape Measure Satellite Yagi.

It converts the O3 design and O5 cut sheet into a repeatable bench process that produces a mechanically complete antenna structure ready for:

- O7 — Feed & Matching System
- O8 — Initial RF Testing & Tuning
- O9 — Field Performance Testing
- O10 — Satellite / ISS Field Validation

This procedure controls:

- Material preparation
- Boom cutting
- Dimensional layout
- Hole drilling
- Tape-steel cutting
- Element labeling
- Driven-element mechanical preparation
- Stiffener installation
- Dual-boom assembly
- Feedpoint mounting-hole preparation
- Mechanical inspection
- As-built dimensional recording
- Build photographs
- Fabrication deviations

O6 does **not** install or electrically terminate the coax feed lines, matching network, coax chokes, BNC feed interfaces, or other RF-feed components. Those operations belong to O7.

O6 also does **not** include RF tuning. Any dimensional or matching changes resulting from measurement belong to O8 and must be recorded as **as-tuned** changes rather than silently modifying the original O3/O5 baseline.

---

# 2. Required Inputs Before Fabrication

Fabrication should not begin until the following repository documents are available and internally consistent:

- `docs/design.md`
- `docs/bill-of-materials.md`
- `docs/cut-sheet.md`
- `docs/fabrication.md`

The builder should verify that:

- O3 contains the finalized antenna dimensions.
- O4 contains the required materials.
- O5 contains the finalized cut and drill locations.
- All purchased substitutions have been reviewed.
- No unresolved material mismatch affects O5 geometry.
- The actual tape-measure blade fits the planned boom-hole concept before production drilling begins.

---

# 3. Required Materials

The O6 mechanical build uses the materials defined in O4.

Primary O6 materials:

- 1/2 in Schedule 40 PVC
- Narrow flexible conductive tape-measure steel
- 3/8 in nonconductive dowel or fiberglass stiffener
- Small cable ties for 2 m stiffener attachment
- UV-resistant cable ties for the dual-boom rotating collars
  - **8 in preferred**
  - **6 in minimum**
- #6-32 feedpoint machine screws and related hardware for match-drilling and fit verification

The following O4 items are reserved primarily for O7 and are **not required to complete O6**:

- RG-58 50 Ω coax feed lines
- Feed lugs
- #12 AWG solid copper hairpin conductor
- Heat-shrink tubing
- Electrical tape
- Electronics solder
- Electronics-compatible flux

---

# 4. Required Tools

Minimum O6 fabrication tools:

- Measuring tape or steel rule
- Fine-point permanent marker
- Square
- Drill
- 7/16 in drill bit
- Approx. 5/32 in drill bit for #6 feedpoint hardware
- PVC cutter or hacksaw
- Snips suitable for tape-measure steel
- File or deburring tool
- Safety glasses

Recommended:

- Bench vise or padded workholding
- Center punch
- Calipers
- Small round file

O7-specific electrical tools such as wire strippers, terminal crimpers, soldering equipment, heat-shrink tools, and multimeters are not required to complete the mechanical O6 phase.

---

# 5. Safety Requirements

## 5.1 Eye Protection

Safety glasses shall be worn when:

- Cutting tape-measure steel
- Drilling PVC
- Match-drilling tape steel
- Deburring
- Trimming stiffener material

Spring-steel tape can release stored mechanical energy after cutting.

## 5.2 Tape-Steel Handling

Freshly cut tape steel may have:

- Sharp corners
- Burrs
- Spring-back
- Kinked edges

Every cut end must be deburred before normal handling.

## 5.3 Drilling

Do not hold PVC or steel directly in the hand while drilling if a vise or clamp is available.

Avoid crushing PVC with excessive clamping force.

When match-drilling the feedpoint hardware, control the workpiece so the drill cannot snag the spring-steel tape and pull it unexpectedly.

---

# 6. Fabrication Control Philosophy

The build shall follow three configuration states.

## 6.1 As-Designed

The dimensions specified in O3/O5.

## 6.2 As-Built

The dimensions actually measured after O6 mechanical fabrication and assembly.

## 6.3 As-Tuned

The final configuration after O7 feed-system installation and O8 RF tuning.

Do not overwrite the original design dimensions with as-built or as-tuned values.

---

# 7. Step 1 — Inspect Incoming Materials

Before cutting anything, inspect all material required for O6.

## PVC

Verify:

- Correct nominal size
- At least 60 in usable length
- No cracks
- No major bends
- Clean enough for marking

## Tape Steel

Verify:

- Conductive steel
- Width fits the O5 hole concept
- At least 18 ft usable length
- No severe kinks
- No rust or mechanical damage in critical sections

## Dowel / Fiberglass

Verify:

- 3/8 in nominal diameter
- Straight
- Nonconductive
- At least 36 in usable length

## Cable Ties

Verify:

- Small ties are available for 2 m stiffener attachment
- Dual-boom collar ties are UV-resistant where practical
- Dual-boom collar ties are **8 in preferred or 6 in minimum**

## Feedpoint Hardware

Verify:

- #6-32 screws fit the selected nuts
- Washers fit the screws
- Hardware is available for match-drilling and mechanical fit checks

If any major discrepancy exists, stop fabrication and update O4/O5 before continuing.

---

# 8. Step 2 — Cut PVC Booms

Cut:

| Boom ID | Finished Length |
| --- | ---: |
| 2M-BOOM | **30.000 in** |
| 70CM-BOOM | **30.000 in** |

After cutting:

1. Square each end as closely as practical.
2. Deburr inside and outside edges.
3. Verify final length.
4. Select one end as FRONT.
5. Mark:
   - `FRONT`
   - Direction-of-gain arrow
   - Band ID

Example:

```text
FRONT / GAIN →

2 M
│────────────────────────────────────────────│
0.000                                    30.000 in
```

---

# 9. Step 3 — Establish Reference Lines

Draw a longitudinal reference line along each boom.

This line is used to:

- Keep element holes aligned
- Keep station marks consistent
- Help verify drilling perpendicularity

Do not rely on visual estimation alone.

---

# 10. Step 4 — Lay Out 2 Meter Element Stations

Measure every location from the FRONT datum.

Mark:

| Station | Position from FRONT |
| --- | ---: |
| 2M-D1 | **2.000 in** |
| 2M-DE | **13.500 in** |
| 2M-R | **21.500 in** |

Also mark dual-boom joint locations:

| Joint | Position from FRONT |
| --- | ---: |
| J1 | **4.500 in** |
| J2 | **22.500 in** |

Re-measure each position independently from FRONT.

Do not use chained measurements from one station to the next.

---

# 11. Step 5 — Lay Out 70 Centimeter Element Stations

Measure every location from the FRONT datum.

Mark:

| Station | Position from FRONT |
| --- | ---: |
| 70-D3 | **3.500 in** |
| 70-D2 | **9.500 in** |
| 70-D1 | **15.500 in** |
| 70-DE | **18.500 in** |
| 70-R | **21.000 in** |

Also mark:

| Joint | Position from FRONT |
| --- | ---: |
| J1 | **4.500 in** |
| J2 | **22.500 in** |

---

# 12. Quality Gate A — Layout Verification

Before drilling:

- [ ] Both booms measure 30.000 in
- [ ] Both FRONT datums are clearly marked
- [ ] Band labels are present
- [ ] Longitudinal reference lines are present
- [ ] All stations were measured independently from FRONT
- [ ] 2 m spacing agrees with O5
- [ ] 70 cm spacing agrees with O5
- [ ] J1/J2 marks are present

If any mark is questionable, erase and re-mark it before drilling.

---

# 13. Step 6 — Drill Practice Hole

Before drilling the finished booms:

1. Use scrap 1/2 in PVC.
2. Drill one 7/16 in through-hole.
3. Deburr the hole.
4. Test-fit the actual purchased tape steel.

The tape should pass through without destructive force.

If the blade does not fit:

**STOP.**

Do not enlarge every antenna hole blindly.

Update the mechanical mounting method first.

---

# 14. Step 7 — Drill Main Element Holes

Use a:

**7/16 in drill bit**

Drill through the approximate center of the PVC cross-section at each element station.

## 2 m Boom

Drill at:

- 2.000 in
- 13.500 in
- 21.500 in

## 70 cm Boom

Drill at:

- 3.500 in
- 9.500 in
- 15.500 in
- 18.500 in
- 21.000 in

Keep the drill approximately perpendicular to the boom.

---

# 15. Step 8 — Deburr Main Element Holes

Remove:

- PVC chips
- Sharp edges
- Internal burrs

Use a round file or deburring tool if necessary.

Do not excessively enlarge the holes.

---

# 16. Quality Gate B — Boom Geometry

Verify:

- [ ] 3 element holes exist on the 2 m boom
- [ ] 5 element holes exist on the 70 cm boom
- [ ] Holes are centered reasonably well
- [ ] Holes are approximately square to the boom
- [ ] No PVC cracking exists
- [ ] Actual tape steel test-fits
- [ ] Joint marks remain visible

If a hole is badly misplaced, replacing the boom is preferred over attempting to compensate by changing RF geometry.

---

# 17. Step 9 — Cut 2 Meter Tape-Steel Elements

Cut and immediately label each piece.

## Passive Elements

| ID | Finished Length |
| --- | ---: |
| 2M-R | **41.400 in** |
| 2M-D1 | **35.400 in** |

## Driven Element Halves

| ID | Finished Length |
| --- | ---: |
| 2M-DE-L | **18.575 in** |
| 2M-DE-R | **18.575 in** |

Center gap when assembled:

**0.250 in**

Overall driven-element span:

**37.400 in**

---

# 18. Step 10 — Cut 70 Centimeter Tape-Steel Elements

## Passive Elements

| ID | Finished Length |
| --- | ---: |
| 70-R | **12.900 in** |
| 70-D1 | **11.900 in** |
| 70-D2 | **11.900 in** |
| 70-D3 | **11.700 in** |

## Driven Element Halves

| ID | Finished Length |
| --- | ---: |
| 70-DE-L | **6.175 in** |
| 70-DE-R | **6.175 in** |

Center gap when assembled:

**0.250 in**

Overall driven-element span:

**12.600 in**

---

# 19. Step 11 — Deburr and Label Steel Elements

For every steel element:

1. Deburr both cut ends.
2. Remove sharp corners.
3. Verify length.
4. Mark the element ID using permanent marker or a temporary tape label.

Do not rely on visual recognition.

The 70 cm directors differ by only small dimensional amounts.

---

# 20. Quality Gate C — Element Verification

Before installation:

## 2 m

- [ ] 2M-R = 41.400 in
- [ ] 2M-D1 = 35.400 in
- [ ] 2M-DE-L = 18.575 in
- [ ] 2M-DE-R = 18.575 in

## 70 cm

- [ ] 70-R = 12.900 in
- [ ] 70-D1 = 11.900 in
- [ ] 70-D2 = 11.900 in
- [ ] 70-D3 = 11.700 in
- [ ] 70-DE-L = 6.175 in
- [ ] 70-DE-R = 6.175 in

Do not trim any element for RF tuning during O6.

---

# 21. Step 12 — Cut Stiffeners

Cut the 3/8 in nonconductive stiffener stock into:

| ID | Initial Length |
| --- | ---: |
| ST-1 | **12.000 in** |
| ST-2 | **12.000 in** |
| ST-3 | **12.000 in** |

These dimensions are mechanical starting values and may be shortened for fit.

They are not RF-critical antenna-element lengths.

---

# 22. Step 13 — Dry-Fit 2 Meter Passive Elements

Install:

- 2M-D1
- 2M-R

through their corresponding 7/16 in holes.

Center each continuous element so the left and right projections are approximately equal.

Do not permanently secure yet.

---

# 23. Step 14 — Dry-Fit 70 Centimeter Passive Elements

Install:

- 70-D3
- 70-D2
- 70-D1
- 70-R

through their corresponding boom holes.

Center each element.

Verify that:

- All 70 cm elements are parallel
- No blade is severely twisted
- Element IDs are in the correct physical order

---

# 24. Step 15 — Install 2 Meter Driven Halves

Insert:

- 2M-DE-L
- 2M-DE-R

from opposite sides of the driven-element station.

Set:

**Center gap = 0.250 in**

Verify:

**Overall span = 37.400 in**

Keep both halves symmetric about the boom centerline.

Do not electrically terminate or permanently lock the feedpoint during O6.

---

# 25. Step 16 — Install 70 Centimeter Driven Halves

Install:

- 70-DE-L
- 70-DE-R

Set:

**Center gap = 0.250 in**

Verify:

**Overall span = 12.600 in**

Keep both halves symmetric.

Do not electrically terminate the feedpoint during O6.

---

# 26. Step 17 — Install 2 Meter Stiffeners

Install one nonconductive stiffener at each 2 m element station.

For each station:

1. Position the 3/8 in stiffener alongside the tape-measure element near the boom.
2. Keep the stiffener centered approximately on the boom/element intersection.
3. Secure the tape steel to the stiffener using small cable ties.
4. Use enough tension to support the tape without permanently flattening, creasing, or distorting it.
5. Verify the stiffener does not shift the RF element away from its intended station.
6. Shorten the stiffener only if required for fit, clearance, or portability.

The stiffeners are mechanical supports and are not RF-critical conductive elements.

Do not substitute metal stiffeners without design review.

---

# 27. Step 18 — Center and Align All Elements

Check each continuous element.

Within each band:

- Elements shall be parallel.
- Elements shall be approximately perpendicular to the boom.
- Continuous elements shall be centered.
- Driven halves shall be symmetrical.
- No element shall contact another element.

Recommended centering accuracy:

## 2 m

**≤ 1/8 in**

## 70 cm

**≤ 1/16 in**

---

# 28. Step 19 — Mark Feed-Screw Locations

Feed-screw holes are intentionally **match-drilled during assembly** after the driven-element halves are installed and centered.

For each driven half:

1. Select a screw position close to the feedpoint.
2. Verify the screw will penetrate:
   - The local PVC wall at the feedpoint
   - Only the intended driven-element half
3. Verify the opposite driven half remains electrically isolated.
4. Preserve the 0.250 in center gap.
5. Confirm the planned screw location leaves adequate PVC material around the hole.

Do not place the screw so close to an edge that cracking is likely.

The #6-32 × 1/2 in screw is local feedpoint hardware. It is **not** intended to pass completely through the full outside diameter of the PVC boom.

---

# 29. Step 20 — Match-Drill Feed-Screw Holes

Use a clearance bit appropriate for the actual #6-32 hardware.

Nominal starting point:

**approximately 5/32 in**

Match-drill carefully through:

- The local PVC wall
- The installed tape-steel driven-element half

Do not intentionally drill through both sides of the boom.

Deburr the completed holes.

Avoid allowing the drill to snag the spring-steel tape.

At the end of O6, the feed-screw holes should be mechanically ready for O7 feed-system installation.

---

# 30. Step 21 — Assemble Dual-Boom Rotating Collars

Align the two booms with their FRONT ends pointing in the same longitudinal direction.

At:

- **J1 = 4.500 in from FRONT**
- **J2 = 22.500 in from FRONT**

install one UV-resistant cable tie around both booms at each joint.

Use:

- **8 in ties preferred**
- **6 in ties minimum**

These ties act as rotating collars.

Tighten each collar only enough to:

- Keep the booms together
- Prevent separation
- Allow deliberate relative rotation

Do not cinch the ties into rigid clamps.

Verify the collars do not migrate into antenna element holes or interfere with nearby elements.

---

# 31. Step 22 — Verify Operating Orientation

Rotate the booms until the two element planes are approximately:

**90° apart**

This is the normal operating configuration.

Verify:

- J1/J2 remain in position
- Cable ties do not interfere with elements
- Both booms remain mechanically retained
- Relative rotation feels deliberate rather than uncontrolled

Because O7 feed lines are not yet installed, coax routing and feedpoint-wire behavior are verified later during O7.

---

# 32. Step 23 — Verify Storage Orientation

Rotate the booms toward a parallel/folded configuration.

Verify:

- Elements can be positioned for transport
- J1/J2 remain in place
- The booms do not separate
- No element is mechanically overloaded by the folding action

Final storage behavior with installed coax is rechecked during O7.

---

# 33. Quality Gate D — Mechanical Assembly

Verify:

- [ ] 2 m elements are correctly ordered
- [ ] 70 cm elements are correctly ordered
- [ ] All passive elements are centered
- [ ] Driven halves are symmetrical
- [ ] 2 m center gap = 0.250 in
- [ ] 70 cm center gap = 0.250 in
- [ ] 2 m stiffeners are installed
- [ ] Feedpoint holes are match-drilled and deburred
- [ ] J1/J2 collars use 8 in preferred / 6 in minimum ties
- [ ] J1/J2 collars retain both booms
- [ ] Booms rotate through operating and storage positions
- [ ] No sharp exposed steel burrs remain
- [ ] No visible PVC cracking exists

Do not install or electrically terminate the O7 feed system as part of this quality gate.

---

# 34. Step 24 — Record As-Built Mechanical Dimensions

Use the O5 as-built tables.

At minimum measure and record:

## 2 m

- Boom length
- Director length
- Director position
- Driven overall span
- Driven center gap
- Driven position
- Reflector length
- Reflector position

## 70 cm

- Boom length
- D3 length/position
- D2 length/position
- D1 length/position
- Driven overall span
- Driven gap
- Driven position
- Reflector length/position

Also record:

- J1 position
- J2 position
- Approximate operating boom angle
- Storage configuration functionality

If the O5 as-built table contains feed-system fields such as hairpin dimensions, leave those for completion during O7.

Do not assume the antenna exactly matches nominal dimensions.

Measure it.

---

# 35. Step 25 — Photograph the Mechanical Build

Minimum recommended O6 photographs:

1. Raw materials before cutting
2. Both finished 30 in booms
3. Boom layout marks before drilling
4. Drilled 2 m boom
5. Drilled 70 cm boom
6. All 2 m steel elements laid out with ruler
7. All 70 cm steel elements laid out with ruler
8. 2 m driven-element gap
9. 70 cm driven-element gap
10. 2 m stiffener installation
11. Match-drilled 2 m feedpoint mounting holes
12. Match-drilled 70 cm feedpoint mounting holes
13. J1/J2 rotating collars
14. Complete operating configuration
15. Complete storage configuration

Store these images under:

```text
images/
└── fabrication/
    ├── materials/
    ├── boom-layout/
    ├── elements/
    ├── mechanical-assembly/
    └── final-assembly/
```

O7 feedpoint, coax-routing, choke, and electrical-termination photographs should be stored separately with the feed-system documentation.

---

# 36. Fabrication Deviation Record

Any meaningful departure from O5 shall be recorded.

| Deviation ID | Part / Feature | Designed Value | As-Built Value | Reason | Accepted? |
| --- | --- | --- | --- | --- | --- |
| | | | | | |
| | | | | | |
| | | | | | |

Examples:

- Element cut slightly short
- Hole drilled off station
- Different cable tie used
- Dowel shortened
- Feed screw moved
- Joint location shifted

Do not hide errors.

A documented deviation can later be correlated with measured RF performance.

---

# 37. Fabrication Stop Conditions

Stop fabrication and review the design if:

- Tape steel does not fit the 7/16 in boom hole
- A main element hole is significantly misplaced
- PVC cracks around an RF element station
- A driven-element half is cut materially short
- Feedpoint mounting holes cannot preserve electrical isolation between driven halves
- Dual-boom collars cannot retain the booms while permitting deliberate rotation
- Dual-boom joint prevents approximately 90° operation
- A material substitution changes the antenna geometry

Do not compensate for a fabrication error by arbitrarily changing another RF dimension.

Electrical feedline, BNC, hairpin, and coax-routing problems belong to O7 rather than O6.

---

# 38. O6 Completion State

O6 is complete when the antenna is:

- Mechanically assembled
- Dimensionally recorded
- Equipped with correctly positioned and aligned antenna elements
- Equipped with the required 2 m nonconductive stiffeners
- Prepared with match-drilled feedpoint mounting holes
- Equipped with functional dual-boom rotating collars
- Capable of operating and storage boom rotation
- Photographically documented
- Ready for O7 feed-system installation

O6 does **not** require:

- Coax feedline installation
- Feed-lug installation
- Hairpin installation
- Coax choke formation
- BNC feed labeling
- DC feed continuity checks
- Final SWR
- Final resonance
- Final impedance match
- Satellite reception
- Terrestrial pattern measurements

Those belong to later phases.

---

# 39. O6 Acceptance Checklist

O6 may be considered complete when:

- [ ] Materials have passed receiving inspection
- [ ] Both PVC booms are cut to 30.000 in
- [ ] FRONT datums are marked
- [ ] All main element stations are drilled
- [ ] All tape-steel elements are cut and labeled
- [ ] All steel ends are deburred
- [ ] 2 m elements are installed
- [ ] 70 cm elements are installed
- [ ] Driven-element gaps are set
- [ ] 2 m stiffeners are installed
- [ ] Feedpoint holes are match-drilled
- [ ] Feedpoint holes are deburred
- [ ] Dual-boom rotating collars are installed
- [ ] Joint ties meet the 8 in preferred / 6 in minimum requirement
- [ ] Operating orientation is functional
- [ ] Storage orientation is functional
- [ ] As-built mechanical dimensions are recorded
- [ ] Fabrication deviations are documented
- [ ] Build photographs are archived under `images/fabrication/`
- [ ] Mechanical assembly is ready for O7
- [ ] O6 has been committed to the GitHub repository

---

# 40. Handoff to O7 and O8

After O6, the mechanically complete antenna structure is transferred to O7.

## O7 constructs and verifies:

- Driven-element electrical contact surfaces
- RG-58 feed lines
- Feed lugs
- Feedpoint electrical connections
- 2 m hairpin matching element
- 2 m six-turn coax choke
- 70 cm four-turn coax choke
- Coax routing and strain relief
- BNC band labeling
- DC continuity and isolation checks
- Feed-system mechanical integrity
- Final feed architecture
- External diplexer/interface strategy where applicable

O7 should also recheck:

- Driven-element center gaps
- Boom rotation with installed coax
- Storage configuration with installed coax
- Any mechanical effect caused by feedline routing

## O8 performs:

- NanoVNA calibration
- Broad S11 sweeps
- Narrow sweeps
- SWR measurement
- Complex impedance measurement
- Smith-chart analysis
- Feedline-sensitivity testing
- Hairpin tuning
- Final as-tuned recording

No RF tuning shall be performed without updating the project record.

---

# 41. Revision Control

| Revision | Date | Description |
| --- | --- | --- |
| Rev. A | 2026-08-24 | Initial formal O6 fabrication and mechanical assembly procedure based on finalized O3/O4/O5 design; O7 electrical feed work separated into its own phase |

Future revisions should preserve prior history.

---

# 42. Engineering Intent

O6 is intended to make fabrication reproducible while preserving the boundary between mechanical fabrication and RF feed-system construction.

The desired project sequence is:

```text
O3 — RF DESIGN
      ↓
O4 — MATERIAL CONTROL
      ↓
O5 — CUT / DRILL CONTROL
      ↓
O6 — MECHANICAL FABRICATION
      ↓
AS-BUILT MECHANICAL RECORD
      ↓
O7 — FEED & MATCHING SYSTEM
      ↓
O8 — RF CHARACTERIZATION / TUNING
```

The finished antenna should not merely exist.

Its physical construction should be traceable, measurable, repeatable, and directly comparable to the original design.

---

**End of O6 Fabrication & Assembly Procedure**
