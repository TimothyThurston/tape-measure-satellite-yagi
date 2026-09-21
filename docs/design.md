# O3 - Antenna Design and Dimensions

## Tape Measure Satellite Yagi

**Project:** Tape Measure Satellite Yagi  
**Project ID:** TM-YAGI-01  
**Document:** O3 Antenna Design and Dimensional Baseline  
**Repository path:** `docs/design.md`  
**Application:** Handheld amateur-radio satellite and ISS operation  
**Bands:** 2 m / 70 cm  
**Revision:** Rev. B  
**Date:** 2026-09-21  
**Status:** Controlled pre-fabrication design baseline  

---

## 1. Purpose

This document defines the Revision B architecture, RF geometry, dimensional conventions, mechanical interfaces, feed interfaces, tolerances, and verification requirements for the Tape Measure Satellite Yagi.

Revision B retains the verified W6NBC-derived element lengths and within-band spacings from Rev. A. It replaces the outdated joint, folding, touching-boom, coax-coil, polarization, and fabrication assumptions identified during the September 2026 construction-readiness review.

This document controls design intent. O4 controls materials and sourcing. O5 controls exact cutting, marking, drilling, mechanical fit, and as-built dimensional records. O6 and O7 control fabrication and feed construction. O8 controls calibrated RF testing and tuning.

---

## 2. Revision B audit disposition

### 2.1 Verified without RF-geometry change

| Design item | Audit result |
|---|---|
| Three-element 2 m Yagi geometry | Retained |
| Five-element 70 cm Yagi geometry | Retained |
| Element lengths | Arithmetic and source comparison passed |
| Driven-half calculations | Passed |
| Within-band station spacings | Passed |
| Front/rear coordinate conversion | Passed |
| Two 30.000 in booms | Retained |
| 2 m shunt-hairpin topology | Retained as a tunable starting design |
| 70 cm direct-feed topology | Retained as a tunable starting design |

### 2.2 Corrected in Revision B

| Rev. A issue | Revision B disposition |
|---|---|
| Booms described as mechanically joined and rotatable | Removed. The booms are retained in one fixed operating orientation using removable ties and separator pads. |
| Folded storage configuration | Removed. The booms are separated for storage by cutting and replacing the retention ties. |
| Touching PVC booms | Removed. Installed bare-surface clearance is at least 0.250 in. |
| Separate joint or pivot assumptions | Removed. No hinge, tee, crossbar, pivot, or dedicated joint mechanism is used. |
| Tight six-turn and four-turn RG-58 boom coils | Removed. Band-appropriate snap-on ferrites are the baseline. |
| Mixed rear and front datum conventions | FRONT is now the primary construction datum; rear values are cross-checks. Physical element locations are unchanged. |
| Broad fabrication tolerances | Replaced by the tighter O5 Rev. B controls, including the close-reflector clearance. |
| Orthogonal arrays implied cross- or circular polarization | Corrected. Each band remains linearly polarized; the two different-band element planes are orthogonal. |
| Hairpin defined mainly by wire length | Replaced by a measurable starting geometry plus tuning record requirements. |
| Blanket no-short check for driven halves | Corrected. The completed 2 m hairpin intentionally creates DC continuity across its feed nodes. |
| Incomplete feedpoint mechanical interface | Added controlled node assignments, coupon requirement, fastener stack interface, and clearance rules. |

---

## 3. Design requirements

### 3.1 Intended use

The antenna is a portable, handheld, dual-band directional antenna intended primarily for amateur-radio satellite and International Space Station operation.

The design must support:

- Manual azimuth and elevation tracking.
- Manual roll of the complete antenna for polarization adjustment.
- Separate 2 m and 70 cm RF feeds.
- Two-radio full-duplex operating arrangements, subject to receiver-desensitization testing.
- Field disassembly without a permanent boom joint.
- Repeatable reconstruction of the controlled operating geometry.

### 3.2 Frequency scope

