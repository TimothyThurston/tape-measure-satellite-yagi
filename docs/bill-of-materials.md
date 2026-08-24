# O4 — Bill of Materials & Sourcing

## Tape Measure Satellite Yagi

**Project:** Tape Measure Satellite Yagi  

**Document:** O4 Bill of Materials & Sourcing  

**Repository Path:** `docs/bill-of-materials.md`  

**Application:** Amateur-Radio Satellite / ISS Operation  

**Bands:** 2 m / 70 cm  

**Design Inputs:** Finalized O3 baseline with planned O5/O7 mechanical and feed interfaces  

**Design Status:** Pre-Fabrication Sourcing Baseline  

**Revision:** Rev. A  

**Price Check Date:** 2026-08-24

---

# 1. Purpose

This document is the formal bill of materials and sourcing record for the Tape Measure Satellite Yagi.

It defines:

- Required antenna materials
- Required quantities
- Required stock dimensions
- Material specifications
- Feedline and connector hardware
- Fasteners
- Consumables
- Reusable tools and test equipment
- Estimated costs
- Baseline sourcing
- Owned-vs-purchased status
- Acceptable substitutes
- Procurement notes
- As-purchased records

This document is intended to remain synchronized with:

- **O3 — Antenna Design & Dimensions**
- **O5 — Mechanical Drawing & Cut Sheet**
- **O6 — Fabrication & Assembly**
- **O7 — Feed & Matching System**
- **O8 — Initial RF Testing & Tuning**

Any purchased item that differs materially from this baseline should be documented in the **As-Purchased Record** and evaluated before fabrication.

---

# 2. Design Traceability

The BOM is based on the finalized O3 dimensional baseline together with the planned O5 mechanical interface and planned O7 feed-system interface. Mechanical joint details and final feed implementation remain subject to completion of those phases.

## 2.1 Structural Configuration

- Two separate **30.000 in (762.0 mm)** booms
- Nominal **1/2 in Schedule 40 PVC**
- Three-element 2 m Yagi
- Five-element 70 cm Yagi
- Flexible small-width steel tape-measure elements
- Dual-boom structure capable of approximately **90° relative rotation**
- 3/8 in nonconductive stiffeners on the long 2 m elements

## 2.2 Feed Configuration

### 2 m

- 50 Ω RG-58 coax
- Split driven element
- 0.250 in (6.35 mm) center gap
- 8.500 in (215.9 mm) #12 AWG solid-copper hairpin
- Six-turn RG-58 choke
- BNC external connection

### 70 cm

- 50 Ω RG-58 coax
- Split driven element
- 0.250 in (6.35 mm) center gap
- No separate impedance-matching element
- Four-turn RG-58 choke
- BNC external connection

---

# 3. Tape-Measure Stock Requirement

The net conductive steel required by the O3 element schedule is:

## 3.1 2 m Steel Requirement

| Element | Conductive Steel Required |
| --- | ---: |
| 2M-R | 41.400 in |
| 2M-DE-L | 18.575 in |
| 2M-DE-R | 18.575 in |
| 2M-D1 | 35.400 in |
| **2 m total** | **113.950 in** |

**113.950 in ÷ 12 = 9.496 ft**

## 3.2 70 cm Steel Requirement

| Element | Conductive Steel Required |
| --- | ---: |
| 70-R | 12.900 in |
| 70-DE-L | 6.175 in |
| 70-DE-R | 6.175 in |
| 70-D1 | 11.900 in |
| 70-D2 | 11.900 in |
| 70-D3 | 11.700 in |
| **70 cm total** | **60.750 in** |

**60.750 in ÷ 12 = 5.063 ft**

## 3.3 Total Steel Requirement

**113.950 in + 60.750 in = 174.700 in**

**174.700 in ÷ 12 = 14.558 ft**

### Procurement Requirement

**Absolute minimum usable stock:** 14.56 ft  

**Recommended minimum usable stock:** **18 ft**  

**Preferred procurement quantity:** **20 ft or more**

The additional stock provides allowance for:

- End-hook removal
- Damaged coating
- Test cuts
- Deburring
- Fabrication errors
- Future replacement elements
- V2 experimentation

The baseline source below provides considerably more stock than the antenna requires.

---

# 4. Primary Build BOM

Prices are planning values observed on **2026-08-24** and are provided for budgeting only.

They do **not** include:

- Sales tax
- Shipping
- Local-store price differences
- Promotional discounts

| BOM ID | Item | Specification | Purchase Qty | Used in Build | Baseline Source | Est. Price | Inventory Status |
| --- | --- | --- | ---: | ---: | --- | ---: | --- |
| BOM-001 | PVC pipe | 1/2 in nominal Schedule 40 PVC, 10 ft | 1 | 60 in total | Home Depot — Charlotte Pipe/JM Eagle equivalent | $7.56 | **VERIFY** |
| BOM-002 | Tape-measure steel | Small-width conductive steel tape; baseline 3/8 in × 100 ft | 1 | 174.700 in net | Home Depot — Stanley FATMAX 100 ft × 3/8 in | $27.93 | **VERIFY** |
| BOM-003 | Element stiffener | 3/8 in × 36 in wood or fiberglass dowel | 1 | Approx. 36 in | Home Depot — 3/8 in × 36 in hardwood dowel | $2.28 | **VERIFY** |
| BOM-004 | 2 m coax feed | RG-58, 50 Ω, BNC male-to-male, 6 ft | 1 | Approx. 5–6 ft | Home Depot — SANOXY 6 ft RG58 BNC cable | $8.03 | **VERIFY** |
| BOM-005 | 70 cm coax feed | RG-58, 50 Ω, BNC male-to-male, 6 ft | 1 | Approx. 5–6 ft | Home Depot — SANOXY 6 ft RG58 BNC cable | $8.03 | **VERIFY** |
| BOM-006 | Feedpoint machine screws | #6-32 × 1/2 in stainless pan-head | 1 pack | 4 required; extras retained | Home Depot — Hillman 30-pack | $4.99 | **VERIFY** |
| BOM-007 | Feedpoint nuts | #6-32 machine-screw nuts | 1 pack | 4 required | Home Depot — Everbilt 12-pack | $1.38 | **VERIFY** |
| BOM-008 | Feedpoint flat washers | #6 stainless flat washer | 1 pack | 4–8 required | Home Depot — Everbilt 12-pack | $1.57 | **VERIFY** |
| BOM-009 | Feed lugs | 22–16 AWG, #4–6 stud ring terminals | 1 pack | 4 required | Gardner Bender or equivalent | $4.00 budget | **VERIFY** |
| BOM-010 | Hairpin conductor | #12 AWG solid copper wire | 1 ft | 8.500 in | Home Depot — Southwire solid CU THHN by foot | $0.49 | **VERIFY** |
| BOM-011 | Boom/element ties | 4 in UV-resistant black cable ties | 1 pack | Approx. 12–20 | Home Depot — Commercial Electric 100-pack UV black | $10.78 | **VERIFY** |
| BOM-018 | Dual-boom pivot/joint hardware | Mechanically secure joint allowing approximately 90° relative boom rotation; exact hardware and geometry to be finalized in O5 | 1 assembly | 1 assembly | TBD after O5 mechanical detail | TBD | **PLANNED** |

### Primary Build Subtotal

**Known-price primary-build procurement subtotal: $77.04**

This subtotal includes BOM-001 through BOM-011 and excludes **BOM-018 — Dual-boom pivot/joint hardware**, whose exact hardware and price remain TBD until the O5 mechanical joint is finalized.

Actual cash cost will be lower if PVC, hardware, cable ties, wire, or other materials are already on hand.

---

# 5. Optional / Recommended Consumables

These are strongly useful during fabrication but are not unique RF components.

