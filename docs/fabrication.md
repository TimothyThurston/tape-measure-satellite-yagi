# O6 - Fabrication and Assembly

## Tape Measure Satellite Yagi

**Project:** Tape Measure Satellite Yagi  
**Project ID:** TM-YAGI-01  
**Document:** O6 Fabrication and Assembly Procedure  
**Repository path:** `docs/fabrication.md`  
**Application:** Handheld amateur-radio satellite and ISS operation  
**Bands:** 2 m / 70 cm  
**Revision:** Rev. B  
**Date:** 2026-09-21  
**Status:** Controlled mechanical fabrication procedure  

---

## 1. Purpose and scope

This document converts the controlled O3 through O5 Revision B baseline into a safe, repeatable mechanical build process for the Tape Measure Satellite Yagi.

O6 controls:

- Incoming-material inspection and measurement.
- Mandatory scrap-coupon testing.
- PVC boom cutting, marking, and drilling.
- Tape-steel and support cutting.
- Element labeling, installation, centering, and retention.
- Driven-element gap setup.
- Feed-node hole marking and drilling in the tape steel.
- Separator-pad and dual-boom retention assembly.
- Mechanical clearances and handling checks.
- Pre-feed DC isolation checks.
- As-built dimensional recording.
- Fabrication photographs and deviation records.

O6 does **not**:

- Remove either antenna-side BNC connector.
- Strip or terminate RG-58.
- Crimp or solder feed lugs.
- Install the 2 m hairpin.
- Install or finalize ferrite common-mode suppression.
- Apply final heat shrink or weatherproofing.
- Perform VNA measurements or RF tuning.
- Transmit through the antenna.

Those operations belong to O7 and O8.

---

## 2. Revision B audit disposition

### 2.1 Retained from the later Rev. A fabrication draft

| Item | Disposition |
|---|---|
| O6 mechanical / O7 electrical phase boundary | Retained |
| Two 30.000 in PVC booms | Retained |
| FRONT-datum station layout | Retained |
| Verified RF element lengths | Retained |
| 7/16 in baseline element holes | Retained subject to the full coupon test |
| Three 12.000 in nonconductive 2 m supports | Retained and made final, not trimmable by default |
| As-designed / as-built / as-tuned configuration control | Retained |
| Build photographs and deviation log | Retained and expanded |

### 2.2 Corrected in Revision B

| Rev. A fabrication issue | Revision B correction |
|---|---|
| Rotating collar and folding instructions | Removed. The booms are fixed in operating orientation while tied and are separated for storage. |
| Six-inch dual-boom ties allowed | Removed. Use 8 in minimum UV-resistant ties. |
| Touching booms | Removed. Use two nonconductive separator pads with at least 0.250 in installed clearance. |
| J1/J2 called joints | Renamed retention stations. No separate joint mechanism exists. |
| Practice hole tested only the tape | Replaced by a complete tape/support/PVC and feed-hardware coupon. |
| Feed screws drilled through the PVC wall | Prohibited. Feed-node holes are drilled only through the exposed driven-half tape steel. |
| Supports could be shortened | Removed. All three controlled supports remain 12.000 in unless a documented revision approves a change. |
| Loose centering and station controls | Replaced by O5 Rev. B tolerances and the close-reflector check. |
| Feed work and coax coils appeared in the older combined draft | Excluded from O6. O7 uses snap-on ferrites instead of tight coils. |
| Contact surfaces could be tinned under hardware | Prohibited. Mechanical clamp surfaces remain untinned. |
| Relative boom rotation treated as normal handling | Prohibited while ties are installed. Roll the complete antenna during operation. |
| Incomplete mechanical DC checks | Added driven-half, parasitic-element, and cross-band isolation checks before O7. |

---

## 3. Controlling inputs

Do not begin O6 unless these documents are available and mutually consistent:

| Document | Required revision | Function |
|---|---|---|
| O3 - Antenna Design and Dimensions | Rev. B | Architecture and design intent |
| O4 - Bill of Materials and Sourcing | Rev. B | Controlled materials and substitutions |
| O5 - Mechanical Drawing and Cut Sheet | Rev. B | Exact cuts, stations, tolerances, coupon, and clearances |
| O6 - Fabrication and Assembly | Rev. B | Mechanical build sequence |

If a value in this procedure conflicts with O5 Rev. B, stop and reconcile the documents before cutting or drilling. Do not choose whichever value is easier to fabricate.