| Band | Amateur allocation used for characterization | Design reference frequency |
|---|---:|---:|
| 2 m | 144-148 MHz | 145 MHz |
| 70 cm | 420-450 MHz | 435 MHz |

The reference frequencies are geometry sanity-check points, not guaranteed resonance points. O8 must evaluate the actual operating channels selected for satellite and ISS use.

### 3.3 Performance claims

Before measurement, Revision B claims only a controlled prototype geometry. It does not claim a measured value for:

- Resonant frequency.
- Feedpoint impedance.
- SWR or return loss.
- Forward gain.
- Front-to-back ratio.
- Beamwidth.
- Cross-band isolation.
- Common-mode suppression.
- Receiver desensitization.

Those values require calibrated testing of the completed antenna and station.

---

## 4. Antenna architecture

The antenna consists of two distinct Yagi-Uda arrays mounted on two separate, parallel PVC booms:

| Array | Elements | Boom | Feed |
|---|---|---|---|
| 2 m | Reflector, split driven element, one director | One 30.000 in nominal 1/2 in Schedule 40 PVC boom | Independent 50 ohm RG-58 line; shunt hairpin at feedpoint |
| 70 cm | Reflector, split driven element, three directors | One 30.000 in nominal 1/2 in Schedule 40 PVC boom | Independent 50 ohm RG-58 line; direct feed |

Both arrays point toward the same FRONT/director end. Both boom centerlines remain parallel.

The element planes are orthogonal in the operating assembly. This arrangement provides one linear polarization on 2 m and a different linear polarization on 70 cm. Because the orthogonal fields are on different bands, the complete antenna is **not** a same-frequency crossed Yagi and does **not** inherently produce circular polarization.

The operator adjusts polarization by rolling the complete antenna about the shared longitudinal direction, not by rotating one boom inside a joint.

---

## 5. Coordinate system and dimensional conventions

### 5.1 Primary datum

Revision B uses one construction datum for both booms:

- **FRONT = X 0.000 in** at the director end and intended direction of gain.
- **REAR = X 30.000 in** at the operator/handle end.
- Every station is measured independently from FRONT.

The rear-end cross-check is:

`X from REAR = 30.000 in - X from FRONT`

This changes only the controlling notation from O3 Rev. A. It does not move any element.

### 5.2 Length convention

- Passive-element length is finished conductive tip-to-tip length.
- Split-driven-element overall span includes the physical center gap.
- Split-driven-element conductive length excludes the center gap.
- Individual driven-half lengths are controlled separately.
- Inches govern. Metric values are rounded references using 1 in = 25.4 mm.

### 5.3 Orientation terms

- **Front:** director end and intended primary direction of gain.
- **Rear:** reflector/operator end.
- **Left/right:** viewed from behind the antenna while looking toward FRONT.
- **Element plane:** the plane containing the longitudinal boom centerline and that band's elements.

---

## 6. Controlled RF element schedule

### 6.1 2 m array

| ID | Element | Finished length or span | X from FRONT | X from REAR | Notes |
|---|---|---:|---:|---:|---|
| 2M-D1 | Director 1 | 35.400 in (899.2 mm) | 2.000 in (50.8 mm) | 28.000 in (711.2 mm) | Forward-most 2 m element |
| 2M-DE | Driven element | 37.400 in (950.0 mm) overall | 13.500 in (342.9 mm) | 16.500 in (419.1 mm) | Split; 0.250 in center gap |
| 2M-R | Reflector | 41.400 in (1051.6 mm) | 21.500 in (546.1 mm) | 8.500 in (215.9 mm) | Rear-most 2 m element |

The 2 m design uses one director. No 2M-D2 element is used.

### 6.2 70 cm array