| BOM ID | Item | Specification | Qty | Baseline Source | Est. Price | Required? | Inventory Status |
| --- | --- | --- | ---: | --- | ---: | --- | --- |
| BOM-012 | Heat-shrink tubing | Thin-wall polyolefin assortment | 1 pack | Home Depot — Commercial Electric 8-pack | $2.90 | Recommended | **VERIFY** |
| BOM-013 | Electrical tape | 3/4 in vinyl electrical tape | 1 roll | Home Depot — Commercial Electric | $2.68 | Recommended | **VERIFY** |
| BOM-014 | Solder | Electronics solder appropriate for coax/feed work | 1 | Existing shop supply / electronics supplier | TBD | Required for preferred construction | **VERIFY** |
| BOM-015 | Flux | Electronics-compatible flux | 1 | Existing shop supply / electronics supplier | TBD | Recommended | **VERIFY** |
| BOM-016 | Abrasive | Fine sandpaper / emery cloth | 1 | Existing shop supply / hardware store | TBD | Required | **VERIFY** |
| BOM-017 | Permanent marker | Fine-point | 1 | Existing shop supply | TBD | Required | **VERIFY** |

### Primary Build + Priced Consumables

**$77.04 + $2.90 + $2.68 = $82.62**

**Estimated subtotal with currently priced consumables: $82.62**

Solder, flux, abrasive, and miscellaneous shop supplies are excluded until inventory is checked.

---

# 6. PVC Stock Allocation

One 10 ft length provides:

**10 ft × 12 = 120 in**

Required:

- 2 m boom: **30.000 in**
- 70 cm boom: **30.000 in**

Total used:

**30 in + 30 in = 60 in**

Remaining:

**120 in - 60 in = 60 in**

**PVC utilization:** 50%

The remaining material should be retained for:

- Replacement boom
- Drilling practice
- Feedpoint experiments
- V2 parts
- Other antenna projects

---

# 7. Dowel Stock Allocation

Baseline stock:

**3/8 in × 36 in**

Recommended initial cuts:

- 12 in stiffener
- 12 in stiffener
- 12 in stiffener

These provide reinforcement at the three 2 m element stations.

The exact installed stiffener lengths may be shortened during O6 if required for fit or portability.

The stiffener material must remain:

- Nonconductive
- Mechanically stiff
- Small enough to fit the intended boom-hole arrangement

Acceptable materials include:

- Hardwood dowel
- Fiberglass rod

Avoid replacing the stiffener with conductive metal unless the antenna is deliberately redesigned and retested.

---

# 8. Dual-Boom Pivot / Joint Requirement

The antenna requires a mechanical joint that connects the 2 m and 70 cm PVC booms while allowing approximately **90° relative rotation** for normal operation and a more parallel/folded configuration for storage.

The exact joint hardware is intentionally **not specified as a final purchased part in Rev. A** because the detailed geometry belongs to O5 — Mechanical Drawing & Cut Sheet.

The O5 joint design must define:

- Pivot location
- Fastener or hinge type
- Required washers/spacers
- Locking or friction method
- Whether conductive hardware is acceptable at the selected location
- Clearance for coax routing
- Mechanical stop or rotation limit, if used
- Folded/storage position
- Operating position

Procurement rule:

> Do not purchase final pivot/joint hardware until the O5 mechanical detail is complete.

BOM-018 remains a planned, unpriced line item until that design is finalized.

---

# 9. Coax and BNC Hardware Strategy

## 9.1 V1 Baseline

V1 uses:

**Two 6 ft RG-58 50 Ω BNC male-to-male premade cables**

One cable is assigned to each band.

During fabrication:

1. One BNC connector is retained as the antenna's external connector.
2. The opposite connector is removed.
3. The cut coax end is stripped.
4. Center conductor and shield are separated.
5. Feed lugs are installed.
6. The cable itself forms the required coax choke.
7. Remaining cable is routed toward the handle/rear.

This approach avoids requiring:

- BNC crimp tools
- Bulk RG-58 termination tools
- Separate field-installed BNC plugs

## 9.2 Required Retained BNC Interfaces

Final V1 antenna:

- **2 m:** one BNC male feed connector
- **70 cm:** one BNC male feed connector

The BNC ends must be permanently labeled by band.