---

## 4. Configuration control

Maintain three distinct records:

### 4.1 As-designed

The controlled O3-O7 values before fabrication.

### 4.2 As-built

The actual measured dimensions, materials, fit, gaps, clearances, feed-node spacing, and retention geometry after O6/O7 construction and before RF tuning.

### 4.3 As-tuned

The final configuration after O8 measurement and adjustment.

Never overwrite an as-designed value with a fabricated or tuned value. Record deviations separately.

---

## 5. Required O6 materials

Use only O4-approved materials.

| Item | O6 use |
|---|---|
| Nominal 1/2 in Schedule 40 PVC | Two 30.000 in booms plus scrap coupon |
| Approximately 3/8 in conductive tape steel | RF elements plus coupon |
| 3/8 in x 12.000 in nonconductive supports | Three 2 m element supports plus one spare for coupon |
| Approximately 4 in nonconductive cable ties | Element/support retention and temporary positioning |
| 8 in minimum UV-resistant black cable ties | Two installed dual-boom retention ties plus spares |
| Two nonconductive separator pads | Installed at J1 and J2 |
| #6-32 screws, nuts, and flat washers | Coupon and feed-node hole fit verification |
| One representative #4-6 ring lug | Coupon stack verification only |
| Fine abrasive | Local feed-node contact-pad preparation after drilling |
| Temporary nonconductive 0.250 in gap gauge | Driven-element gap setup |
| Labels or masking tape and marker | Part identification |

RG-58, final ring lugs, the hairpin blank, ferrites, solder, heat shrink, and electrical finishing materials are controlled by O4 but are installed during O7.

---

## 6. Required tools

Minimum tools:

- Safety glasses.
- Cut-resistant work gloves for handling spring steel.
- Steel rule or measuring tape with at least 1/32 in graduations where controlled.
- Caliper capable of reading PVC, tape, support, pad, screw, and coax dimensions.
- Fine-point permanent marker.
- Square.
- V-block, drill guide, or equivalent round-pipe fixture.
- Drill or drill press.
- 7/16 in drill bit.
- Candidate approximately 5/32 in #6 clearance bit.
- PVC cutter, fine-tooth saw, or hacksaw.
- Snips rated for the tape steel.
- Fine file and deburring tools.
- Padded vise or clamps.
- Multimeter.
- Camera or phone for fabrication records.

Recommended:

- Sacrificial wood drilling block.
- Low-tack tape for temporary marking and gap retention.
- Printed or fabricated 45-degree assembly-angle template.
- Small machinist square.

---

## 7. Safety controls

### 7.1 Spring-steel tape

- Wear eye protection and gloves while cutting and deburring.
- Control both sides of the cut; the blade can spring or whip.
- Deburr each piece immediately.
- Do not leave unlabeled sharp offcuts on the bench.

### 7.2 Drilling

- Do not hand-hold PVC, tape steel, or the coupon while drilling.
- Use a V-block or equivalent fixture for round pipe.
- Clamp tape steel flat to a sacrificial block before drilling node holes.
- Keep hands away from the bit and from the possible snag direction.
- Stop if the tape catches, twists, cracks, or kinks.

### 7.3 PVC

- Do not crush the pipe in the vise.
- Stop for visible cracks, splits, or severe whitening around a hole.
- Remove chips and burrs before inserting elements.

### 7.4 Electrical and RF safety

- Keep radios, transmitters, and analyzers disconnected during O6.
- O6 multimeter checks are performed only on the unpowered structure.
- Do not transmit before O8 acceptance testing.

---

## 8. Fabrication record header

Complete before cutting:

| Field | Entry |
|---|---|
| Builder |  |
| Build date |  |
| O3 revision | Rev. B |
| O4 revision | Rev. B |
| O5 revision | Rev. B |
| O6 revision | Rev. B |
| PVC manufacturer / marking |  |
| Tape manufacturer / blade model |  |
| Support material |  |
| Hardware source |  |
| Deviations open at start |  |

---

## 9. Step 1 - Inspect and measure incoming materials

### 9.1 PVC

Verify and record:

- Correct nominal 1/2 in Schedule 40 material.
- At least 60 in usable length plus a coupon section.
- Actual outside diameter.
- Straightness and surface condition.
- No cracks, crushing, or major bends.

### 9.2 Tape steel

Verify and record:

- Conductive spring-steel base material.
- Actual width and thickness.
- Blade curvature and coating.
- At least 18 ft usable length.
- No severe kinks, cracks, or corrosion in the selected sections.

Reject a 1 in or wider blade unless O3-O5 are formally revised.

### 9.3 Supports

Verify and record:

- Nonconductive material.
- Actual diameter.
- Straightness.
- At least three 12.000 in pieces plus one coupon piece.

### 9.4 Retention materials

Verify:

- At least two 8 in minimum UV-resistant ties plus spares.
- Two nonconductive pads approximately 1.000 x 0.500 in.
- Each installed pad thickness will remain at least 0.250 in.
- Small ties are available for all element-retention stations.

### 9.5 Feed hardware for coupon

Verify:

- Actual #6-32 screw fits the nut.
- Flat washer and representative ring lug fit the screw.
- Both 1/2 in and 3/4 in candidate screw lengths are available.
- Candidate drill bit provides a free but not excessive clearance fit.

---

## 10. Quality Gate A - material acceptance

- [ ] PVC OD measured and recorded.
- [ ] Tape width, thickness, curvature, coating, and conductivity recorded.
- [ ] Support diameter measured and recorded.
- [ ] At least 18 ft usable tape steel accepted.
- [ ] Three final supports plus one coupon support available.
- [ ] Separator pads and 8 in minimum ties accepted.
- [ ] Candidate #6-32 hardware stack available.

Stop if any controlled material differs from O4/O5 without an approved substitution.

---

## 11. Step 2 - Build and approve the material coupon

Use the actual project materials. Do not substitute easier scrap of a different size.

### 11.1 PVC/tape/support fit

1. Secure a short scrap section of the actual PVC in the drilling fixture.
2. Drill one 7/16 in through-hole through the pipe centerline.
3. Deburr without enlarging the hole.
4. Test the actual 3/8 in support and actual tape together through the hole.
5. Test the tape alone through the same size hole for the 70 cm condition.
6. Inspect the tape for crushing, permanent kinking, or forced distortion.
7. Inspect the PVC for cracking and uncontrolled looseness.

### 11.2 Feed-node hardware fit

1. Clamp a tape coupon flat to sacrificial wood.
2. Center the candidate feed-node hole across the blade width.
3. Drill with the candidate approximately 5/32 in bit.
4. Deburr both faces.
5. Assemble this representative stack from screw head toward nut:
   1. #6-32 screw.
   2. Bare tape coupon.
   3. Representative ring lug.
   4. Representative #12 wire hook or equal-thickness gauge for the 2 m stack.
   5. Flat washer.
   6. Nut.
6. Begin with the 1/2 in screw.
7. Confirm the nut fully engages and at least two complete threads are visible.
8. Use the 3/4 in screw only if the 1/2 in screw fails engagement.
9. Confirm the stack clamps without bending or tearing the tape.

Do not tin the tape coupon beneath the mechanical stack.

### 11.3 Separator-pad fit

1. Place a pad between two scrap or uncut sections of the actual PVC.
2. Wrap one 8 in tie around both pipes and the pad.
3. Tighten only enough to prevent sliding.
4. Confirm the pad remains centered.
5. Measure the installed bare-surface gap.
6. Reject a pad that compresses below 0.250 in, slips uncontrollably, cracks, or permanently deforms.

---

## 12. Quality Gate B - coupon approval

- [ ] 7/16 in hole drilled cleanly without PVC damage.
- [ ] Actual tape and support share the 2 m hole without forced distortion.
- [ ] Actual tape fits the 70 cm condition without uncontrolled looseness.
- [ ] Candidate #6 clearance hole fits the actual screw.
- [ ] Shortest usable screw identified.
- [ ] Node stack clamps securely with at least two full threads beyond the nut.
- [ ] Separator pad retains at least 0.250 in installed gap.

If any item fails, stop. Do not enlarge all final holes or improvise a joint.

---

## 13. Step 3 - Cut the PVC booms

Cut:

| Boom ID | Band | Finished length |
|---|---|---:|
| PVC-2M | 2 m | 30.000 in |
| PVC-70 | 70 cm | 30.000 in |

For each boom:

1. Make a square cut.
2. Deburr inside and outside.
3. Measure the finished length.
4. Reject or recut if shorter than the O5 tolerance permits.
5. Select and mark the FRONT end.
6. Mark the REAR/operator end.
7. Mark the band ID.
8. Add a permanent direction-of-gain arrow pointing toward FRONT.