| ID | Element | Finished length or span | X from FRONT | X from REAR | Notes |
|---|---|---:|---:|---:|---|
| 70-D3 | Director 3 | 11.700 in (297.2 mm) | 3.500 in (88.9 mm) | 26.500 in (673.1 mm) | Forward-most 70 cm element |
| 70-D2 | Director 2 | 11.900 in (302.3 mm) | 9.500 in (241.3 mm) | 20.500 in (520.7 mm) | Director |
| 70-D1 | Director 1 | 11.900 in (302.3 mm) | 15.500 in (393.7 mm) | 14.500 in (368.3 mm) | Director |
| 70-DE | Driven element | 12.600 in (320.0 mm) overall | 18.500 in (469.9 mm) | 11.500 in (292.1 mm) | Split; 0.250 in center gap |
| 70-R | Reflector | 12.900 in (327.7 mm) | 21.000 in (533.4 mm) | 9.000 in (228.6 mm) | Rear-most 70 cm element |

The 70 cm design uses three directors. No 70-D4 or 70-D5 element is used.

---

## 7. Driven-element geometry

### 7.1 Controlled dimensions

| Parameter | 2 m | 70 cm |
|---|---:|---:|
| Overall tip-to-tip span | 37.400 in (950.0 mm) | 12.600 in (320.0 mm) |
| Physical center gap | 0.250 in (6.35 mm) | 0.250 in (6.35 mm) |
| Combined conductive length | 37.150 in (943.6 mm) | 12.350 in (313.7 mm) |
| Left-half length | 18.575 in (471.8 mm) | 6.175 in (156.8 mm) |
| Right-half length | 18.575 in (471.8 mm) | 6.175 in (156.8 mm) |

Calculations:

- 2 m: `(37.400 - 0.250) / 2 = 18.575 in per half`
- 70 cm: `(12.600 - 0.250) / 2 = 6.175 in per half`

The physical steel-tip gap and the feed-node screw spacing are different dimensions. O5 sets the screw locations after the actual material stack is dry-fitted.

### 7.2 Electrical isolation

Before the 2 m hairpin is connected, the two halves of each driven element must be isolated from one another. After the 2 m hairpin is connected, its two nodes have intended DC continuity through the hairpin. The 70 cm driven halves remain DC-isolated from each other when disconnected from RF equipment.

---

## 8. Element spacing

### 8.1 2 m adjacent spacing

| From | To | Spacing |
|---|---|---:|
| 2M-D1 | 2M-DE | 11.500 in (292.1 mm) |
| 2M-DE | 2M-R | 8.000 in (203.2 mm) |

### 8.2 70 cm adjacent spacing

| From | To | Spacing |
|---|---|---:|
| 70-D3 | 70-D2 | 6.000 in (152.4 mm) |
| 70-D2 | 70-D1 | 6.000 in (152.4 mm) |
| 70-D1 | 70-DE | 3.000 in (76.2 mm) |
| 70-DE | 70-R | 2.500 in (63.5 mm) |

Absolute FRONT-datum stations remain controlling. Spacing values are independent cross-checks.

---

## 9. RF geometry sanity check

Using `lambda = c / f` with `c = 299,792,458 m/s`:

| Reference | Wavelength |
|---|---:|
| 145 MHz | 81.399 in (2.0675 m) |
| 435 MHz | 27.133 in (0.6892 m) |

Element-length ratios at the reference frequencies:

| Element class | 2 m ratio | 70 cm ratio |
|---|---:|---:|
| Reflector | 41.400 / 81.399 = 0.509 lambda | 12.900 / 27.133 = 0.475 lambda |
| Driven conductive length | 37.150 / 81.399 = 0.456 lambda | 12.350 / 27.133 = 0.455 lambda |
| Director(s) | 35.400 / 81.399 = 0.435 lambda | 11.900 / 27.133 = 0.439 lambda; 11.700 / 27.133 = 0.431 lambda |

These ratios are plausible for coupled Yagi arrays and agree with the retained source geometry. They do not predict the completed antenna's exact impedance, resonance, gain, or pattern.

---

