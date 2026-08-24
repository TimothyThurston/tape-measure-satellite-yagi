# O3 — Antenna Design & Dimensions

## Tape Measure Satellite Yagi

**Project:** Tape Measure Satellite Yagi

**Document:** O3 Antenna Design & Dimensional Baseline

**Application:** Amateur-Radio Satellite / ISS Operation

**Bands:** 2 m / 70 cm

**Design Status:** Pre-Fabrication Baseline

**Revision:** Rev. A

---

## 1. Purpose

This document defines the pre-fabrication antenna design and dimensional baseline for the Tape Measure Satellite Yagi.

The antenna is a portable, handheld, dual-band directional antenna intended primarily for amateur-radio satellite and International Space Station operations using the 2 meter and 70 centimeter amateur bands.

This document establishes:

- Antenna architecture
- Element identification
- Element lengths
- Element positions
- Boom geometry
- Driven-element geometry
- Feedpoint location
- Antenna orientation
- Dimensional conventions
- Fabrication tolerances
- Design assumptions

These dimensions form the baseline for:

- O4 — Bill of Materials & Sourcing
- O5 — Mechanical Drawing & Cut Sheet
- O6 — Fabrication & Assembly
- O7 — Feed & Matching System
- O8 — Initial RF Testing & Tuning

Any dimensional changes made after fabrication begins should be documented separately as **as-built** or **as-tuned** revisions rather than silently replacing this baseline.

---

## 2. Design Requirements

The antenna is intended to satisfy the following general requirements.

### 2.1 Frequency Coverage

The design supports amateur-radio operation within:

| Band | Amateur Allocation |
| --- | ---: |
| 2 meters               | 144–148 MHz |
| 70 centimeters         | 420–450 MHz |

The antenna is optimized primarily for satellite-related portions of these bands rather than attempting to provide identical performance across every frequency in both allocations.

---

### 2.2 Primary Operating Use

The primary operating mode is handheld satellite tracking.

The antenna should therefore be:

- Directional
- Lightweight
- Portable
- Mechanically resilient
- Reasonably balanced when handheld
- Suitable for manual azimuth tracking
- Suitable for manual elevation tracking
- Capable of being rotated around the boom axis for polarization adjustment

The operator should be capable of continuously changing:

1. Azimuth
2. Elevation
3. Polarization

during a satellite pass.

---

## 3. Antenna Architecture

The antenna uses a **dual-band Yagi-Uda architecture** incorporating separate 2 m and 70 cm Yagi arrays on **two parallel 30.0 in portable PVC booms mechanically joined so the arrays can rotate relative to one another**.

Each band uses a combination of:

- Reflector element
- Driven element
- Director element(s)

The reflector is positioned behind the driven element relative to the primary direction of radiation.

The directors are positioned in front of the driven element.

Conceptually:

```text
REAR                                           FRONT

Reflector → Driven Element → Director(s) → Direction of Gain

                                          ───────────────►
```

The antenna's **front** is therefore the director end of the boom.

The antenna's **rear** is the reflector end.

---

## 4. Coordinate and Measurement System

To prevent ambiguity during fabrication, all boom positions are referenced to a single mechanical datum.

### 4.1 Boom Datum

Define:

**X = 0**

at the selected rear boom reference point.

All element positions are measured forward from this datum along the longitudinal centerline of the boom.

For cross-reference with O5, which uses the **front end as its fabrication datum**, the relationship is:

`X_rear = 30.000 in - X_front`

The rear-referenced O3 coordinates and front-referenced O5 drilling coordinates therefore describe the **same physical element locations**.

```text
X = 0

│

▼

REAR ─────────────────────────────────────────────── FRONT

     │          │          │          │

     Elements positioned using absolute X coordinates
```

Absolute positions should be used wherever practical rather than chained dimensions.

This prevents individual measurement errors from accumulating along the boom.

---

### 4.2 Element-Length Convention

Unless otherwise specified:

**Element length = total tip-to-tip conductive length.**

For split driven elements, two dimensions are tracked separately:

- **Overall tip-to-tip span**, including the physical center feed gap.
- **Combined conductive length**, equal to the sum of the two metal halves and excluding the center gap.

Individual driven-element half lengths are documented separately in Section 6.

---

### 4.3 Units

Primary fabrication dimensions should use:

**inches**

Metric equivalents may also be recorded for engineering reference.

Where both are provided:

**1 in = 25.4 mm**

The same unit system should be used consistently within each drawing or fabrication table.

---

## 5. Final Element Schedule

The tables in this section contain the authoritative O3 pre-fabrication dimensions.

> **DIMENSIONAL BASELINE COMPLETE:** The numeric values below are the finalized pre-fabrication dimensions carried forward into O5. O5 uses a front-of-boom datum; this O3 document retains its defined rear-of-boom datum, so the absolute X coordinates below are the mathematically equivalent rear-referenced positions on the same 30.0 in booms.

### 5.1 2 Meter Elements

| ID | Element Type | Total Length | Boom Position X | Notes |
| --- | --- | ---: | ---: | --- |
| 2M-R | Reflector | **41.400 in (1051.6 mm)** | **8.500 in (215.9 mm)** | Rear-most 2 m element |
| 2M-DE | Driven Element | **37.400 in (950.0 mm) overall tip-to-tip span** | **16.500 in (419.1 mm)** | Split at feedpoint; 0.250 in center gap |
| 2M-D1 | Director 1 | **35.400 in (899.2 mm)** | **28.000 in (711.2 mm)** | Forward-most 2 m element |

The finalized 2 m design contains **one director**. No 2M-D2 element is used.

---

### 5.2 70 Centimeter Elements

| ID | Element Type | Total Length | Boom Position X | Notes |
| --- | --- | ---: | ---: | --- |
| 70-R | Reflector | **12.900 in (327.7 mm)** | **9.000 in (228.6 mm)** | Rear-most 70 cm element |
| 70-DE | Driven Element | **12.600 in (320.0 mm) overall tip-to-tip span** | **11.500 in (292.1 mm)** | Split at feedpoint; 0.250 in center gap |
| 70-D1 | Director 1 | **11.900 in (302.3 mm)** | **14.500 in (368.3 mm)** | Director |
| 70-D2 | Director 2 | **11.900 in (302.3 mm)** | **20.500 in (520.7 mm)** | Director |
| 70-D3 | Director 3 | **11.700 in (297.2 mm)** | **26.500 in (673.1 mm)** | Forward-most 70 cm element |

The finalized 70 cm design contains **three directors**. No 70-D4 or 70-D5 elements are used.

---

## 6. Driven-Element Geometry

The driven element is electrically divided at the feedpoint.

Each driven element consists of two conductive halves separated by a controlled physical gap.

### 6.1 2 Meter Driven Element

| Parameter | Dimension |
| --- | ---: |
| Overall tip-to-tip span | **37.400 in (950.0 mm)** |
| Combined conductive length, excluding center gap | **37.150 in (943.6 mm)** |
| Left-half length | **18.575 in (471.8 mm)** |
| Right-half length | **18.575 in (471.8 mm)** |
| Feedpoint gap | **0.250 in (6.35 mm)** |
| Boom position X, rear datum | **16.500 in (419.1 mm)** |
| Equivalent O5 position from FRONT | **13.500 in (342.9 mm)** |

The two halves must remain electrically isolated except through the intended feed/matching system.

---

### 6.2 70 Centimeter Driven Element

| Parameter | Dimension |
| --- | ---: |
| Overall tip-to-tip span | **12.600 in (320.0 mm)** |
| Combined conductive length, excluding center gap | **12.350 in (313.7 mm)** |
| Left-half length | **6.175 in (156.8 mm)** |
| Right-half length | **6.175 in (156.8 mm)** |
| Feedpoint gap | **0.250 in (6.35 mm)** |
| Boom position X, rear datum | **11.500 in (292.1 mm)** |
| Equivalent O5 position from FRONT | **18.500 in (469.9 mm)** |

