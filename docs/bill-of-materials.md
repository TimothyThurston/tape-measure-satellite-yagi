# O4 — Bill of Materials & Sourcing

## Tape Measure Satellite Yagi

**Project:** Tape Measure Satellite Yagi  
**Project ID:** TM-YAGI-01  
**Document:** O4 Bill of Materials & Sourcing  
**Repository path:** `docs/bill-of-materials.md`  
**Application:** Handheld amateur-radio satellite and ISS operation  
**Bands:** 2 m / 70 cm  
**Revision:** Rev. L  
**Date:** 2026-10-12  
**Status:** Controlled construction and procurement baseline  

---

## 1. Purpose

This document defines the materials, quantities, specifications, ownership status, substitutions, and receiving inspections for the Revision L Tape Measure Satellite Yagi.

Revision B retains the verified W6NBC-derived RF geometry while correcting the material and integration problems found during the September 2026 construction-readiness review.

This document controls material selection. Exact cut locations, mounting geometry, assembly steps, and RF acceptance procedures are controlled by O5 through O8.

---

## 2. Revision L configuration

The Revision L antenna uses:

- Two separate 30.000 in booms made from nominal 1/2 in Schedule 40 PVC.
- One three-element 2 m Yagi.
- One five-element 70 cm Yagi.
- Approximately 3/8 in wide conductive steel tape-measure elements.
- Three separate 3/8 in × 12 in nonconductive supports for the 2 m elements.
- Two independent 50 ohm RG-58 feed lines.
- One BNC interface per band.
- A split 2 m driven element with a 0.250 in center gap and a tunable #12 solid-copper shunt hairpin.
- A split 70 cm driven element with a 0.250 in center gap and direct coax feed.
- Band-appropriate snap-on ferrite common-mode suppression near each feedpoint.
- Simple removable dual-boom retention using UV-resistant cable ties and nonconductive separator pads.

Revision L does **not** use:

- A separate boom-joint mechanism.
- A hinge, pivot bolt, PVC tee, PVC crosspiece, crossbar, or metal boom connector.
- Wooden spacer blocks.
- Four-inch cable ties around both booms.
- Tight RG-58 coils wound around the 1/2 in PVC booms.
- A BNC tee to combine the two antenna feeds.

The cable ties and separator pads are retention consumables, not a separate boom-joint assembly.

---

## 3. Controlled RF material totals

### 3.1 Tape-steel requirement

The split driven-element gaps contain no conductive steel. The net tape requirement is therefore:

| Band | Element | Conductive steel |
|---|---|---:|
| 2 m | Reflector | 41.400 in |
| 2 m | Driven halves combined | 37.150 in |
| 2 m | Director 1 | 35.400 in |
|  | **2 m subtotal** | **113.950 in** |
| 70 cm | Reflector | 12.900 in |
| 70 cm | Driven halves combined | 12.350 in |
| 70 cm | Director 1 | 11.900 in |
| 70 cm | Director 2 | 11.900 in |
| 70 cm | Director 3 | 11.700 in |
|  | **70 cm subtotal** | **60.750 in** |
|  | **Total net steel** | **174.700 in (14.558 ft)** |

Procure or reserve at least **20 ft (240.000 in) of usable tape steel** in lengths that allow every scheduled cut and one continuous 41.400 in spare section for a full 2M-R reflector recut. The installed elements use 174.700 in; adding the spare requires 216.100 in and leaves 23.900 in for end cleanup, damaged coating, cutting loss, and test coupons. Obtain more steel if actual losses exceed that margin.

### 3.2 PVC requirement

| Item | Finished quantity | Nominal finished length | Nominal net total |
|---|---:|---:|---:|
| 2 m boom | 1 | 30.000 in | 30.000 in |
| 70 cm boom | 1 | 30.000 in | 30.000 in |
| **Total** | **2** |  | **60.000 in** |

One 10 ft PVC length is sufficient and provides ample cutting allowance. O5 Rev. L accepts each finished boom at 30.000 in +/- 0.0625 in and requires the two finished lengths to differ by no more than 0.03125 in. The two finished booms remain intact and parallel; no tee or crosspiece is required.