## 10. Conductive material and supports

### 10.1 Tape steel

The baseline radiating material is conductive spring-steel tape approximately 3/8 in wide.

| Group | Net conductive length |
|---|---:|
| 2 m | 113.950 in |
| 70 cm | 60.750 in |
| **Total** | **174.700 in (14.558 ft)** |

At least 18 ft of usable tape steel is reserved to cover damaged material, cutting loss, coupons, and replacements.

Changing the blade width, thickness, curvature, coating, or base material can change electrical and mechanical behavior. One-inch or wider tape is not a drop-in substitution.

### 10.2 2 m supports

Each 2 m element station uses one nonconductive 3/8 in x 12.000 in support. The controlled installed quantity is three.

The actual tape, support, and PVC must pass the O5 material-coupon fit test before the final booms are drilled.

### 10.3 70 cm support

The 70 cm tape steel passes through the validated boom holes without a separate longitudinal dowel. Retention remains nonconductive.

---

## 11. Boom geometry and retention

### 11.1 Booms

| Parameter | Requirement |
|---|---|
| Material | Nominal 1/2 in Schedule 40 PVC, nonmetallic |
| Quantity | Two separate booms |
| Finished length | 30.000 in each |
| Alignment | FRONT-to-FRONT and REAR-to-REAR |
| Longitudinal relationship | Parallel |
| Element-plane relationship | 90 degrees +/- 2 degrees |

### 11.2 Relative cross-section

In the operating assembly:

- The line between boom centers is 45 degrees +/- 5 degrees from either element plane.
- Bare PVC surface-to-surface separation is at least 0.250 in.
- Clearance from either boom to components carried by the other boom is at least 0.125 in.
- The 2M-R and 70-R stations retain at least 0.0625 in measured physical edge clearance.

The 45-degree cross-section and separator gap provide clearance for the 2 m supports and keep both element planes away from the neighboring pipe.

### 11.3 Retention

| Station | X from FRONT | Components |
|---|---:|---|
| J1 | 4.500 in +/- 0.125 in | One nonconductive separator pad and one 8 in minimum UV-resistant tie |
| J2 | 22.500 in +/- 0.125 in | One nonconductive separator pad and one 8 in minimum UV-resistant tie |

Each pad is approximately 1.000 x 0.500 in with at least 0.250 in installed thickness. No retention holes are drilled in either boom.

The ties and pads are removable retention consumables, not a separate boom-joint mechanism. Revision B prohibits a hinge, pivot bolt, PVC tee, PVC crosspiece, crossbar, metal boom connector, wood spacer block, and permanent adhesive joint.

There is no separate boom-joint mechanism in Revision B.

The booms do not rotate relative to one another while retained. Cut and replace the ties to separate or reassemble the antenna.

---

## 12. Close-feature clearance

With both FRONT ends aligned:

- 70-R is centered at 21.000 in.
- 2M-R is centered at 21.500 in.
- Nominal longitudinal center separation is 0.500 in.

O5 controls this pair at 0.500 in +/- 0.03125 in and requires at least 0.0625 in measured physical edge clearance after assembly.

If the actual tape width, curvature, or mounting orientation violates the clearance requirement, fabrication stops for an engineering review. Do not bend, notch, offset, or shorten an RF element merely to clear the other array.

---

## 13. Feed and matching architecture

### 13.1 Independent feeds

Each band has one independent 50 ohm RG-58 feedline terminating in its own operator-end BNC male connector.

The two antenna feeds are not combined with a passive BNC tee. The baseline station uses two radios and two independent feeds. Any future single-port arrangement requires a properly specified VHF/UHF diplexer and a separate station-interface revision.

### 13.2 Feed nodes

| Band | Node A | Node B |
|---|---|---|
| 2 m | One driven half + coax center lug + one hairpin end | Other driven half + coax braid lug + other hairpin end |
| 70 cm | One driven half + coax center lug | Other driven half + coax braid lug |

