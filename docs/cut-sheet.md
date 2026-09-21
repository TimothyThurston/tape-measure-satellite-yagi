# O5 - Mechanical Drawing and Cut Sheet

## Tape Measure Satellite Yagi

**Project:** Tape Measure Satellite Yagi  
**Project ID:** TM-YAGI-01  
**Document:** O5 Mechanical Drawing and Cut Sheet  
**Repository path:** `docs/cut-sheet.md`  
**Application:** Handheld amateur-radio satellite and ISS operation  
**Bands:** 2 m / 70 cm  
**Revision:** Rev. B  
**Date:** 2026-09-21  
**Status:** Controlled pre-fabrication baseline  

---

## 1. Purpose and control

This document is the controlling cut, mark, drill, and mechanical-fit sheet for the Revision B Tape Measure Satellite Yagi.

It supersedes the Rev. A O5 PDF. Dimensions in inches govern; metric values are rounded references. Do not scale sketches, photographs, or printed pages.

Revision B retains the verified RF element lengths and longitudinal element stations. It corrects the mechanically conflicting joint, choke, feedpoint, support, and inspection instructions in Rev. A.

If an older document conflicts with this sheet on cutting or mechanical fabrication, this O5 Rev. B sheet controls. Electrical tuning and RF acceptance remain controlled by O7 and O8.

---

## 2. Audit disposition

### 2.1 Verified and retained

| Item checked | Result |
|---|---|
| Two 30.000 in PVC booms | Retained |
| 2 m element lengths | Arithmetic verified; retained |
| 70 cm element lengths | Arithmetic verified; retained |
| 0.250 in driven-element center gaps | Verified; retained |
| Driven-half calculations | Verified: 18.575 in for 2 m and 6.175 in for 70 cm |
| Front-datum element stations | Verified against the 30.000 in rear-datum conversion; retained |
| Adjacent within-band spacings | Verified; retained |
| Net tape-steel requirement | Verified as 174.700 in |
| Three 3/8 in x 12.000 in 2 m supports | Retained and made explicit |
| 8.500 in #12 solid-copper hairpin | Retained as an initial tunable blank, not a guaranteed final match |

### 2.2 Corrected in Rev. B

| Rev. A problem | Rev. B correction |
|---|---|
| Rotating tie-wrap collars and folding language | Removed. The operating assembly is fixed; separate the booms for storage by cutting and replacing the ties. |
| Separate boom-joint assumptions | Removed. There is no hinge, pivot, tee, crossbar, or joint assembly. |
| Four-inch ties around both booms | Replaced by two 8 in minimum UV-resistant ties, one at each retention station. |
| Touching booms | Replaced by two nonconductive separator pads providing at least 0.250 in installed bare-surface clearance. |
| Six-turn and four-turn RG-58 coils | Removed. Use band-appropriate snap-on ferrites after the feedpoint. |
| Uncontrolled feed-screw location and hardware stack | Added a mandatory material coupon, symmetric hole-location rule, node stack, and screw-length selection check. |
| Instruction to tin clamped tape contact | Removed. Do not tin beneath a washer or other mechanical clamp. |
| Hairpin bend described as noncritical | Replaced by a symmetric, measured starting geometry and an as-built record. |
| Blanket requirement for no DC short between 2 m driven halves | Corrected. The 2 m feed is open only before the hairpin is connected; the completed hairpin creates intended DC continuity. |
| Loose station tolerance at the closely spaced reflectors | Added a cross-boom relative-location and physical-clearance requirement. |
| Ambiguous support cuts of approximately 8-12 in | Replaced by three controlled 12.000 in support pieces. |

---

## 3. Mechanical configuration

The finished antenna uses two separate, intact, parallel PVC booms:

| Boom | Band | Finished length | Element plane |
|---|---|---:|---|
| Boom A | 2 m | 30.000 in (762.0 mm) | Reference plane A |
| Boom B | 70 cm | 30.000 in (762.0 mm) | 90 degrees to plane A in the operating assembly |