### 3.3 Nonconductive support requirement

Use three individual **3/8 in × 12.000 in nominal** dowels or fiberglass rods, one at each 2 m element station. Each finished support must measure **12.000 in +/- 0.0625 in** (11.9375-12.0625 in) under O5 Hold Point C. Individual precut pieces are preferred over attempting three exact cuts from a nominal 36 in stick; measure each precut piece before acceptance.

---

## 4. Controlled build BOM

Status terms:

- **Owned:** Previously confirmed as on hand.
- **Verify:** Expected to be on hand, but must be physically inspected before use.
- **Acquire:** Required for Revision L and not previously confirmed as owned.
- **Select after measurement:** Exact variant depends on actual measured material.

| ID | Item | Controlled specification | Installed quantity | Procurement quantity | Status | Notes |
|---|---|---|---:|---:|---|---|
| BOM-001 | PVC pipe | Nominal 1/2 in Schedule 40 PVC, nonmetallic | 2 × 30.000 in nominal | 1 × 10 ft stock length | **Owned** | Finished-length acceptance: each 30.000 in +/- 0.0625 in; pair difference no more than 0.03125 in per O5. Measure actual OD before layout. Do not use the purchased tee. |
| BOM-002 | Tape-measure steel | Conductive spring steel, approximately 3/8 in wide, minimum 20 ft usable with one continuous 41.400 in recut section | 174.700 in net | Minimum 20 ft usable | **Verify** | Reject wide 1 in or 1-1/4 in blades unless O5 is redesigned. |
| BOM-003 | 2 m element supports | 3/8 in × 12.000 in nominal hardwood dowel or fiberglass rod | 3 | 5 minimum | **Owned — 10 pieces** | Nonmetallic only. Each finished piece must pass 12.000 in +/- 0.0625 in; retain spares for drilling and fit tests. |
| BOM-004 | 2 m feed line | 50 ohm RG-58, 6 ft, factory BNC male-to-male | 1 | 1 | **Owned** | One antenna-end connector will be removed only after routing is approved. |
| BOM-005 | 70 cm feed line | 50 ohm RG-58, 6 ft, factory BNC male-to-male | 1 | 1 | **Owned** | One antenna-end connector will be removed only after routing is approved. |
| BOM-006 | 2 m common-mode ferrites | Fair-Rite 31-material Snap-It, maximum cable diameter at least 0.250 in; baseline part 0431164281 or verified equivalent | 4 | 5 | **Acquire after cable measurement** | Install near the 2 m feedpoint. Final count is validated during O8 coax-movement testing. |
| BOM-007 | 70 cm common-mode ferrites | Fair-Rite 61-material Snap-It, maximum cable diameter at least 0.250 in; baseline part 0461164281 or verified equivalent | 4 | 5 | **Acquire after cable measurement** | Install near the 70 cm feedpoint. Final count is validated during O8 coax-movement testing. |
| BOM-008 | Dual-boom retention ties | UV-resistant black nylon cable ties, 8 in minimum nominal length | 2 | 8 minimum | **Acquire / verify** | One at each O5 retention station plus spares. Four-inch ties are prohibited for the two-boom wrap. |
| BOM-009 | Nonconductive separator pads | Nylon, acetal, or HDPE; 0.375 in minimum installed thickness; approximately 1.0 × 0.5 in footprint | 2 | 4 | **Acquire** | One at each retention station. Not a hinge or joint. Final pad geometry is controlled by O5. |
| BOM-010 | Feedpoint screws | #6-32 stainless machine screws; stock both 1/2 in and 3/4 in lengths | 4 final | 8 of each candidate length | **Owned in hardware assortment** | O5 selects the shortest length that fully engages the nut without approaching the opposite electrical node. |
| BOM-011 | Feedpoint nuts | #6-32 stainless nuts | 4 | 8 | **Owned in hardware assortment** | No loose hardware permitted. |
| BOM-012 | Feedpoint flat washers | #6 stainless flat washers | 4 minimum | 12 | **Owned in hardware assortment** | Final stack count is controlled by the O5 feedpoint detail. |
| BOM-013 | Coax feed lugs | 22–16 AWG ring terminals with #4–6 stud opening | 4 | 8 | **Acquire / verify** | Two per feed line: center conductor and braid. |
| BOM-014 | 2 m hairpin conductor | #12 AWG solid copper, bare or stripped THHN | 1 adjustable blank | 12 in minimum | **Owned — 25 ft THHN** | O7 cuts, labels, and measures the 8.500 in initial blank before forming it; finished geometry is controlled and tuned by O7/O8. |
| BOM-015 | Small strain-relief ties | UV-resistant nylon cable ties, approximately 4 in | As required | 20 minimum | **Verify** | Used only for element support, ferrite retention, and coax strain relief—not around both booms. |
| BOM-016 | Heat-shrink tubing | Thin-wall polyolefin assortment sized for individual coax conductors and terminals | As required | 1 assortment | **Owned — 240-piece assortment** | Do not cover a contact until DC inspection is complete. |
| BOM-017 | Electronics solder | Sn99.3/Cu0.7 electronics solder | As required | Existing spool | **Owned** | Use only with electronics-compatible flux. |
| BOM-018 | Separate pivot/joint hardware | **Retired — not used in Revision L** | 0 | 0 | **Removed** | No pivot bolt, hinge, tee, crossbar, or dedicated joint assembly. ID is not reassigned. |
| BOM-019 | Electronics flux | Flux compatible with coax conductors, copper lugs, and solder alloy | As required | 1 | **Verify** | Clean residues as required by the product instructions. |
| BOM-020 | Contact-preparation abrasive | Fine emery cloth or equivalent | As required | 1 small piece | **Verify** | Expose clean conductive steel only where electrical contact is required. |
| BOM-021 | Electrical tape | Quality vinyl electrical tape | As required | 1 roll | **Verify** | Temporary positioning and finishing only; not a structural joint. |
| BOM-022 | Feedpoint labels | Durable labels or heat-shrink identifiers marked `2 m` and `70 cm` | 2 | 4 | **Acquire / fabricate** | Both BNC tails must be unambiguous. |