Left/right assignment may be reversed before assembly, but the selected convention must remain consistent and labeled.

### 13.3 Mechanical node interface

Each node uses its own #6-32 stainless screw, nut, flat washer, and coax ring lug. The 2 m nodes also capture the bare hairpin ends.

O5 requires:

- A material coupon before drilling final feed hardware.
- Symmetric screw placement on the exposed driven halves.
- The shortest usable 1/2 in or 3/4 in screw.
- At least two full threads visible beyond the nut.
- Clean bare-metal contact only at the node.
- No tinning beneath a washer or mechanical clamp.
- No screw or lug capable of touching the opposite driven half.

The node screw-center spacing is measured as-built; it is not assumed to equal the 0.250 in steel-tip gap.

### 13.4 2 m shunt hairpin

The 2 m baseline uses an 8.500 in initial blank of fully bare #12 AWG solid copper connected in shunt across the two feed nodes.

The starting geometry is a symmetric U with:

- Parallel equal-length legs.
- Leg spacing equal to the measured feed-node spacing.
- One smooth 180-degree bottom bend.
- Orientation away from the 70 cm boom and rearward coax route.
- Recorded leg spacing, leg length, bend diameter, and conductor clearance.

Wire length alone does not define the hairpin's RF reactance. O8 tunes and records the final geometry from measured impedance.

### 13.5 70 cm direct feed

The 70 cm coax center and braid connect directly to the two isolated driven halves. No separate matching wire or intentional DC bridge is included in the baseline.

---

## 14. Common-mode suppression and cable routing

Revision B deletes the tight RG-58 coils around the PVC booms.

| Feed | Initial suppression baseline | Validation |
|---|---|---|
| 2 m | Four Fair-Rite 31-material snap-on ferrites, baseline part 0431164281 or verified equivalent | O8 coax-movement test |
| 70 cm | Four Fair-Rite 61-material snap-on ferrites, baseline part 0461164281 or verified equivalent | O8 coax-movement test |

The actual RG-58 jacket diameter must be measured before ordering or installing ferrites. Equivalent parts require documented material, sufficient cable opening, and a secure closure.

Cable routing requirements:

- Place the ferrite group near the feedpoint before the rearward run.
- Keep the intact jacket close to the feedpoint.
- Strain-relieve the cable without loading the electrical nodes.
- Route toward REAR/operator end.
- Keep cable and ferrites clear of elements, hairpin, J1, J2, and the other feedpoint.
- Obey the cable manufacturer's minimum bend radius.
- Do not wrap RG-58 tightly around either boom.
- Label the free BNC ends `2 m` and `70 cm`.

Ferrite count and position remain subject to O8 measurement. Low SWR alone does not prove adequate common-mode suppression.

---

## 15. Fabrication tolerances

O5 Rev. B controls the following targets:

| Feature | Tolerance or requirement |
|---|---:|
| 2 m passive element length | +/- 0.0625 in |
| 2 m driven-half length | +/- 0.03125 in; half mismatch no more than 0.03125 in |
| 70 cm passive element length | +/- 0.03125 in |
| 70 cm driven-half length | +/- 0.0156 in; half mismatch no more than 0.0156 in |
| 2 m station from FRONT | +/- 0.0625 in |
| 70 cm station from FRONT | +/- 0.03125 in |
| Driven steel-tip gap | 0.250 in +/- 0.0156 in |
| Element-plane angle | 90 degrees +/- 2 degrees |
| Installed bare-surface boom gap | 0.250 in minimum |
| 2M-R to 70-R center separation | 0.500 in +/- 0.03125 in |
| 2M-R to 70-R physical edge clearance | 0.0625 in minimum |

Actual dimensions are recorded before RF tuning. A dimensional deviation is not corrected by silently changing the design value.

---

## 16. RF interaction and polarization

### 16.1 Coupled-array behavior