The feedpoint geometry is especially dimension-sensitive at UHF and should be fabricated carefully.

---

## 7. Element Spacing

Element spacing is determined from the absolute boom coordinates listed in Section 5.

For documentation and checking purposes, adjacent spacing should also be recorded.

### 7.1 2 Meter Spacing

| From | To | Spacing |
| --- | --- | ---: |
| Reflector | Driven Element | **8.000 in (203.2 mm)** |
| Driven Element | Director 1 | **11.500 in (292.1 mm)** |

---

### 7.2 70 Centimeter Spacing

| From | To | Spacing |
| --- | --- | ---: |
| Reflector | Driven Element | **2.500 in (63.5 mm)** |
| Driven Element | Director 1 | **3.000 in (76.2 mm)** |
| Director 1 | Director 2 | **6.000 in (152.4 mm)** |
| Director 2 | Director 3 | **6.000 in (152.4 mm)** |

Absolute X coordinates remain the authoritative O3 fabrication reference.

---

## 8. Boom Geometry

### 8.1 Boom Length

**Final boom length:** **30.000 in (762.0 mm) per boom**

The boom must provide sufficient length for:

- Rear element clearance
- Complete RF element array
- Forward element clearance
- Handheld operating area
- Feedline routing
- Mechanical attachment hardware

---

### 8.2 Boom Centerline

All element positions are referenced along the boom longitudinal centerline.

Elements should be installed approximately perpendicular to the boom unless otherwise documented.

Top view:

```text
REAR                                              FRONT
                                                  DIRECTION OF GAIN ►

       │        │        │        │        │
───────┼────────┼────────┼────────┼────────┼──────── BOOM
       │        │        │        │        │
```

The final O5 drawing will provide a complete scaled or dimensioned mechanical representation.

---

## 9. Antenna Orientation

The antenna orientation must remain unambiguous throughout construction and testing.

### Front

The **director end** of the antenna.

This is the intended primary direction of gain.

### Rear

The **reflector end** of the antenna.

### Left / Right

Left and right are defined while standing behind the antenna and looking toward the director/front end.

This convention should also be used in mechanical drawings and feedpoint documentation.

### 9.1 Dual-Band Element-Plane Orientation

During normal operation, the 2 m and 70 cm element planes are rotated approximately **90° relative to one another**.

The two booms may be rotated toward a parallel/folded configuration for storage and transport.

---

## 10. Tape-Measure Element Construction

The radiating elements are constructed from flexible steel tape-measure material.

This material was selected because it offers:

- Low mass
- Low cost
- High availability
- Mechanical flexibility
- Ability to recover after bending
- Reduced likelihood of permanent element damage during field use
- Compact portable construction

Tape-measure steel should nevertheless be treated as a conductive antenna element whose physical dimensions affect RF performance.

Paint, coating, surface finish, mounting hardware, and nearby conductive materials may affect the final tuned behavior.

---

## 11. Element Alignment

All elements should be installed as consistently as practical.

Target mechanical conditions include:

- Elements perpendicular to the boom
- Element centerlines aligned with the intended mounting plane
- Left and right halves symmetrical where applicable
- Minimal unintended element twist
- Consistent mounting orientation
- No unintended conductive contact between separate driven-element sections

Alignment should be verified before RF testing.

---

## 12. Fabrication Tolerances

Because the antenna operates at VHF and UHF frequencies, dimensional accuracy becomes increasingly important as wavelength decreases.

Recommended fabrication-control targets are:

### 2 Meter Elements

Target element-length accuracy:

**±1/8 in (±3.2 mm) or better**

Target boom-position accuracy:

**±1/8 in (±3.2 mm) or better**

---

### 70 Centimeter Elements

Target element-length accuracy:

**±1/16 in (±1.6 mm) or better**

Target boom-position accuracy:

**±1/16 in (±1.6 mm) or better**

---

### Driven-Element / Feedpoint Geometry

Feedpoint geometry should be fabricated as accurately and symmetrically as practical.

The final dimensions should be measured and recorded rather than assumed to match the cut sheet perfectly.