Assembly requirements:

- Align both FRONT ends with each other and both REAR ends with each other.
- Keep the boom longitudinal centerlines parallel.
- Set the 2 m and 70 cm element planes to **90 degrees +/- 2 degrees**.
- Set the line between the two boom centers approximately halfway between the two element planes: **45 degrees +/- 5 degrees** from either plane.
- Maintain at least **0.250 in (6.35 mm)** bare-surface clearance between the PVC booms at both retention stations.
- Maintain at least **0.125 in (3.2 mm)** physical clearance between either boom and every element, dowel, feed screw, lug, hairpin, ferrite, and cable on the other boom.
- Do not rotate or fold one boom relative to the other while the retention ties are installed.
- For storage or transport, cut the two retention ties and separate the booms. Use new ties for reassembly.

There is no separate boom-joint mechanism.

---

## 4. Master cut list

Cut finished lengths from the actual material. Deburr every cut edge and label each part immediately.

### 4.1 Tape-steel elements

| Cut ID | Band | Element | Finished conductive length | Metric | Quantity | Cut detail |
|---|---|---|---:|---:|---:|---|
| 2M-R | 2 m | Reflector | 41.400 in | 1051.6 mm | 1 | Continuous strip |
| 2M-DE-L | 2 m | Driven left half | 18.575 in | 471.8 mm | 1 | One half of split driven element |
| 2M-DE-R | 2 m | Driven right half | 18.575 in | 471.8 mm | 1 | One half of split driven element |
| 2M-D1 | 2 m | Director 1 | 35.400 in | 899.2 mm | 1 | Continuous strip |
| 70-R | 70 cm | Reflector | 12.900 in | 327.7 mm | 1 | Continuous strip |
| 70-DE-L | 70 cm | Driven left half | 6.175 in | 156.8 mm | 1 | One half of split driven element |
| 70-DE-R | 70 cm | Driven right half | 6.175 in | 156.8 mm | 1 | One half of split driven element |
| 70-D1 | 70 cm | Director 1 | 11.900 in | 302.3 mm | 1 | Continuous strip |
| 70-D2 | 70 cm | Director 2 | 11.900 in | 302.3 mm | 1 | Continuous strip |
| 70-D3 | 70 cm | Director 3 | 11.700 in | 297.2 mm | 1 | Continuous strip |

Tape-steel totals:

| Group | Net length |
|---|---:|
| 2 m elements | 113.950 in |
| 70 cm elements | 60.750 in |
| **Total net steel** | **174.700 in (14.558 ft)** |

Reserve at least 18 ft of usable approximately 3/8 in wide conductive tape steel. The difference covers cleanup, kerf, damaged coating, the required coupon, and replacement pieces.

### 4.2 Non-element cuts

| Cut ID | Material | Finished size | Quantity | Use |
|---|---|---:|---:|---|
| PVC-2M | Nominal 1/2 in Schedule 40 PVC | 30.000 in | 1 | 2 m boom |
| PVC-70 | Nominal 1/2 in Schedule 40 PVC | 30.000 in | 1 | 70 cm boom |
| ST-1 | 3/8 in nonconductive dowel or fiberglass rod | 12.000 in | 1 | 2M-D1 support |
| ST-2 | 3/8 in nonconductive dowel or fiberglass rod | 12.000 in | 1 | 2M-DE support |
| ST-3 | 3/8 in nonconductive dowel or fiberglass rod | 12.000 in | 1 | 2M-R support |
| 2M-HP | #12 AWG solid copper, fully bare | 8.500 in initial blank | 1 | Tunable 2 m shunt hairpin |
| PAD-1 | Nylon, acetal, or HDPE | 1.000 x 0.500 x 0.250 in minimum | 1 | Front retention separator |
| PAD-2 | Nylon, acetal, or HDPE | 1.000 x 0.500 x 0.250 in minimum | 1 | Rear retention separator |