Yagi performance results from current induced in the reflector and directors by the driven element. The final response depends on the complete geometry, including:

- Element lengths and spacings.
- Tape width, curvature, coating, and conductivity.
- Feedpoint and hairpin geometry.
- PVC and support material.
- Coax routing and common-mode current.
- Nearby elements on the other band.
- Boom spacing and relative orientation.

The 2 m structure is electrically significant near the 70 cm region, so the two arrays must be tested both separately and in their complete assembled configuration.

### 16.2 Polarization

Each Yagi is linearly polarized in its own element plane. The 90-degree relationship does not create circular polarization because the two orthogonal arrays do not radiate the same frequency with controlled equal amplitude and quadrature phase.

During operation, roll the complete antenna as required to maximize the received signal or accommodate changing propagation polarization. Do not rotate one boom relative to the other.

---

## 17. DC verification interface

With radios, diplexers, and analyzers disconnected:

| Test condition | 2 m expected | 70 cm expected |
|---|---|---|
| BNC pin to assigned driven half | Continuity | Continuity |
| BNC shell to assigned driven half | Continuity | Continuity |
| Pin to shell before hairpin bridge | Open | Open |
| Pin to shell in finished baseline | Continuity through hairpin | Open |
| Either feed conductor to parasitic elements | Open | Open |
| Between the two independent feeds | Open | Open |

The 2 m unwanted-short test is performed with one hairpin end disconnected. A completed hairpin can otherwise mask an accidental feedpoint short.

---

## 18. RF testing interface

O8 must establish the performance of the as-built antenna before transmit.

Minimum design-interface requirements:

- Calibrate the analyzer with OPEN, SHORT, and LOAD over the chosen sweep.
- Verify calibration with a known 50 ohm load.
- State the measurement reference plane.
- Sweep 144-148 MHz and 420-450 MHz for characterization.
- Take dense measurements at the actual planned transmit and receive channels.
- Record SWR, resistance, reactance, and complex measurement data where available.
- Compare each array separately and in the complete assembled configuration.
- Terminate or document the unused feed during every test.
- Repeat measurements while moving the coax to detect common-mode sensitivity.
- Recheck after every hairpin, ferrite, cable-route, or weatherproofing change.
- Do not connect an active transmitter to the analyzer.

The project acceptance target is SWR no greater than 2:1 at each required transmit frequency, subject to any stricter radio-manufacturer requirement. Seek no greater than 1.5:1 near primary operating channels where practical without sacrificing directional performance.

SWR acceptance does not prove useful gain, pattern, polarization response, or receiver isolation. O9 and O10 field tests remain required.

---

## 19. Station integration interface

The baseline satellite station uses:

- One radio and feed for uplink.
- One radio and feed for downlink.
- A flexible radio-side jumper or other strain relief at each handheld connector.
- Separate `2 m` and `70 cm` labels.

Before operational release, test whether the uplink transmitter desensitizes or overloads the downlink receiver. Dual-band or dual-watch capability does not itself prove simultaneous transmit/receive performance.

Filtering, a diplexer, or another station-level change must be selected from measured behavior and device specifications. It is not part of the radiating-structure baseline unless formally added by revision.

---

## 20. Configuration records

Maintain three distinct configurations:

### 20.1 As-designed

The controlled Rev. B dimensions and interfaces in O3 through O7 before fabrication.

### 20.2 As-built

The actual measured dimensions, materials, node spacing, hairpin geometry, boom gap, clearances, ferrite placement, and cable routing before RF tuning.

### 20.3 As-tuned

The final dimensions and feed configuration after O8 adjustments.

Do not overwrite design values with fabricated or tuned values. Record deviations so the effect of construction and tuning can be evaluated.

---

## 21. Pre-construction hold points

The design is released, but physical construction remains conditional on the actual materials passing O4/O5 inspection.