---

## 5. Common-mode suppression change

Revision B replaces the earlier six-turn and four-turn tight RG-58 boom coils with snap-on ferrites.

Reasons for the change:

1. A tight coax winding occupies the same space as the neighboring parallel boom.
2. Winding RG-58 around nominal 0.840 in OD PVC may violate the purchased cable's minimum bend radius.
3. Snap-on parts can be installed after the cable is routed and can be changed during O8 testing without shortening the feed line.
4. Different ferrite materials can be selected for the 2 m and 70 cm operating ranges.

Baseline selections:

- **2 m:** Fair-Rite 31 material, suitable for lower-frequency suppression through the VHF range.
- **70 cm:** Fair-Rite 61 material, intended for high-frequency suppression in the UHF range.

The specified part numbers accept cable up to 0.250 in diameter. Measure the actual RG-58 before ordering. Equivalent parts require the same material family, adequate inside diameter, secure closure, and published manufacturer data.

The initial installed count is four ferrites per feed. O8 must repeat the SWR/impedance measurement while the coax is moved. Add or reposition ferrites if the antenna response changes materially with cable position.

---

## 6. Dual-boom retention materials

Revision L has no separate boom-joint assembly.

The two booms are retained at the O5 stations using:

- One 8 in UV-resistant cable tie at each station.
- One nonconductive separator pad at each station.
- No holes through either boom for retention.
- No metal connector between the booms.

The separator establishes at least 0.375 in of bare-surface clearance between the two PVC pipes. O5 controls pad geometry, retention method, boom orientation, and the minimum installed surface gap. The tied booms remain fixed relative to each other; cut and replace the ties to separate them for storage.

The ties must retain both booms without crushing the PVC. Replace any tie that is nicked, UV-damaged, or permanently stretched.