Do not cut either boom into folding sections. Do not install the purchased PVC tee.

---

## 14. Step 4 - Establish reference lines

On each boom:

1. Draw one straight longitudinal element-plane reference line.
2. Transfer the line across each planned station using a square.
3. Mark a separate assembly-orientation line 45 degrees around the pipe from the element-plane line for use when setting the boom-center relationship.
4. Keep all labels clear of drilling points.

Do not rely on visual estimation alone.

---

## 15. Step 5 - Lay out element and retention stations

Measure every station independently from FRONT. Do not chain dimensions.

### 15.1 2 m boom

| Station | X from FRONT | Purpose |
|---|---:|---|
| 2M-D1 | 2.000 in | Director 1 |
| J1 | 4.500 in | Front retention station; no hole |
| 2M-DE | 13.500 in | Driven element |
| 2M-R | 21.500 in | Reflector |
| J2 | 22.500 in | Rear retention station; no hole |

### 15.2 70 cm boom

| Station | X from FRONT | Purpose |
|---|---:|---|
| 70-D3 | 3.500 in | Director 3 |
| J1 | 4.500 in | Front retention station; no hole |
| 70-D2 | 9.500 in | Director 2 |
| 70-D1 | 15.500 in | Director 1 |
| 70-DE | 18.500 in | Driven element |
| 70-R | 21.000 in | Reflector |
| J2 | 22.500 in | Rear retention station; no hole |

### 15.3 Independent checks

- Confirm every rear-datum value using `30.000 - X from FRONT`.
- Align both FRONT ends and verify the nominal 2M-R to 70-R center difference is 0.500 in.
- Confirm no retention station overlaps an RF station.

---

## 16. Quality Gate C - layout verification

- [ ] Both boom lengths recorded.
- [ ] FRONT, REAR, band ID, and gain arrows present.
- [ ] Longitudinal element-plane references present.
- [ ] Assembly-orientation references present.
- [ ] All element stations measured independently from FRONT.
- [ ] Rear-datum cross-checks completed.
- [ ] J1 and J2 marked as no-hole retention stations.
- [ ] Nominal reflector-center separation confirmed at 0.500 in.

Have a second person remeasure the station marks where practical. If working alone, remeasure after a short break using a different rule orientation.

---

## 17. Step 6 - Drill the element holes

Use the approved 7/16 in coupon result.

1. Place the boom in a V-block or equivalent fixture.
2. Align the element-plane reference.
3. Drill through the pipe centerline at each RF station only.
4. Keep the bit perpendicular to the boom axis.
5. Deburr inside and outside without enlarging the hole.
6. Inspect after every hole for cracking, splitting, whitening, and wander.

Drill:

| Boom | Hole locations from FRONT |
|---|---|
| 2 m | 2.000, 13.500, 21.500 in |
| 70 cm | 3.500, 9.500, 15.500, 18.500, 21.000 in |

Do not drill at J1 or J2. Do not drill feed-node holes through the PVC.

---

## 18. Quality Gate D - boom inspection

- [ ] Three element holes on the 2 m boom.
- [ ] Five element holes on the 70 cm boom.
- [ ] No holes at J1 or J2.
- [ ] Hole axes are parallel within each boom.
- [ ] Stations remain within the O5 tolerance.
- [ ] No cracks, splits, crushing, or severe whitening.
- [ ] Holes are deburred without excessive enlargement.
- [ ] Actual tape/support fit remains consistent with the coupon.

Replace a badly drilled boom rather than moving an RF element to compensate.

---

## 19. Step 7 - Cut, deburr, and label RF elements

Cut every finished length from the actual tape steel. Label immediately.

### 19.1 2 m cuts

| ID | Element | Finished length |
|---|---|---:|
| 2M-R | Reflector | 41.400 in |
| 2M-DE-L | Driven left half | 18.575 in |
| 2M-DE-R | Driven right half | 18.575 in |
| 2M-D1 | Director 1 | 35.400 in |

### 19.2 70 cm cuts

| ID | Element | Finished length |
|---|---|---:|
| 70-R | Reflector | 12.900 in |
| 70-DE-L | Driven left half | 6.175 in |
| 70-DE-R | Driven right half | 6.175 in |
| 70-D1 | Director 1 | 11.900 in |
| 70-D2 | Director 2 | 11.900 in |
| 70-D3 | Director 3 | 11.700 in |