- [ ] Actual PVC OD recorded.
- [ ] Tape width, thickness, curvature, coating, and conductivity recorded.
- [ ] Support diameter recorded.
- [ ] Coax diameter and documented bend limit recorded where available.
- [ ] Ferrite fit confirmed on the actual coax.
- [ ] Shared 2 m tape/support/PVC coupon passed.
- [ ] 70 cm tape/PVC coupon passed.
- [ ] Feed-node screw, nut, washer, lug, and hairpin coupon passed.
- [ ] Separator-pad installed thickness confirmed.
- [ ] Cross-boom and close-reflector clearances confirmed.

Failure of a hold point requires a documented deviation or design revision before the affected final parts are made.

---

## 22. O3 acceptance checklist

- [x] Project name is consistently **Tape Measure Satellite Yagi**.
- [x] Project ID is TM-YAGI-01.
- [x] Revision is Rev. B.
- [x] Two separate 30.000 in booms are defined.
- [x] No separate boom-joint mechanism is included.
- [x] Front/rear and left/right conventions are defined.
- [x] Every element has a unique ID, length, and absolute station.
- [x] Driven-element half lengths and gaps are defined.
- [x] Within-band spacings are verified.
- [x] Net conductive steel length is verified as 174.700 in.
- [x] Orthogonal different-band planes are not mischaracterized as circular polarization.
- [x] Feed nodes and matching topology are defined.
- [x] Tight coax coils are removed.
- [x] Band-appropriate ferrite baselines are defined.
- [x] Mechanical retention and clearances agree with O4 and O5 Rev. B.
- [x] Fabrication tolerances agree with O5 Rev. B.
- [x] Correct pre- and post-hairpin DC expectations are defined.
- [x] RF and station-level validation requirements are defined.
- [ ] Actual material measurements and coupons have passed.
- [ ] As-built configuration has been recorded.
- [ ] O8 RF acceptance has passed.

The final three open items are physical build and test gates, not missing design definitions.

---

## 23. Revision control

| Revision | Date | Description |
|---|---|---|
| Rev. A | 2026-08-24 | Initial formal design and dimensional baseline. |
| **Rev. B** | **2026-09-21** | Retained verified RF geometry; standardized the FRONT datum; removed rotating/folding joint and touching-boom assumptions; corrected polarization language; replaced coax coils with ferrites; aligned feedpoint, tolerance, clearance, DC-test, station, and configuration controls with the Rev. B BOM and cut sheet. |

The 2026-09-15 boom-retention drawing was an unreleased draft and did not consume the Rev. B repository revision identifier.

---

## 24. Related controlled documents

| Document | Function |
|---|---|
| O4 Rev. B - Bill of Materials and Sourcing | Materials, quantities, ownership, substitutions, and receiving inspection |
| O5 Rev. B - Mechanical Drawing and Cut Sheet | Cutting, station layout, drilling, mechanical assembly dimensions, and hold points |
| O6 - Fabrication and Assembly | Controlled build sequence |
| O7 - Feed and Matching System | Coax preparation, node construction, hairpin setup, ferrites, and strain relief |
| O8 - Initial RF Testing and Tuning | Analyzer calibration, tuning, acceptance, and coax-movement test |
| O9/O10 - Field Validation | Directional, comparative, satellite, and ISS operational testing |

---

## 25. Engineering intent

Revision B provides a self-consistent design baseline for a buildable dual-band handheld satellite antenna without relying on the mechanically conflicting assumptions in Rev. A.

The retained RF geometry is a credible published starting point, not proof of final performance. Engineering completion requires the as-built record, calibrated impedance and SWR measurements, common-mode sensitivity testing, directional field evidence, and station-level desensitization testing.

Baseline RF geometry is derived from the project design set based on John Portune, W6NBC, QST, January 2012, pages 37-39. Revision B boom retention, feed hardware, ferrite suppression, tolerances, clearance controls, and verification gates are TM-YAGI-01 project-specific engineering changes.

---

**End of O3 Rev. B Antenna Design and Dimensions**