Pad thickness is the minimum installed separation. If a pad compresses, permanently deforms, or measures less than 0.250 in after installation, replace it with a thicker part.

### 4.3 Stock breakdown

One 10 ft PVC length is sufficient for both 30.000 in booms and leaves approximately 60 in before saw kerf. Do not cut the booms into folding sections.

Do not cut either RG-58 feedline until its routing, ferrite fit, and strain-relief locations have been dry-fitted. At that point remove only the antenna-side connector from each cable; retain the factory BNC male at the operator end.

---

## 5. Driven-element arithmetic

The 0.250 in center gap is part of the overall span but contains no conductive tape steel.

| Band | Overall span | Center gap | Calculation | Each metal half |
|---|---:|---:|---|---:|
| 2 m | 37.400 in | 0.250 in | (37.400 - 0.250) / 2 | 18.575 in |
| 70 cm | 12.600 in | 0.250 in | (12.600 - 0.250) / 2 | 6.175 in |

Keep the two halves of each driven element equal before tuning. If O8 tuning requires shortening, remove equal amounts from the outer ends unless the tuning procedure explicitly records another method.

---

## 6. Boom datum and station schedule

### 6.1 Datum

- **FRONT = 0.000 in** at the director end and direction of intended gain.
- **REAR = 30.000 in** at the operator/handle end.
- Measure every station independently from the FRONT datum. Do not chain measurements from one element to the next.
- Rear-datum cross-check: `X_REAR = 30.000 - X_FRONT`.

### 6.2 Boom A - 2 m stations

| Station | X from FRONT | X from REAR | Adjacent spacing | Hole |
|---|---:|---:|---:|---|
| 2M-D1 | 2.000 in (50.8 mm) | 28.000 in (711.2 mm) | - | 7/16 in through |
| 2M-DE | 13.500 in (342.9 mm) | 16.500 in (419.1 mm) | 11.500 in from 2M-D1 | 7/16 in through |
| 2M-R | 21.500 in (546.1 mm) | 8.500 in (215.9 mm) | 8.000 in from 2M-DE | 7/16 in through |

### 6.3 Boom B - 70 cm stations

| Station | X from FRONT | X from REAR | Adjacent spacing | Hole |
|---|---:|---:|---:|---|
| 70-D3 | 3.500 in (88.9 mm) | 26.500 in (673.1 mm) | - | 7/16 in through |
| 70-D2 | 9.500 in (241.3 mm) | 20.500 in (520.7 mm) | 6.000 in from 70-D3 | 7/16 in through |
| 70-D1 | 15.500 in (393.7 mm) | 14.500 in (368.3 mm) | 6.000 in from 70-D2 | 7/16 in through |
| 70-DE | 18.500 in (469.9 mm) | 11.500 in (292.1 mm) | 3.000 in from 70-D1 | 7/16 in through |
| 70-R | 21.000 in (533.4 mm) | 9.000 in (228.6 mm) | 2.500 in from 70-DE | 7/16 in through |

### 6.4 Dual-boom retention stations

| Retention station | X from FRONT | Components | Nearest RF station |
|---|---:|---|---|
| J1 | 4.500 in +/- 0.125 in | One PAD-1 and one 8 in minimum tie | 70-D3 at 3.500 in |
| J2 | 22.500 in +/- 0.125 in | One PAD-2 and one 8 in minimum tie | 2M-R at 21.500 in |

The pad long axis runs parallel to the booms. Center the pad and tie at the stated station. Do not drill either boom at J1 or J2.

---

## 7. Marking and drilling controls

### 7.1 Before drilling