### 19.3 Finish requirements

For every piece:

1. Control spring-back while cutting.
2. Deburr both ends.
3. Round sharp corners without shortening beyond tolerance.
4. Measure the finished length after deburring.
5. Label the ID and intended left/right orientation where applicable.
6. Record the actual length.

Do not trim any element for RF tuning during O6.

Net tape steel in the finished elements is 174.700 in.

---

## 20. Step 8 - Prepare the 2 m supports

Use three separate nonconductive pieces:

| ID | Station | Finished length |
|---|---|---:|
| ST-1 | 2M-D1 | 12.000 in |
| ST-2 | 2M-DE | 12.000 in |
| ST-3 | 2M-R | 12.000 in |

1. Verify each support is straight and nonconductive.
2. Deburr or sand sharp ends.
3. Mark the center at 6.000 in.
4. Label the assigned station.
5. Do not shorten a support for convenience, folding, or storage.

If a 12.000 in support creates a verified interference, stop and document it for engineering review.

---

## 21. Quality Gate E - cut-part verification

- [ ] All ten tape pieces present and labeled.
- [ ] All tape lengths pass O5 tolerance.
- [ ] Driven halves match within the controlled difference.
- [ ] All exposed tape edges are deburred.
- [ ] Three supports measure 12.000 in and are labeled.
- [ ] No part is kinked, cracked, or short.
- [ ] Net tape schedule reconciles to 174.700 in.

Do not use an accidentally short element. Cut a replacement.

---

## 22. Step 9 - Dry-fit passive elements

### 22.1 2 m passive elements

At 2M-D1 and 2M-R:

1. Place the assigned 12.000 in support alongside the tape.
2. Pass the validated tape/support pair through the 7/16 in hole.
3. Align the support center mark with the boom centerline.
4. Center the conductive tape left-to-right within 1/16 in.
5. Keep the tape and support straight through the boom cross-section.
6. Do not permanently retain yet.

### 22.2 70 cm passive elements

At 70-D3, 70-D2, 70-D1, and 70-R:

1. Pass the tape through the assigned 7/16 in hole.
2. Center the tape left-to-right within 1/32 in.
3. Confirm the element ID and physical order.
4. Keep all four element axes parallel.
5. Do not permanently retain yet.

---

## 23. Step 10 - Fit the driven elements

### 23.1 2 m driven element

1. Place ST-2 through the 2M-DE station using the validated tape/support arrangement.
2. Insert 2M-DE-L and 2M-DE-R from opposite sides.
3. Place a 0.250 in nonconductive gauge between the physical inner steel ends.
4. Set the overall tip-to-tip span to 37.400 in.
5. Match left/right projection about the boom centerline.
6. Keep both halves collinear.
7. Apply temporary nonconductive retention so the gap cannot close.

### 23.2 70 cm driven element

1. Insert 70-DE-L and 70-DE-R from opposite sides.
2. Place a 0.250 in nonconductive gauge between the physical inner steel ends.
3. Set the overall tip-to-tip span to 12.600 in.
4. Match left/right projection about the boom centerline.
5. Keep both halves collinear.
6. Apply temporary nonconductive retention so the gap cannot close.

The steel-tip gap is not the feed-node screw spacing.

---

## 24. Step 11 - Install nonconductive element retention

Use small approximately 4 in cable ties. Keep every locking head away from the intended feed-node hardware and operator contact areas.

### 24.1 2 m stations

At each 2 m station:

1. Install one small station tie around the PVC in the element cross-section so it gently captures the tape/support pair at both hole exits.
2. Tighten only enough to prevent lateral sliding; do not flatten the tape, crush the support, or indent the PVC.
3. Add one small tie around the tape and support near each support end, approximately 0.750 in inboard from the support tip.
4. Confirm the conductive tape remains centered and straight.
5. Confirm the driven gap remains controlled at 2M-DE.

### 24.2 70 cm stations

At each 70 cm station:

1. Install one small station tie around the PVC in the element cross-section so it gently captures the tape at both hole exits.
2. Tighten only enough to prevent lateral sliding without flattening, creasing, or twisting the blade.
3. Place the locking head away from the feed-node location at 70-DE.
4. Recheck centering and parallelism.

If this retention method cannot hold the actual blade securely without distortion, stop. Do not add metal fasteners or adhesive without revising O4-O6.