---

## 7. Feedpoint hardware allowance

The antenna has four electrical feed nodes:

- 2 m Node A: coax center conductor, one driven half, and one hairpin end.
- 2 m Node B: coax braid, the other driven half, and the other hairpin end.
- 70 cm Node A: coax center conductor and one driven half.
- 70 cm Node B: coax braid and the other driven half.

The BOM intentionally stocks both 1/2 in and 3/4 in #6-32 screws. O5 selects the shortest usable screw after an actual-material coupon confirms the screw, bare tape contact pad, coax ring lug, 2 m hairpin hook where applicable, flat washer, and nut stack. O5/O6 use visible witness marks to verify the hidden driven gaps, then drill each feed-node hole through the exposed driven-half tape only while the halves have removable temporary retention. Final driven-station ties are installed after drilling and refitting; this does not change hardware quantities.

Do not substitute a full transverse bolt through the entire pipe. Each screw must contact only its assigned driven half and must remain clear of the opposite electrical node.

---

## 8. Owned station-interface accessories

These items support radio connection and strain relief but are not part of the antenna's radiating assembly.

| ID | Item | Quantity | Status | Use |
|---|---|---:|---|---|
| STA-001 | RG-316 BNC-to-SMA jumper, approximately 20 in | 2 | **Owned** | Flexible radio pigtails and connector strain relief. |
| STA-002 | Short RG-8X BNC male-to-female cable | 1 | **Owned** | Optional extension/strain relief where appropriate. |
| STA-003 | Earpiece/headset | 1 | **Verify** | Downlink monitoring during two-radio operation. |

Do not connect the 2 m and 70 cm antenna feeds with a passive BNC tee. The baseline satellite station uses two independent radios and two independent feed lines.

---

## 9. Reusable tools and test equipment

These are required or recommended project equipment and are not charged as installed antenna material.

| Item | Status | Purpose |
|---|---|---|
| Weller soldering iron | **Owned** | Feedline and lug soldering. |
| Klein MM450 multimeter | **Owned** | Continuity and accidental-short checks only. |
| Wire stripper/crimper | **Owned** | Coax preparation and lug work. |
| Drill and square | **Verify** | Controlled boom and feedpoint drilling. |
| 7/16 in drill bit | **Verify** | Baseline element-station holes; final use requires O5 coupon approval. |
| Approximately 5/32 in drill bit | **Verify** | Candidate #6 clearance size; verify on scrap and actual hardware. |
| Caliper | **Acquire / borrow if unavailable** | Measure PVC, coax, tape, dowels, screws, and spacer thickness. |
| NanoVNA or equivalent calibrated antenna analyzer | **Required before transmit; not previously owned** | Measure S11, SWR, resistance, reactance, tuning, and cable sensitivity. |
| 50 ohm calibration load and required adapters | **Acquire with analyzer** | Establish and verify the measurement reference plane. |
| Eye protection and gloves | **Required** | Cutting and handling spring-steel tape. |

The multimeter cannot determine antenna resonance, impedance, SWR, gain, or common-mode choke effectiveness.

---

## 10. Receiving and phase-entry inspection

Record actual measurements in the Section 11 as-purchased log before the material's phase uses it. Mechanical materials are accepted before O6 final-part work. Coax and ferrites are accepted under the O5 Section 12 feed-entry gate before O7 removes either antenna-side BNC connector; their acceptance does not block O6 mechanical work.

### PVC

- [ ] PVC stock is sufficient for two intact nominal 30.000 in booms; O5 Hold Point C will check each finished length against 30.000 in +/- 0.0625 in and the pair difference against 0.03125 in maximum.
- [ ] Actual outside diameter is recorded.
- [ ] Pipe is straight and undamaged.
- [ ] No tee or crosspiece is assigned to the antenna.

### Tape steel

- [ ] Blade is approximately 3/8 in wide.
- [ ] Blade thickness and curvature are recorded.
- [ ] Base metal is electrically conductive.
- [ ] At least 20 ft is usable and free from severe kinks, cracks, and corrosion.
- [ ] The cutting plan preserves one continuous 41.400 in section for a possible full 2M-R recut through cut inspection.
- [ ] A scrap coupon is reserved for drilling and contact tests.