---

## 13. RF Design Basis

Yagi-Uda antenna behavior results from electromagnetic interaction among the driven element and nearby parasitic elements.

The basic roles are:

### Driven Element

The element directly coupled to the feed system and transmitter/receiver.

### Reflector

Located behind the driven element and generally somewhat longer than the corresponding resonant driven element.

Its interaction with the driven element contributes to suppressing rearward radiation and increasing forward directivity.

### Directors

Located forward of the driven element and generally shorter than the corresponding driven element.

Directors contribute to concentrating the radiation pattern toward the front of the antenna.

The final antenna response depends on the combined effects of:

- Element lengths
- Element spacing
- Element diameter/width
- Conductive material
- Boom interactions
- Driven-element geometry
- Feedpoint geometry
- Feedline behavior
- Nearby objects
- Construction tolerances

Consequently, calculated dimensions represent a design baseline rather than a guarantee of the final resonant response.

O8 testing will determine the actual as-built RF behavior.

---

## 14. Dual-Band Design Considerations

Combining separate 2 m and 70 cm Yagi arrays within a mechanically coupled dual-boom assembly introduces interaction that does not exist when designing each Yagi completely independently.

Potential effects include:

- Mutual coupling between elements
- Resonance shifts
- Feed-system interaction
- Pattern distortion
- Changes in input impedance
- Mechanical-placement constraints

The final design should therefore be evaluated as a complete antenna system rather than assuming each individual element operates independently.

The purpose of O8 testing is to measure the resulting antenna rather than relying solely on theoretical element dimensions.

---

## 15. Feedpoint Design Interface

Detailed electrical construction of the feed and matching system is controlled by:

**O7 — Construct Feed & Matching System**

O3 defines the physical interface required for that system.

The design must provide:

- A clearly identified driven-element location
- Electrical isolation between driven-element halves where required
- Mechanical access to the feedpoint
- Space for feed and matching components
- A route for coaxial feedline
- Mechanical strain-relief provisions

Nominal radio-system feed impedance:

**50 Ω**

Planned O7 feed/matching baseline:

| Parameter | 2 m | 70 cm |
| --- | ---: | ---: |
| Driven-element center gap | **0.250 in (6.35 mm)** | **0.250 in (6.35 mm)** |
| Feedline | **RG-58, 50 Ω** | **RG-58, 50 Ω** |
| Matching network | **8.500 in (215.9 mm) #12 AWG solid-copper shunt hairpin** | **Direct feed; no separate matching element** |
| Coax choke | **6 turns RG-58 around boom** | **4 turns RG-58 around boom** |
| Antenna-side external interface | **BNC** | **BNC** |

Final impedance and SWR will be experimentally measured during O8.

---

## 16. Feedline Routing Interface

The coaxial feedline should be routed so that it:

- Does not significantly deform antenna elements
- Does not interfere with manual aiming
- Does not place mechanical load on the feedpoint
- Avoids unnecessarily sharp bends
- Remains mechanically secured
- Minimizes unintended interaction with the RF structure where practical

The exact routing arrangement will be finalized during O7.

---

## 17. As-Designed Configuration

This document represents the antenna's:

**AS-DESIGNED / PRE-FABRICATION CONFIGURATION**

Three separate configurations should eventually exist in the repository.

### As-Designed

The dimensions contained in this O3 document before construction.

### As-Built

The dimensions physically measured after O6/O7 construction and before RF tuning.

### As-Tuned

The final dimensions and feed configuration resulting from O8 experimental tuning.

These configurations should not be conflated.

This distinction allows later analysis of how fabrication and tuning affected the original engineering design.

---

## 18. Dimensional Verification

Before O3 is considered complete, verify:

- Element IDs are unique
- No reflector/director labels are reversed
- Every element has a length
- Every element has an absolute boom position
- Driven elements have documented split dimensions
- Feedpoint locations are unambiguous
- Front/rear orientation is defined
- Units are consistent
- Boom positions increase in the intended forward direction
- Adjacent spacing values agree with absolute X coordinates
- Dimensions are compatible with the intended boom length
- 2 m and 70 cm elements can coexist mechanically
- No obvious transcription errors exist