---

## 25. Step 12 - Mark and drill the feed-node holes

Perform this step only after both driven gaps, overall spans, and temporary retention pass inspection.

For each of the four driven halves:

1. Mark one hole center across the middle of the approximately 3/8 in blade width.
2. Place the center 0.250 in +/- 0.062 in outboard of the adjacent PVC surface.
3. Mirror the left and right hole locations.
4. Confirm the screw and washer envelope will remain clear of the opposite half, other boom, hairpin route, and station tie.
5. Mark the selected point clearly.
6. Remove one driven half at a time while preserving all reference marks.
7. Clamp the tape flat to sacrificial wood.
8. Drill the approved approximately 5/32 in clearance hole through the tape only.
9. Deburr both faces without removing excessive material.
10. Prepare a small bare-metal contact pad around the hole using fine abrasive.
11. Do not tin the contact pad.
12. Reinstall the half, reset the gap and overall span, and repeat for the next half.

After all four holes are complete:

- Install the selected bare #6-32 screws, washers, and nuts temporarily for mechanical fit only.
- Do not install ring lugs or the hairpin during O6.
- Confirm at least two complete threads are visible beyond each nut.
- Confirm each screw contacts only its assigned driven half.
- Record the 2 m and 70 cm node-center spacing.
- Remove and bag the temporary hardware by band if O7 will perform the final stack assembly.

Do not drill the PVC wall for feed-node hardware.

---

## 26. Quality Gate F - element and feed-node geometry

- [ ] Every element is in the correct station and order.
- [ ] 2 m passive elements are centered within 1/16 in.
- [ ] 70 cm passive elements are centered within 1/32 in.
- [ ] Driven halves remain matched and collinear.
- [ ] 2 m gap is 0.250 in +/- 0.0156 in.
- [ ] 70 cm gap is 0.250 in +/- 0.0156 in.
- [ ] 2 m overall driven span is 37.400 in within tolerance.
- [ ] 70 cm overall driven span is 12.600 in within tolerance.
- [ ] Feed-node holes are in tape only, centered across blade width, and deburred.
- [ ] No contact pad is tinned.
- [ ] Temporary screw fit passes with at least two threads beyond each nut.
- [ ] No feed screw can bridge the driven-element gap.
- [ ] 2 m and 70 cm node-center spacings are recorded.

---

## 27. Step 13 - Assemble the two booms in operating orientation

There is no separate boom-joint mechanism.

1. Lay both booms FRONT-to-FRONT and REAR-to-REAR.
2. Keep the longitudinal centerlines parallel.
3. Set the two element planes to 90 degrees +/- 2 degrees.
4. Use the orientation references to set the line between boom centers to 45 degrees +/- 5 degrees from either element plane.
5. At J1, place PAD-1 between the bare PVC surfaces with its 1.000 in long axis parallel to the booms.
6. Center one 8 in minimum UV-resistant tie over J1 and PAD-1.
7. Tighten only enough to retain the booms without axial slip or PVC indentation.
8. Repeat at J2 using PAD-2 and a new 8 in minimum tie.
9. Confirm each pad remains centered and produces at least 0.250 in installed bare-surface clearance.
10. Orient each tie head away from the operator's hand, coax route, and RF elements.
11. Trim tie tails flush only after all geometry passes.

Do not use a 4 in or 6 in tie around both booms. Do not add a tee, hinge, pivot, crossbar, metal clamp, wood block, bolt, or adhesive joint.

The booms must not rotate relative to each other while retained. For storage, cut both retention ties and separate the booms. Use new ties for reassembly.

---

## 28. Step 14 - Verify retention and clearances

With the antenna mechanically assembled:

1. Pull each boom axially by hand; neither may slip.
2. Apply a gentle opposite twist; the 90-degree relationship must remain fixed.
3. Confirm neither PVC surface is flattened or visibly indented.
4. Measure and record the J1 and J2 installed gaps.
5. Measure and record the element-plane angle.
6. Confirm the center-to-center line remains approximately 45 degrees from both element planes.
7. Confirm at least 0.125 in clearance from either boom to components carried by the other boom.
8. Confirm the 2 m supports clear the 70 cm boom.
9. Confirm all feed-node screw envelopes clear the other boom and array.
10. Confirm J1/J2 pads and ties do not touch any RF element.
11. Confirm the rear handle region remains usable.

### Close-reflector check