### Supports

- [ ] At least three straight 3/8 in support pieces are available at or above 11.9375 in; precut pieces pass the 12.000 in +/- 0.0625 in finished-length limit, and longer stock has enough length to trim.
- [ ] Actual diameters are recorded.
- [ ] One spare is reserved for the tape/dowel/PVC coupon.

### Coax - before O7 feed entry

- [ ] Both cables are confirmed as 50 ohm RG-58.
- [ ] Actual jacket diameter is recorded.
- [ ] Manufacturer/model and published bend radius are recorded if available.
- [ ] Both factory BNC connectors pass continuity and short tests.
- [ ] No connector is cut off before O5/O7 routing approval.

### Ferrites - before O7 feed entry

- [ ] The initial installed counts are available: four 31-material parts for 2 m and four 61-material parts for 70 cm.
- [ ] The selected inside diameter fits the measured coax.
- [ ] The 2 m parts are verified as 31 material or an approved equivalent.
- [ ] The 70 cm parts are verified as 61 material or an approved equivalent.
- [ ] Parts latch securely and can be strain-relieved without crushing the coax.

### Retention components

- [ ] Eight-inch UV-resistant ties are available.
- [ ] Separator pads are at least 0.375 in thick after installation.
- [ ] Pad material is nonconductive and dimensionally stable.

### Feed hardware

- [ ] #6-32 screw, nut, washer, and lug fit are verified.
- [ ] Candidate screw lengths are available.
- [ ] Ring terminals accept the actual coax conductors.
- [ ] No hardware can bridge the driven-element gap.

---

## 11. As-purchased record

Complete this table from packages and receipts. Prices are historical records, not controlled engineering dimensions.

| BOM ID | Manufacturer / product | Actual specification | Quantity on hand | Unit cost | Date checked | Accepted / deviation |
|---|---|---|---:|---:|---|---|
| BOM-001 |  |  |  |  |  |  |
| BOM-002 |  |  |  |  |  |  |
| BOM-003 |  |  |  |  |  |  |
| BOM-004 |  |  |  |  |  |  |
| BOM-005 |  |  |  |  |  |  |
| BOM-006 |  |  |  |  |  |  |
| BOM-007 |  |  |  |  |  |  |
| BOM-008 |  |  |  |  |  |  |
| BOM-009 |  |  |  |  |  |  |
| BOM-010–013 |  |  |  |  |  |  |
| BOM-014–017 |  |  |  |  |  |  |
| BOM-019–022 |  |  |  |  |  |  |

---

## 12. Substitution control

### Substitutions allowed after inspection

- Another manufacturer of nominal 1/2 in Schedule 40 PVC with comparable actual dimensions.
- Fiberglass rod in place of hardwood dowel at the same controlled diameter.
- Another approximately 3/8 in conductive spring-steel blade that fits the validated O5 mounting coupon.
- Equivalent RG-58 with known 50 ohm impedance and documented physical properties.
- Equivalent snap-on ferrites with the same material range, suitable cable opening, and published data.
- Brass feed hardware in place of stainless if dimensions and corrosion compatibility are verified.

### Substitutions requiring O3/O5/O7 review

- One-inch or wider tape blade.
- A different boom outside diameter.
- Metal or carbon-fiber boom material.
- Wire or rod radiating elements.
- Different feedline type or length.
- Air-wound coax choke.
- Different hairpin wire gauge or stranded hairpin wire.
- Any mechanism that rigidly joins the booms.

### Prohibited substitutions

- Metal 2 m element supports.
- Passive BNC tee for combining the two antenna feeds.
- Four-inch ties around both booms.
- A PVC tee, crossbar, metal pivot, or permanent boom joint.
- Unidentified ferrite material sold only by color or appearance.

---

## 13. O4 release checklist