Suggested labels:

- `2M`
- `70CM`

## 9.3 Radio-Specific Adapters

Radio adapters are **not core antenna components** because the antenna should not be permanently tied to one handheld.

Purchase the correct adapter only after the final radio connector is confirmed.

Examples may include:

- BNC female → SMA male
- BNC female → SMA female
- BNC adapters for a VNA/test cable

**Never assume SMA gender/polarity from the word "SMA" alone. Verify the actual radio connector.**

---

# 10. Coax Length Adequacy

A 6 ft feed line provides:

**6 ft × 12 = 72 in**

The cable must accommodate:

- Feedpoint connection
- Coax choke
- Routing toward the rear/handle
- Rotation slack between booms
- External connection to the radio or adapter

Approximate choke-wrap consumption around nominal 1/2 in Schedule 40 PVC is modest relative to 72 in of available cable.

The final coax should **not** be shortened until the mechanical routing and choke geometry are confirmed during O6/O7.

---

# 11. Fastener Schedule

The published construction uses #6-32 screws at the driven-element feedpoints.

V1 requires:

## 2 m Feedpoint

- 2 × #6-32 machine screws
- 2 × #6-32 nuts
- 2–4 × #6 flat washers
- 2 × coax feed lugs
- Hairpin ends captured at the feed hardware

## 70 cm Feedpoint

- 2 × #6-32 machine screws
- 2 × #6-32 nuts
- 2–4 × #6 flat washers
- 2 × coax feed lugs

### Minimum Hardware Actually Used

| Part | Minimum Qty |
| --- | ---: |
| #6-32 screws | 4 |
| #6-32 nuts | 4 |
| #6 flat washers | 4 |
| Feed lugs | 4 |

Additional hardware is intentionally purchased as spare stock.

---

# 12. Feed-Lug Specification

The RG-58 center conductor is substantially smaller than #12–14 building wire.

Therefore, the preferred feed-lug range is:

**22–16 AWG**

with:

**#4–6 stud opening**

This is a correction over the earlier rough shopping discussion that mentioned larger 16–14 AWG terminals.

Acceptable terminal types:

1. Ring terminal — preferred
2. Fork/spade terminal — acceptable if mechanically secure
3. Properly formed/soldered direct connection — acceptable only if strain relief is excellent

The terminal must fit the #6 feedpoint screw without being mechanically loose.

---

# 13. Hairpin Match Material

The 2 m matching element requires:

- **#12 AWG solid copper**
- **8.500 in (215.9 mm)** initial length

The purchased THHN insulation may be removed in the active hairpin region if necessary for forming and consistent geometry.

Do not substitute:

- Stranded wire
- Steel wire
- Aluminum wire

without documenting the substitution and retesting the matching system.

Preferred substitute:

**Bare #12 solid copper wire**

---

# 14. Tape-Measure Material Requirements

The baseline antenna concept requires flexible conductive steel tape-measure material.

The original W6NBC design describes the elements as ordinary **small-width tape-measure material** and uses 7/16 in holes in the PVC boom.

For TM-YAGI-01 V1, the preferred procurement specification is:

- Steel blade
- Approximately **3/8 in wide**
- At least **18 ft usable length**
- Conductive base metal
- Flexible
- Free of severe kinks or corrosion

The baseline 100 ft × 3/8 in Stanley product greatly exceeds the required stock length but satisfies the narrow-width requirement.

### Do Not Substitute Blindly

Many modern 25 ft retractable tape measures use:

- 1 in blades
- 1-1/4 in blades
- Thick wide blades

Those will **not fit the O5/O6 7/16 in through-hole construction**.

A wider blade may still be usable in a redesigned slotted boom, but that would be a **mechanical-design revision**, not a drop-in substitution.

---

# 15. Acceptable Substitutions

## 15.1 PVC

### Baseline

1/2 in Schedule 40 PVC

### Acceptable

- Same nominal size from another manufacturer
- Similar nonconductive tubing with comparable stiffness

### Requires Design Review

- Metal boom
- Carbon-fiber boom
- Substantially different outside diameter