With FRONT ends aligned:

- 70-R center is 21.000 in.
- 2M-R center is 21.500 in.
- Relative center separation must be 0.500 in +/- 0.03125 in.
- Measured physical edge clearance must be at least 0.0625 in.

Do not bend, notch, offset, or shorten a reflector to create clearance.

---

## 29. Quality Gate G - completed mechanical assembly

- [ ] FRONT ends aligned and gain arrows agree.
- [ ] Boom centerlines parallel.
- [ ] Element planes 90 degrees +/- 2 degrees.
- [ ] Boom-center line 45 degrees +/- 5 degrees from both element planes.
- [ ] J1 and J2 use 8 in minimum UV-resistant ties.
- [ ] One approved separator pad installed at each retention station.
- [ ] Installed boom gap at least 0.250 in at J1 and J2.
- [ ] No axial slip under hand load.
- [ ] No relative rotation under gentle hand load.
- [ ] No crushed or indented PVC.
- [ ] Each boom clears components on the other boom by at least 0.125 in.
- [ ] Reflector physical edge clearance at least 0.0625 in.
- [ ] No tie or pad contacts an RF element.
- [ ] Antenna separates for storage only by cutting the retention ties.

---

## 30. Step 15 - Perform pre-feed multimeter checks

Keep all radios, coax cables, analyzers, and other equipment disconnected.

Use clean exposed cut ends or the prepared node contact pads for probe contact. Do not remove unnecessary coating.

| Test | Expected result |
|---|---|
| Each passive element end-to-end | Continuity |
| Each individual driven half end-to-node pad | Continuity |
| 2M-DE-L to 2M-DE-R before hairpin | Open |
| 70-DE-L to 70-DE-R | Open |
| Either driven half to any parasitic element on its band | Open |
| Any 2 m element to any 70 cm element | Open |
| Any element to an unassigned metal screw | Open or not applicable; no loose screws permitted |

An unexpected continuity result requires inspection for metal debris, a closed driven gap, a misplaced screw, or unintended element contact.

O7 repeats cable-specific checks before and after the hairpin is connected.

---

## 31. Step 16 - Record the as-built mechanical configuration

Complete the O5 as-built table before removing the retention ties or beginning O7.

At minimum record:

### Booms and materials

- Both finished boom lengths.
- Actual PVC OD.
- Tape width and thickness.
- Support diameter and finished lengths.
- Separator material and installed thickness.

### Every RF element

- Actual finished length.
- Actual FRONT-datum station.
- Centering or left/right projection.
- Element ID and orientation.

### Driven elements

- Both half lengths.
- Overall span.
- Steel-tip center gap.
- Feed-node center spacing.
- Feed-node hole diameter.

### Assembly

- J1 and J2 positions.
- J1 and J2 installed boom gaps.
- Element-plane angle.
- Boom-center-line angle.
- Close-reflector center separation and physical edge clearance.
- Minimum observed cross-boom component clearance.

Leave hairpin geometry, ferrite position, coax routing, cable termination, and RF measurements blank for O7/O8.

---

## 32. Step 17 - Photograph the O6 build

Minimum photographs:

1. Material identification and measured dimensions.
2. Approved tape/support/PVC coupon.
3. Approved feed-node stack coupon.
4. Approved separator-pad coupon.
5. Both cut 30.000 in booms.
6. All layout marks before drilling.
7. Each drilled boom before element installation.
8. All labeled 2 m cut parts beside a rule.
9. All labeled 70 cm cut parts beside a rule.
10. Each 2 m tape/support cross-section and retention method.
11. 2 m driven gap and node-hole locations.
12. 70 cm driven gap and node-hole locations.
13. J1 separator and tie.
14. J2 separator and tie.
15. End view showing the 90-degree planes and 45-degree boom-center line.
16. Close-reflector clearance with a scale or feeler reference.
17. Completed mechanical assembly from FRONT and REAR.
18. All completed O6 inspection and as-built records.

Suggested repository structure:

```text
photos/
└── fabrication/
    ├── materials-and-coupons/
    ├── boom-layout-and-drilling/
    ├── elements-and-supports/
    ├── feed-node-preparation/
    ├── boom-retention/
    └── completed-mechanical-build/
```

Photographs are supporting evidence. Recorded measurements remain the controlled as-built data.

---

## 33. Fabrication deviation log

Record every departure from O3-O6.