- [x] Project name is consistently **Tape Measure Satellite Yagi**.
- [x] Two separate 30.000 in PVC booms and O5 finished-length and pair-matching acceptance limits are specified.
- [x] Net tape-steel requirement is 174.700 in.
- [x] Procurement allowance is at least 20 ft usable tape steel with a 41.400 in recut section reserved.
- [x] Three individual 3/8 in × 12.000 in nominal supports and their finished-length tolerance are specified.
- [x] Two independent 6 ft RG-58/BNC feed lines are specified.
- [x] Tight boom-wound coax coils have been removed from the baseline.
- [x] Band-appropriate snap-on ferrite materials are specified.
- [x] Eight-inch dual-boom retention ties are specified.
- [x] Nonconductive separator pads are included.
- [x] Separate pivot/joint hardware has been removed.
- [x] Feedpoint screws, nuts, washers, and lugs are counted.
- [x] The 8.500 in hairpin is identified as an initial adjustable blank.
- [x] Previously owned major materials and tools are recorded.
- [x] NanoVNA/analyzer testing is required before transmit.
- [ ] Actual mechanical material measurements have been entered before O6 final-part work; coax and ferrite checks are entered before O7 feed work.
- [ ] O5 has released the mounting coupon, separator geometry, and final screw stack.

The final two open checklist items are physical phase-entry and O5 interface checks. They do not require additional O4 design changes unless actual material or coupon inspection fails.

---

## 14. Revision control

| Revision | Date | Description |
|---|---|---|
| Rev. A | 2026-08-24 | Initial sourcing baseline. |
| Rev. B | 2026-09-21 | Standardized project name; removed separate joint hardware and four-inch dual-boom ties; added separator pads; replaced tight coax coils with band-appropriate snap-on ferrites; corrected dowel stock allowance; expanded feedpoint hardware, inspection, ownership, and substitution controls. |
| Rev. C | 2026-10-12 | Increased the minimum installed separator-pad thickness and bare-PVC boom gap from 0.250 in to 0.375 in to satisfy the 0.125 in support clearance at the 40-degree orientation limit; clarified fixed boom retention and tape-only feed-node screws. |
| Rev. D | 2026-10-12 | Raised minimum usable tape-steel procurement to 20 ft and reserved a continuous 41.400 in section for one full reflector recut; installed steel total remains 174.700 in. |
| **Rev. E** | **2026-10-12** | Aligned BOM feedpoint notes with exterior driven-gap witness marks and delayed driven-station tie installation; material quantities are unchanged. |
| **Rev. F** | **2026-10-12** | Added explicit PVC finished-length and pair-matching acceptance limits from O5; quantities and nominal cuts are unchanged. |
| **Rev. G** | **2026-10-12** | Aligned references with the O5/O6 record-phase clarification; materials, quantities, and procurement status are unchanged. |
| **Rev. H** | **2026-10-12** | Assigned the BOM-014 hairpin-blank cut and measurement to O7 and aligned controlled references; materials and quantities are unchanged. |
| **Rev. I** | **2026-10-12** | Clarified that coax and ferrite receiving checks precede O7 feed work rather than O6 mechanical entry; BOM quantities are unchanged. |
| **Rev. J** | **2026-10-12** | Added the finished-length acceptance range for three 12.000 in supports; procurement and installed quantities are unchanged. |
| **Rev. K** | **2026-10-12** | Aligned document references with the O5/O6 rear-station cross-check limit; materials and quantities are unchanged. |
| **Rev. L** | **2026-10-12** | Aligned controlled references with the expanded O5/O6 mechanical as-built record; materials and quantities are unchanged. |

The 2026-09-15 boom-retention drawing was an unreleased draft and did not consume the Rev. B repository revision identifier.

---

## 15. Engineering intent

This BOM provides every material needed to construct and test the Revision L prototype without relying on the mechanically conflicting assumptions in the Rev. A drawing set.

It does not claim measured RF performance. The finished antenna must pass the O8 calibrated impedance/SWR checks, coax-movement test, two-band assembled checks, and station-level receiver-desensitization test before operational release.