---

## 15.2 Element Steel

### Baseline

Approximately 3/8 in wide flexible steel tape

### Acceptable

Small-width steel tape material that fits the boom and remains mechanically usable

### Requires Design Review

- 1 in or wider tape
- Solid aluminum rod
- Copper rod
- Stainless rod
- Wire elements

These change geometry and/or mounting.

---

## 15.3 Dowel

### Baseline

3/8 in hardwood

### Preferred Substitute

3/8 in fiberglass rod

### Do Not Substitute Directly

Metal rod

---

## 15.4 Coax

### Baseline

RG-58, 50 Ω

### Acceptable

Another flexible 50 Ω coax of similar outside diameter if:

- Choke geometry is re-evaluated
- Feed routing remains practical
- Connector termination is compatible

Possible alternatives include:

- RG-316
- RG-174 for very short/light feed sections
- Higher-quality flexible 50 Ω coax

Do not substitute **75 Ω television coax**.

---

## 15.5 BNC Connector

### Baseline

BNC

### Acceptable

Another 50 Ω RF connector if the entire interface is documented

BNC remains preferred for V1 because it is:

- Quick-disconnect
- Mechanically robust
- Common in RF test work
- Easy to adapt to radios and a VNA

---

## 15.6 Fasteners

### Baseline

#6-32 stainless machine hardware

### Acceptable

Equivalent #6-32 corrosion-resistant hardware

Avoid oversized metallic hardware near the feedpoint unless the effect is subsequently measured.

---

# 16. Optional Operating Accessories

These are **not required to fabricate or VNA-test the antenna**.

| Item | Purpose | Procurement Timing |
| --- | --- | --- |
| VHF/UHF diplexer | Combine independent 2 m and 70 cm antenna feeds into one dual-band radio port | Later |
| Radio-specific BNC/SMA adapter | Connect antenna to chosen HT | After radio connector is confirmed |
| Short BNC jumper | Bench/VNA flexibility | Optional |
| Headphones/earpiece | Satellite field operation | Optional |
| Tripod mount | Fixed terrestrial testing | Optional |
| Phone mount | Satellite tracking display | V2 option |
| Compass/inclinometer | Manual azimuth/elevation reference | Optional |

The diplexer remains external in V1.

---

# 17. Reusable Tools — Not Charged to Antenna BOM

These items are tools rather than consumed parts.

| Tool | Required / Recommended | Inventory Status |
| --- | --- | --- |
| Measuring tape / steel rule | Required | **VERIFY** |
| Fine-point marker | Required | **VERIFY** |
| Square | Recommended | **VERIFY** |
| Drill | Required | **VERIFY** |
| 7/16 in drill bit | Required for baseline boom holes | **VERIFY** |
| Approx. 5/32 in drill bit | Required for #6 feedpoint clearance holes; verify against actual hardware | **VERIFY** |
| PVC cutter / hacksaw | Required | **VERIFY** |
| Snips suitable for tape steel | Required | **VERIFY** |
| File / deburring tool | Required | **VERIFY** |
| Wire stripper | Required | **VERIFY** |
| Terminal crimper | Required if crimp lugs are used | **VERIFY** |
| Soldering iron | Required for preferred feedpoint construction | **VERIFY** |
| Heat source for heat shrink | Recommended | **VERIFY** |
| Multimeter | Required for O6 continuity checks | **VERIFY** |
| Safety glasses | Required | **VERIFY** |

---

# 18. RF Test Equipment — Project Equipment, Not Antenna Material

## 18.1 NanoVNA

O8 requires a vector network analyzer or equivalent antenna analyzer.

Recommended baseline:

**NanoVNA-H4**

Relevant capability:

- Covers the 145 MHz and 435 MHz design regions
- Measures S11
- Measures SWR
- Displays complex impedance
- Displays Smith chart
- Supports calibration standards
- Can export measurement data

Current planning source:

**Radioddity NanoVNA-H4 — $92.99 observed 2026-08-24**