| Deviation ID | Part / station | Designed value | As-built value | Cause | Disposition | Approved by / date |
|---|---|---:|---:|---|---|---|
|  |  |  |  |  |  |  |
|  |  |  |  |  |  |  |
|  |  |  |  |  |  |  |

Do not hide a mistake by editing the design value. A misplaced RF station, short element, failed coupon, damaged cable, or clearance violation requires a stop and documented disposition.

---

## 34. Stop conditions

Stop O6 for any of the following:

- A failed material or hardware coupon.
- Tape steel wider than the approved geometry.
- A short-cut, kinked, cracked, or badly twisted RF element.
- A misplaced RF station.
- Cracked, split, crushed, or badly drilled PVC.
- A 2 m support that cannot share the approved hole without distortion.
- A driven gap that will not stay within tolerance.
- A feed-node hole that tears, cracks, or approaches a tape edge unsafely.
- Any feed screw capable of touching the opposite driven half.
- A separator that compresses below 0.250 in or slips uncontrollably.
- Relative boom rotation or axial slip after final retention.
- Less than the required boom, support, hardware, or reflector clearance.
- Unexpected electrical continuity.
- A proposed metal support, metal joint, PVC tee, crossbar, hinge, pivot, or permanent adhesive joint.
- Any substitution that changes the controlled RF or mechanical geometry.

---

## 35. O6 completion checklist

O6 is complete only when:

- [ ] O3, O4, O5, and O6 Rev. B inputs are present.
- [ ] Material measurements are recorded.
- [ ] All coupon tests pass.
- [ ] Both booms are 30.000 in and correctly labeled.
- [ ] All stations and holes pass inspection.
- [ ] All ten tape-steel pieces pass cut and label inspection.
- [ ] All three 12.000 in supports are installed without unauthorized trimming.
- [ ] Every element is centered, aligned, and retained nonconductively.
- [ ] Both driven gaps and overall spans pass.
- [ ] Four feed-node holes are drilled through tape only.
- [ ] Contact pads are clean and untinned.
- [ ] Node-center spacings are recorded.
- [ ] J1/J2 retention uses approved pads and 8 in minimum ties.
- [ ] Fixed 90-degree operating geometry passes the hand-load check.
- [ ] All cross-boom and reflector clearances pass.
- [ ] Pre-feed DC checks pass.
- [ ] O5 as-built mechanical table is complete.
- [ ] Fabrication deviations are closed or formally dispositioned.
- [ ] Required photographs are stored.
- [ ] No coax has been cut and no transmitter has been connected.

---

## 36. Handoff to O7

Deliver the following to the feed-system phase:

- Completed mechanical antenna or two labeled separated booms with fresh retention ties reserved.
- O5 as-built mechanical record.
- O6 completed quality gates.
- Node-hole diameters and node-center spacing for both bands.
- Selected #6-32 screw length from the coupon.
- Feed-hardware parts bag labeled by band.
- Photographs of driven gaps and node locations.
- Open deviation list, if any.

O7 must preserve the recorded gaps, spans, element stations, plane angle, and clearances while installing the coax, lugs, 2 m hairpin, ferrites, strain relief, and labels.

O7 must not add tight boom-wound coax coils or a passive BNC tee.

---

## 37. Revision control

| Revision | Date | Description |
|---|---|---|
| Rev. A | 2026-08-24 | Initial fabrication and assembly procedure. |
| **Rev. B** | **2026-09-21** | Retained the verified mechanical sequence; removed rotating/folding joint instructions, six-inch dual-boom ties, PVC feed-screw drilling, support trimming, and O7 feed work; added complete coupon testing, tape-only node drilling, fixed removable boom retention, separator pads, tighter tolerances, clearance checks, DC isolation tests, as-built records, and explicit stop conditions. |

The 2026-09-15 boom-retention drawing was an unreleased draft and did not consume the Rev. B repository revision identifier.

---

## 38. Engineering intent

O6 Rev. B produces a traceable mechanical antenna structure that can be compared directly with the controlled design and safely handed to O7.

The procedure intentionally stops before electrical feed construction and RF tuning. A mechanically complete antenna is not an electrically accepted antenna. Operational release still requires O7 feed installation, O8 calibrated impedance and SWR testing, common-mode sensitivity checks, and later field validation.

---

**End of O6 Rev. B Fabrication and Assembly Procedure**


---

**End of O6 Fabrication & Assembly Procedure**