1. Measure and record the actual PVC outside diameter.
2. Measure and record tape width, tape thickness, dowel diameter, and coax diameter.
3. Draw one straight longitudinal reference line on each boom.
4. Mark FRONT and REAR permanently on both booms.
5. Mark every station independently from FRONT.
6. Align the booms FRONT-to-FRONT and verify the 2M-R to 70-R station difference before drilling.

### 7.2 Mandatory material coupon

Before drilling any final element station, make one scrap PVC coupon using the actual PVC, tape steel, and support material.

The coupon must demonstrate:

- A clean 7/16 in through-hole without a split or crack.
- The actual 3/8 in support and tape can share the 2 m hole without crushing, permanent kinking, or forced distortion.
- The tape alone fits the 70 cm hole without uncontrolled looseness.
- A candidate approximately 5/32 in #6 clearance hole fits the actual screw.
- The proposed feed-node stack clamps securely using the shortest usable screw.
- The nut fully engages with at least two complete threads visible beyond it.
- No screw, washer, lug, or hairpin can touch the opposite driven half.

If the coupon fails, stop. Do not enlarge all final holes or substitute hardware without updating O5 and the as-built record.

### 7.3 Element-hole drilling

- Use a V-block, drill guide, or drill press fixture to prevent the round PVC from rolling.
- Drill a small pilot only if the fixture and material support it without cracking.
- Finish each controlled element hole at 7/16 in.
- Keep every hole axis perpendicular to the boom axis.
- Keep all holes on one boom parallel and in one element plane.
- Deburr inside and outside without enlarging the hole.
- Inspect the PVC for whitening, splitting, or cracks after each hole.

Do not drill feed-screw holes through the PVC boom as substitutes for the separate node screws.

---

## 8. Element installation geometry

### 8.1 Passive 2 m elements

- Center one 12.000 in nonconductive support at each 2 m station.
- Place the tape steel alongside the support through the validated 7/16 in hole.
- Center the conductive tape left-to-right to within 1/16 in.
- Keep the tape and support straight through the local boom cross-section.
- Retain the tape to the support with small ties or the O6 method; do not place metal retention hardware near the boom.

### 8.2 Passive 70 cm elements

- Pass the tape steel through the validated 7/16 in station hole.
- Center the conductive tape left-to-right to within 1/32 in.
- Use nonconductive retention only.

### 8.3 Driven elements

- Insert the two equal tape halves from opposite sides of the station.
- Use a 0.250 in nonconductive gauge between the physical inner steel ends.
- Establish an overall tip-to-tip span of 37.400 in on 2 m or 12.600 in on 70 cm.
- Keep the halves collinear, symmetric, and electrically isolated before feed hardware is installed.
- Remove the temporary gap gauge only after the halves are mechanically retained.
- Record the finished gap and overall span.

The 0.250 in steel-tip gap is not the distance between feed-screw centers.

---

## 9. Feed-node holes and hardware

There are four separate feed nodes: two on the 2 m driven element and two on the 70 cm driven element.

### 9.1 Hole location

After the driven halves are centered and the gap is fixed:

- Mark one screw hole on each driven half.
- Center the hole across the approximately 3/8 in tape width.
- Place each hole center **0.250 in +/- 0.062 in outboard of the adjacent PVC surface**.
- Mirror the left and right hole positions.
- Verify the entire screw, washer, lug, and hairpin envelope remains clear of the opposite half and the other boom.
- Drill approximately 5/32 in only after confirming clearance on the coupon and with the actual #6-32 screw.
- Record the final center-to-center node spacing.

### 9.2 Controlled stack at each node

From screw head toward the nut:

1. #6-32 stainless pan-head screw.
2. Clean bare tape-steel contact pad.
3. Coax ring lug.
4. Bare hairpin hook on 2 m only.
5. #6 stainless flat washer.
6. #6-32 stainless nut.

Use **one screw and one nut per node**, four nodes total. Begin with the 1/2 in screw. Use the 3/4 in screw only if the coupon shows that 1/2 in cannot provide full nut engagement; in either case use the shortest length that leaves at least two complete threads visible without approaching another conductor.