This cost is **not included** in the antenna-material subtotal because the VNA is reusable test equipment for future RF projects.

## 18.2 VNA Adapters

Exact adapter requirements depend on the selected NanoVNA and final antenna connector arrangement.

Do not buy a pile of random adapters until the exact VNA connector kit is inspected.

---

# 19. Cost Summary

## 19.1 Antenna-Specific Primary Procurement

**Known-price subtotal:** **$77.04**

This excludes BOM-018 dual-boom pivot/joint hardware pending O5 mechanical finalization.

Includes:

- PVC
- Element steel
- Dowel
- Two RG-58/BNC feed lines
- Feedpoint screws
- Nuts
- Washers
- Feed lugs
- #12 copper wire
- Cable ties

## 19.2 With Currently Priced Recommended Consumables

**Known-price subtotal:** **$82.62**

This also excludes BOM-018 dual-boom pivot/joint hardware.

Adds:

- Heat shrink
- Electrical tape

Does not yet include unverified:

- Solder
- Flux
- Abrasive
- Miscellaneous shop supplies

## 19.3 With NanoVNA-H4 Purchased for the Project

**$82.62 + $92.99 = $175.61**

**Known-price planning total including reusable NanoVNA-H4: $175.61**

This total still excludes BOM-018 until the O5 joint hardware is finalized.

The NanoVNA should be treated as laboratory/project equipment rather than a one-time antenna expense.

---

# 20. Premium-Coax Alternative

A higher-cost premade RG-58 BNC cable can be substituted.

Example current source:

**Laird Digital Cinema RG58 50 Ω BNC male-to-male, 6 ft — $23.49 each**

Two cables:

**2 × $23.49 = $46.98**

Compared with the baseline two-cable estimate:

**2 × $8.03 = $16.06**

Additional cost:

**$46.98 - $16.06 = $30.92**

Estimated build cost with premium coax and priced consumables:

**$82.62 + $30.92 = $113.54**

For V1, the lower-cost RG-58 is acceptable provided it is verified to be:

- 50 Ω
- mechanically sound
- correctly terminated
- suitable for the operating power

---

# 21. Owned vs Purchased Record

Do not mark anything as owned until physically verified.

| BOM ID | Item | Owned | Need to Buy | Ordered | Received | Actual Cost |
| --- | --- | :---: | :---: | :---: | :---: | ---: |
| BOM-001 | 1/2 in PVC | [ ] | [ ] | [ ] | [ ] | $_____ |
| BOM-002 | Narrow steel tape stock | [ ] | [ ] | [ ] | [ ] | $_____ |
| BOM-003 | 3/8 in dowel/fiberglass | [ ] | [ ] | [ ] | [ ] | $_____ |
| BOM-004 | 2 m RG-58/BNC feed | [ ] | [ ] | [ ] | [ ] | $_____ |
| BOM-005 | 70 cm RG-58/BNC feed | [ ] | [ ] | [ ] | [ ] | $_____ |
| BOM-006 | #6-32 screws | [ ] | [ ] | [ ] | [ ] | $_____ |
| BOM-007 | #6-32 nuts | [ ] | [ ] | [ ] | [ ] | $_____ |
| BOM-008 | #6 washers | [ ] | [ ] | [ ] | [ ] | $_____ |
| BOM-009 | 22–16 AWG #4–6 feed lugs | [ ] | [ ] | [ ] | [ ] | $_____ |
| BOM-010 | #12 solid copper | [ ] | [ ] | [ ] | [ ] | $_____ |
| BOM-011 | UV-resistant cable ties | [ ] | [ ] | [ ] | [ ] | $_____ |
| BOM-012 | Heat shrink | [ ] | [ ] | [ ] | [ ] | $_____ |
| BOM-013 | Electrical tape | [ ] | [ ] | [ ] | [ ] | $_____ |
| BOM-014 | Solder | [ ] | [ ] | [ ] | [ ] | $_____ |
| BOM-015 | Flux | [ ] | [ ] | [ ] | [ ] | $_____ |
| BOM-016 | Sandpaper/emery cloth | [ ] | [ ] | [ ] | [ ] | $_____ |
| BOM-017 | Permanent marker | [ ] | [ ] | [ ] | [ ] | $_____ |
| BOM-018 | Dual-boom pivot/joint hardware | [ ] | [ ] | [ ] | [ ] | $_____ |