A second dimensional check should be performed when producing the O5 mechanical drawing.

---

### 18.1 O5 Front-Datum Fabrication Cross-Reference

The following values are included only to prevent a datum-conversion mistake during fabrication. **O3 remains rear-referenced; O5 remains the master bench cut/drill sheet.**

### 2 m — Positions Measured from FRONT

| Element | Position from FRONT |
| --- | ---: |
| Director 1 | **2.000 in (50.8 mm)** |
| Driven Element | **13.500 in (342.9 mm)** |
| Reflector | **21.500 in (546.1 mm)** |

### 70 cm — Positions Measured from FRONT

| Element | Position from FRONT |
| --- | ---: |
| Director 3 | **3.500 in (88.9 mm)** |
| Director 2 | **9.500 in (241.3 mm)** |
| Director 1 | **15.500 in (393.7 mm)** |
| Driven Element | **18.500 in (469.9 mm)** |
| Reflector | **21.000 in (533.4 mm)** |

---

## 19. Design Revision Control

The original O3 dimensional baseline should remain preserved in Git history.

If the RF design changes before fabrication:

1. Modify this document.
2. Record the reason for the change.
3. Increment the revision.
4. Commit the change with a descriptive Git commit message.

Example:

```text
Revise 70 cm director spacing before fabrication
```

Once fabrication begins, physical differences should generally be recorded as **as-built deviations** rather than retroactively rewriting the original design.

---

## 20. Design Change Log

| Revision | Date | Description |
| --- | --- | --- |
| Rev. A                  | 2026-08-24 | Initial formal O3 design documentation; finalized dimensional baseline populated from O3/O5 design; Markdown formatting, boom-orientation diagram, dual-boom terminology, and O7 baseline wording corrected |
|                         |            |                                        |

Future revisions should be added without deleting previous entries.

---

## 21. O3 Acceptance Checklist

The O3 issue may be closed when:

- [x] Every 2 m antenna element has a defined final length
- [x] Every 70 cm antenna element has a defined final length
- [x] Every element has a defined absolute boom position
- [x] Driven-element geometries are documented
- [x] Feedpoint locations are defined
- [x] Element spacing has been verified
- [x] Antenna orientation is clearly defined
- [x] Measurement units are consistent
- [x] Fabrication tolerances are documented
- [x] Boom dimensions are documented
- [x] Dimensional tables have been checked for transcription errors
- [x] O3 design agrees with the design used for O4 and O5
- [ ] This revised `docs/design.md` has been committed to the GitHub repository

> **Commit note:** Check the final box only after this revised file has actually been committed to the repository.

---

## 22. Related Documents

This document should eventually be accompanied by:

```text
docs/

├── design.md

├── bill-of-materials.md

├── fabrication.md

├── feed-system.md

├── testing.md

└── final-report.md

drawings/

├── antenna-layout/

├── mechanical/

└── feed-system/

data/

├── swr/

├── terrestrial-tests/

└── satellite-tests/
```

The following project phases depend directly on this document:

- O4 — Finalize Bill of Materials & Sourcing
- O5 — Create Mechanical Drawing & Cut Sheet
- O6 — Fabricate and Assemble Antenna
- O7 — Construct Feed & Matching System
- O8 — Perform Initial RF Testing & Tuning
- O9 — Perform Field Performance Testing
- O10 — Perform Satellite / ISS Field Validation

---

## 23. Engineering Intent

The dimensions contained in this document should not be treated as successful merely because the completed antenna can transmit or receive.

The complete engineering process requires comparison between:

**Predicted design**

↓

**Fabricated antenna**

↓

**Measured RF response**

↓

**Tuned configuration**

↓

**Terrestrial directional performance**

↓

**Satellite / ISS operational performance**

The final project should therefore demonstrate not only that an antenna was constructed, but how the physical design translated into measured and operational RF behavior.

---

**End of O3 Design Document**