Prepare only the local contact pad. Do not remove coating from unnecessary areas. Do not tin the tape beneath the washer, ring lug, screw head, or nut; solder can creep under clamping pressure and loosen the joint.

### 9.3 Electrical node assignment

| Band | Node A | Node B |
|---|---|---|
| 2 m | Left driven half + coax center lug + one hairpin end | Right driven half + coax braid lug + other hairpin end |
| 70 cm | Left driven half + coax center lug | Right driven half + coax braid lug |

Either left/right convention may be reversed before assembly, but it must remain consistent, labeled, and recorded. Never connect both coax conductors to the same half.

---

## 10. 2 m hairpin starting geometry

The 8.500 in #12 solid-copper part is an initial tuning blank.

Starting geometry:

- Strip the entire blank to bare copper without nicking it.
- Form one symmetric U in the 2 m element plane.
- Set the two straight legs parallel.
- Set the leg spacing equal to the measured 2 m feed-node center spacing.
- Use one smooth 180-degree bottom bend with no kink.
- Keep the two legs equal in finished length.
- Orient the U away from the 70 cm boom and away from the rearward coax route.
- Maintain at least 0.500 in clearance from unintended conductors where the actual assembly permits.
- Do not trim the blank before the initial calibrated O8 measurement.

Record node spacing, leg spacing, straight-leg length, bottom-bend diameter, installed orientation, and any later equal trim. Hairpin dimensions after tuning are as-tuned data, not silent changes to this initial cut sheet.

---

## 11. Boom retention - no joint mechanism

At J1 and J2:

1. Place one nonconductive pad between the two bare PVC surfaces.
2. Align the pad long axis with the boom axes.
3. Set the boom-center line 45 degrees +/- 5 degrees between the element planes.
4. Wrap one 8 in minimum UV-resistant cable tie around both booms and the pad.
5. Tighten only enough to prevent axial slip and loss of the 90-degree plane relationship.
6. Confirm the pad remains centered and the installed bare-surface gap is at least 0.250 in.
7. Confirm the PVC is not flattened or visibly indented.
8. Trim the tie tail flush and orient the locking head away from the operator's hand and coax.

After both ties are installed:

- Pull each boom axially by hand; neither may slip.
- Apply gentle opposite twisting; the 90-degree relationship must remain fixed.
- Verify all cross-boom clearances, including the 2 m supports and the reflector pair.
- Verify the coax can route rearward without entering either tie or pad interface.

Do not add a tee, crossbar, pivot bolt, hinge, metal clamp, wood block, or permanent adhesive joint.

---

## 12. Ferrites and coax routing

The Rev. A air-wound coax coils are deleted.

| Feed | Initial ferrite configuration | Location |
|---|---|---|
| 2 m | Four snap-on Fair-Rite 31-material parts, baseline 0431164281 or verified equivalent | Immediately after the feedpoint, before the rearward cable run |
| 70 cm | Four snap-on Fair-Rite 61-material parts, baseline 0461164281 or verified equivalent | Immediately after the feedpoint, before the rearward cable run |

Routing requirements:

- Confirm ferrite fit on the measured RG-58 jacket before removing a connector.
- Route each cable from its node pair toward the REAR/operator end.
- Keep the intact jacket close to the feedpoint and strain-relieve it before the ferrite group.
- Obey the cable manufacturer's minimum bend radius; do not wrap the cable tightly around either boom.
- Keep coax and ferrites clear of radiating-element tips, J1, J2, the hairpin, and the other feedpoint.
- Use small approximately 4 in ties only for local strain relief or ferrite retention, never around both booms.
- Keep enough free cable at the rear for normal handheld movement without loading the feedpoint.
- Label the free BNC ends `2 m` and `70 cm`.

Final ferrite count and position are validated during O8 coax-movement testing.

---