---

# 22. As-Purchased Record

Complete this section after procurement.

| BOM ID | Actual Product | Manufacturer / Model | Supplier | Qty | Actual Price | Date | Deviation from Baseline |
| --- | --- | --- | --- | ---: | ---: | --- | --- |
| | | | | | | | |
| | | | | | | | |
| | | | | | | | |
| | | | | | | | |

If a substitution changes:

- Material
- Width
- Diameter
- Electrical impedance
- Connector type
- Boom geometry
- Fastener size

the change must be reviewed before fabrication.

---

# 23. Baseline Sources

Prices and availability are volatile. The following links document the planning sources used for Rev. A.

## Antenna Materials

- 1/2 in × 10 ft Schedule 40 PVC:  

  <https://www.homedepot.com/p/100348471>

- Stanley FATMAX 100 ft × 3/8 in steel tape:  

  <https://www.homedepot.com/p/100070164>

- 3/8 in × 36 in hardwood dowel:  

  <https://www.homedepot.com/p/206184719>

- #6-32 × 1/2 in stainless machine screws:  

  <https://www.homedepot.com/p/204794602>

- #6-32 machine-screw nuts:  

  <https://www.homedepot.com/p/317478968>

- #6 stainless flat washers:  

  <https://www.homedepot.com/b/Hardware-Fasteners-Washers-Flat-Washers/6/12/N-5yc1vZc2ckZ1z141exZ1z1bsya>

- #12 AWG solid copper THHN, by foot:  

  <https://www.homedepot.com/p/204632003>

- 4 in UV-resistant black cable ties:  

  <https://www.homedepot.com/b/Electrical-Electrical-Tools-Wire-Conduit-Tools-Zip-Ties/Commercial-Electric/4-in/N-5yc1vZbm8eZdnZ1z1w8e9>

- Heat-shrink assortment:  

  <https://www.homedepot.com/p/311129165>

- Electrical tape:  

  <https://www.homedepot.com/p/309810154>

## RF / Coax

- Budget RG-58 6 ft BNC cable:  

  <https://www.homedepot.com/p/SANOXY-6-ft-RG58-BNC-Thinnet-Coaxial-Cable-SNX-CBL-LDR-BN105-1106/315877321>

- Premium Laird RG-58 6 ft BNC cable:  

  <https://www.bhphotovideo.com/c/product/1585553-REG/laird_digital_cinema_rg58_bb_6_rg58_50_ohm_bnc.html>

## Test Equipment

- Radioddity NanoVNA-H4:  

  <https://www.radioddity.com/products/nanovna-h4>

## Design Reference

- John Portune, W6NBC, *A 2 Meter and 70 CM Portable Tape Measure Beam*, QST, January 2012:  

  <https://w6nbc.com/articles/2011-12QSTtapemeasure.pdf>

---

# 24. Procurement Order

Recommended purchase/check sequence:

1. Inventory all existing tools and consumables.
2. Verify narrow steel tape stock can physically fit the O5 boom-hole geometry.
3. Purchase PVC.
4. Purchase tape-measure stock.
5. Purchase 3/8 in dowel/fiberglass.
6. Purchase RG-58/BNC feed cables.
7. Purchase #6-32 feedpoint hardware.
8. Purchase correctly sized 22–16 AWG feed lugs.
9. Obtain #12 solid copper wire.
10. Obtain UV-resistant cable ties.
11. Complete the O5 dual-boom pivot/joint detail.
12. Purchase BOM-018 pivot/joint hardware after O5 defines the exact requirement.
13. Fill any missing consumables.
14. Verify the actual handheld radio connector before buying an SMA/BNC adapter.
15. Acquire/verify the NanoVNA before O8.

---

# 25. Pre-Fabrication Receiving Inspection