## 13. Fabrication tolerances and clearance controls

### 13.1 Cut and station tolerances

| Feature | Controlled tolerance |
|---|---:|
| 2 m passive element finished length | +/- 0.0625 in |
| 2 m driven half finished length | +/- 0.03125 in; half-to-half mismatch no more than 0.03125 in |
| 70 cm passive element finished length | +/- 0.03125 in |
| 70 cm driven half finished length | +/- 0.0156 in; half-to-half mismatch no more than 0.0156 in |
| 2 m boom station from FRONT | +/- 0.0625 in |
| 70 cm boom station from FRONT | +/- 0.03125 in |
| Driven-element steel-tip center gap | 0.250 in +/- 0.0156 in |
| Element centering on 2 m boom | +/- 0.0625 in |
| Element centering on 70 cm boom | +/- 0.03125 in |
| Relative element-plane angle | 90 degrees +/- 2 degrees |
| Installed bare-surface boom gap | 0.250 in minimum |

### 13.2 Close reflector pair

With the boom FRONT ends aligned, the 70-R center at 21.000 in and 2M-R center at 21.500 in must have:

- Relative longitudinal center separation: **0.500 in +/- 0.03125 in**.
- Measured physical edge clearance in the assembled antenna: **0.0625 in minimum**.

If the tape curvature, width, or mounting angle violates the physical-clearance requirement, stop and document the interference. Do not bend, notch, or shorten an RF element to create clearance without an engineering revision.

---

## 14. Inspection and hold points

### Hold Point A - material acceptance

- [ ] PVC OD, tape width/thickness, support diameter, coax diameter, and pad thickness recorded.
- [ ] Tape steel is conductive and approximately 3/8 in wide.
- [ ] Both 30.000 in boom blanks are straight and undamaged.
- [ ] At least 18 ft of usable tape steel is available.

### Hold Point B - coupon approval

- [ ] Shared 2 m tape/support hole fit passes.
- [ ] 70 cm tape-only hole fit passes.
- [ ] #6 clearance hole and hardware stack pass.
- [ ] Selected screw length provides at least two full threads beyond the nut.

### Hold Point C - after cutting

- [ ] Every part is labeled.
- [ ] Every finished length is measured and recorded.
- [ ] No element is short, kinked, cracked, or left with a sharp burr.
- [ ] Driven halves are matched within the controlled difference.

### Hold Point D - after boom drilling

- [ ] Every station is checked from the FRONT datum.
- [ ] Rear-datum conversion is checked independently.
- [ ] Holes are square, coplanar, deburred, and free of cracks.
- [ ] Close-reflector relative location passes.

### Hold Point E - after mechanical assembly

- [ ] Booms are parallel and FRONT ends are aligned.
- [ ] Element planes are 90 degrees +/- 2 degrees.
- [ ] Boom-center line is 45 degrees +/- 5 degrees from both element planes.
- [ ] Both pads retain at least 0.250 in installed gap.
- [ ] Neither boom slips axially or rotates under gentle hand load.
- [ ] Clearance from either boom to components carried by the other boom is at least 0.125 in.
- [ ] Reflector edge clearance is at least 0.0625 in.
- [ ] Feed hardware cannot bridge a driven-element gap.

### Hold Point F - DC checks before hairpin

Disconnect both cables from radios, diplexers, and analyzers.

| Test | Expected result |
|---|---|
| 2 m BNC pin to assigned driven half | Continuity |
| 2 m BNC shell to assigned driven half | Continuity |
| 2 m BNC pin to shell, one hairpin end disconnected | Open |
| 70 cm BNC pin to assigned driven half | Continuity |
| 70 cm BNC shell to assigned driven half | Continuity |
| 70 cm BNC pin to shell | Open |
| Either feed conductor to any parasitic element | Open |
| 2 m feed to 70 cm feed, all equipment detached | Open |

### Hold Point G - DC checks after hairpin

| Test | Expected result |
|---|---|
| 2 m BNC pin to shell | Continuity through the intended hairpin |
| 70 cm BNC pin to shell | Open |
| Either feed conductor to any parasitic element | Open |
| 2 m feed to 70 cm feed, all equipment detached | Open |

Do not transmit until O8 calibrated impedance and SWR testing passes the required operating frequencies.

---

## 15. As-built dimensional record

Complete this table before RF tuning.

| Item | Design value | As-built value | Pass / deviation |
|---|---:|---:|---|
| PVC-2M length | 30.000 in |  |  |
| PVC-70 length | 30.000 in |  |  |
| PVC actual OD | Record |  |  |
| Tape width / thickness | Record |  |  |
| 2M-D1 length / station | 35.400 / 2.000 in |  |  |
| 2M-DE-L length | 18.575 in |  |  |
| 2M-DE-R length | 18.575 in |  |  |
| 2M-DE gap / station | 0.250 / 13.500 in |  |  |
| 2M-R length / station | 41.400 / 21.500 in |  |  |
| 70-D3 length / station | 11.700 / 3.500 in |  |  |
| 70-D2 length / station | 11.900 / 9.500 in |  |  |
| 70-D1 length / station | 11.900 / 15.500 in |  |  |
| 70-DE-L length | 6.175 in |  |  |
| 70-DE-R length | 6.175 in |  |  |
| 70-DE gap / station | 0.250 / 18.500 in |  |  |
| 70-R length / station | 12.900 / 21.000 in |  |  |
| 2 m node-center spacing | Record |  |  |
| 70 cm node-center spacing | Record |  |  |
| Hairpin leg spacing / leg length / bend diameter | Record |  |  |
| Installed boom gap at J1 / J2 | 0.250 in minimum |  |  |
| Element-plane angle | 90 degrees +/- 2 degrees |  |  |
| Reflector physical edge clearance | 0.0625 in minimum |  |  |

Any out-of-tolerance result is an as-built deviation requiring evaluation before O8. Do not silently change a design value to match the fabricated part.

---

## 16. Stop conditions

Stop fabrication for any of the following:

- A short-cut RF element.
- A misplaced element station.
- Cracked, split, or crushed PVC.
- A failed tape/support coupon.
- A driven gap that will not remain fixed.
- Feed hardware that can contact the opposite node.
- Boom, dowel, element, ferrite, hairpin, or coax interference.
- Less than the required installed boom or reflector clearance.
- A coax bend tighter than its documented minimum.
- Unexpected DC continuity or failed intended continuity.
- A material substitution that changes element width, boom OD, feedline type, support material, or RF geometry.

---

## 17. Revision control

| Revision | Date | Description |
|---|---|---|
| Rev. A | 2026-08-17 | Initial mechanical drawing and cut sheet. |
| **Rev. B** | **2026-09-21** | Retained verified RF geometry; standardized project name; removed rotating/folding joint language and coax coils; added fixed removable boom retention, separator pads, ferrites, coupon controls, feed-node geometry, corrected DC checks, tighter clearances, and as-built records. |

The 2026-09-15 boom-retention drawing was an unreleased draft and did not consume the Rev. B repository revision identifier.

---

## 18. Engineering intent

This Rev. B cut sheet makes the verified dimensional baseline buildable without relying on the conflicting joint and choke assumptions in the earlier drawings.

It does not claim measured resonance, impedance, gain, pattern, isolation, or common-mode suppression. Those properties must be established on the completed as-built antenna through O8 and later field testing.

Baseline RF geometry is derived from the project design set based on John Portune, W6NBC, QST, January 2012, pages 37-39. Project-specific boom retention, feed hardware, ferrite suppression, tolerances, and inspection controls are TM-YAGI-01 Rev. B engineering changes.

---

**End of O5 Rev. B Mechanical Drawing and Cut Sheet**