Before cutting anything, verify every purchased component.

## PVC

- [ ] Correct nominal size
- [ ] At least 60 in usable length
- [ ] No cracks
- [ ] Straight enough for the project

## Tape Steel

- [ ] Conductive steel
- [ ] At least 18 ft usable
- [ ] Width compatible with boom-hole design
- [ ] No severe kinks
- [ ] No major corrosion

## Dowel / Fiberglass

- [ ] 3/8 in nominal size
- [ ] At least 36 in total
- [ ] Nonconductive
- [ ] Straight

## Coax

- [ ] RG-58 or approved substitute
- [ ] 50 Ω
- [ ] Two independent cables
- [ ] At least 6 ft each before modification
- [ ] BNC connectors mechanically sound

## Feed Hardware

- [ ] #6-32 screws fit nuts
- [ ] Washers fit screws
- [ ] Lugs fit #6 screws
- [ ] Lugs fit prepared RG-58 conductor
- [ ] Hardware quantity sufficient

## Hairpin Wire

- [ ] #12 AWG
- [ ] Solid copper
- [ ] At least 8.5 in usable

## Cable Ties

- [ ] UV-resistant material
- [ ] Length is suitable for the selected boom/element attachment
- [ ] Quantity is sufficient for the planned build
- [ ] No brittle, cracked, or damaged ties

## Dual-Boom Pivot / Joint Hardware

Complete this inspection after O5 finalizes BOM-018.

- [ ] Hardware matches the O5 mechanical detail
- [ ] Joint allows the required relative boom rotation
- [ ] Joint can be secured in the operating position
- [ ] Joint does not interfere with coax routing
- [ ] Clearances and spacers match the drawing
- [ ] Hardware is mechanically sound
- [ ] Any conductive hardware near RF elements has been reviewed for placement

---

# 26. O4 Acceptance Checklist

O4 may be considered complete when:

- [x] Required antenna materials are defined
- [x] Quantities are defined
- [x] Required tape-steel stock length is calculated
- [x] PVC stock and cut allocation are defined
- [x] Coax type and quantity are defined
- [x] BNC interface strategy is defined
- [x] Feedpoint hardware is defined
- [x] Hairpin material is defined
- [x] Cable-tie requirement is defined
- [x] Recommended consumables are defined
- [x] Reusable tools are separated from antenna materials
- [x] RF test equipment is separated from antenna materials
- [x] Estimated costs are documented
- [x] Baseline sources are documented
- [x] Substitution rules are documented
- [x] Owned-vs-purchased tracking fields are provided
- [x] Planned dual-boom pivot/joint requirement is represented in the BOM
- [x] Unpriced/TBD items are explicitly identified rather than silently included in cost totals
- [ ] O4 has been committed to the GitHub repository

### Procurement Follow-Up — Does Not Block O4 Closure

The following items are intentionally tracked after the sourcing baseline is complete and do **not** prevent the O4 issue from being closed:

- [ ] Physical inventory has been checked
- [ ] Actual purchases have been recorded
- [ ] Actual costs have been recorded
- [ ] BOM-018 pivot/joint hardware has been finalized after O5
- [ ] As-purchased deviations have been recorded as procurement occurs

---

# 27. Revision Control

| Revision | Date | Description |
| --- | --- | --- |
| Rev. A | 2026-08-24 | Initial formal O4 BOM and sourcing baseline based on finalized O3 dimensions with planned O5/O7 mechanical and feed interfaces |

Future revisions should preserve prior history.

---

# 28. Engineering Intent

O4 is not merely a shopping list.

The purpose of the BOM is to preserve traceability between:

**RF design**

↓

**Mechanical design**

↓

**Purchased material**

↓

**As-built hardware**

↓

**Measured RF response**

If an antenna dimension or material changes because a different part was purchased, that change should be visible in the project record.

This allows the final report to distinguish between:

- design assumptions
- procurement decisions
- fabrication deviations
- tuning modifications
- measured performance

---

**End of O4 Bill of Materials & Sourcing**
