# **Tape Measure Satellite Yagi**

A portable dual-band **2 m / 70 cm directional Yagi antenna** constructed using tape measure elements for amateur radio satellite, ISS, and field communications.

This project is intended as both a practical amateur radio antenna and an RF engineering project covering antenna design, mechanical fabrication, impedance matching, measurement, testing, and field validation.

## **Project Status**

**Status:** Controlled pre-fabrication design; technical drawings underway.

The O3–O6 design, materials, cut sheet, and fabrication procedure are at Rev. L. No as-built dimensions or RF test results are recorded in this repository yet. Feed construction (O7), calibrated RF testing (O8), and field validation remain future stages.

## **Overview**

The Tape Measure Satellite Yagi is a lightweight, portable directional antenna designed primarily for handheld amateur radio satellite operation.

The antenna uses flexible steel tape measure elements on two separate, parallel PVC booms: a three-element 2 m array and a five-element 70 cm array. The element planes are orthogonal in the operating assembly, and each band has its own feedline. Tape measure elements are useful for portable antennas because they are inexpensive, easy to cut, and resilient.

The project is designed around the amateur radio:

* **2 meter band — 144–148 MHz**  
* **70 centimeter band — 420–450 MHz**

These bands are commonly used for amateur radio satellites and ISS amateur radio operations.

The completed antenna is intended to be manually aimed while tracking satellites across the sky.

## **Project Objectives**

The primary objectives of this project are to:

* Design and construct a functional portable VHF/UHF Yagi antenna.  
* Support amateur radio satellite and ISS operations.  
* Learn practical antenna design and RF engineering principles.  
* Develop a repeatable mechanical fabrication process.  
* Construct and test an RF feed and matching system.  
* Measure antenna impedance and SWR.  
* Evaluate directional performance in the field.  
* Compare antenna performance against a standard handheld radio antenna.  
* Perform real-world satellite and/or ISS reception tests.  
* Document the complete engineering process.  
* Produce a project suitable for inclusion in an electrical/RF engineering portfolio.

## **Design Concept**

The antenna is based on the Yagi-Uda antenna architecture.

A Yagi typically consists of:

* **Reflector**  
* **Driven element**  
* **One or more directors**

These parasitic elements interact electromagnetically with the driven element to produce a directional radiation pattern.

The antenna therefore concentrates more RF energy in one direction than a typical omnidirectional handheld antenna.

For satellite operation, this provides several advantages:

* Increased forward gain  
* Improved reception of weak satellite signals  
* Rejection of some unwanted signals outside the antenna's primary direction  
* Ability to manually track a spacecraft during a pass

## **Why Tape Measure Elements?**

Instead of rigid aluminum tubing, this antenna uses sections of steel measuring tape as radiating elements.

Tape measure construction offers several advantages for a portable antenna:

* Low cost  
* Lightweight construction  
* Easily obtainable materials  
* Flexible elements  
* Reduced chance of element damage during transport  
* Compact field deployment  
* Easy experimentation with element length

The flexible elements can bend when they strike an object and return approximately to their original position, making the design particularly useful for field operation.

## **Intended Applications**

The antenna is being designed for:

### **AmateurRadio Satellites**

Manual tracking of Low Earth Orbit amateur radio satellites operating in the 2 m and 70 cm bands.

### **International Space Station**

Reception and, where appropriate and authorized, amateur radio communication involving the ISS amateur radio station.

### **Terrestrial Amateur Radio**

The antenna may also be evaluated for:

* Simplex VHF/UHF communication  
* Direction finding  
* Repeater experimentation  
* Field communications  
* Signal strength comparison  
* Antenna pattern experimentation

## **Engineering Process**

Development of the antenna is divided into several engineering stages.

### **O3 — [Antenna Design and Dimensions](docs/design.md)**

Define the final electromagnetic geometry of the antenna, including:

* Element lengths  
* Element spacing  
* Driven element geometry  
* Reflector geometry  
* Director geometry  
* Boom layout

### **O4 — [Bill of Materials and Sourcing](docs/bill-of-materials.md)**

Develop the complete component list for construction, including:

* Tape measure material  
* Two PVC booms  
* Fasteners  
* Element mounts  
* Coaxial cable  
* RF connectors  
* Feedpoint components  
* Electrical hardware

### **O5 — [Mechanical Drawing and Cut Sheet](docs/cut-sheet.md)**

Control the element and boom dimensions, station and hole locations, mechanical fit, material cuts, inspection limits, and as-built measurement forms. Technical drawings use this baseline and are added as separate deliverables.

### **O6 — [Fabrication and Assembly Procedure](docs/fabrication.md)**

Control the construction process from material inspection and test coupons through final mechanical assembly and the handoff to O7.

### **O7 — Feed & Matching System**

Design and construct the RF feedpoint and impedance-matching system.

This stage includes:

* Driven element connection  
* Coaxial feed arrangement  
* Feedline routing  
* Strain relief  
* Impedance matching  
* RF connector installation

### **O8 — Calibration & Initial RF Testing**

Perform initial electrical characterization of the completed antenna.

Testing will include:

* Electrical continuity  
* Shortcircuit inspection  
* Feedline verification  
* SWR measurement  
* Resonance measurement  
* Feedpoint adjustment

### **O9 — Field Performance Testing**

Evaluate antenna performance under real operating conditions.

Testing may include:

* Directionality testing  
* Front-to-back comparison  
* Signal strength measurements  
* Comparison with an HT whip antenna  
* Terrestrial signal tests  
* Repeatability testing

### **O10 — Satellite / ISS Field Validation**

Perform real-world validation using satellite passes.

Testing will evaluate:

* Satellite acquisition  
* Signal strength  
* Manual tracking behavior  
* Polarization effects  
* Usable portion of each pass  
* Comparison against a standard handheld antenna  
* Overall field usability

## **Planned Testing**

RF measurements will be recorded throughout the project rather than relying solely on whether the antenna appears to work.

Planned measurements include:

| Test | Purpose |
| ----- | ----- |
| Continuity Test | Verify electrical connections |
| ShortCircuit Test | Detect feedpoint or coax faults |
| SWR Sweep | Evaluate impedance match |
| Resonant Frequency | Determine actual antenna resonance |
| Signal Comparison | Compare against an HT antenna |
| Directionality Test | Verify directional behavior |
| Front-to-Back Test | Evaluate signal rejection behind antenna |
| Satellite Reception | Validate realworld performance |
| Satellite Tracking | Evaluate handling and pointing behavior |

## **Field Validation**

Satellite testing will use predicted orbital passes and known amateur radio satellite signals.

During each pass, observations may include:

* Satellite  
* Date  
* Acquisition of Signal (AOS)  
* Maximum elevation  
* Loss of Signal (LOS)  
* Operating frequency  
* Radio configuration  
* Antenna orientation  
* Signal strength  
* Audio quality  
* Tracking difficulty  
* Polarization changes  
* Successful reception or communication  
* Environmental conditions

These observations will be recorded for later analysis.

## **Repository Files**

The current controlled files are:

| Stage | File | Purpose |
|---|---|---|
| O3 | [docs/design.md](docs/design.md) | Design geometry, interfaces, and acceptance criteria |
| O4 | [docs/bill-of-materials.md](docs/bill-of-materials.md) | Materials, quantities, sourcing, and receiving checks |
| O5 | [docs/cut-sheet.md](docs/cut-sheet.md) | Cut list, layout, tolerances, hold points, and as-built forms |
| O6 | [docs/fabrication.md](docs/fabrication.md) | Mechanical build sequence and quality gates |
| M-01 | [PDF](drawings/M-01-overall-assembly.pdf) · [editable SVG](drawings/M-01-overall-assembly.svg) | Overall assembly, datum stations, boom orientation, and key clearances |
| M-02 | [PDF](drawings/M-02-2m-boom-layout.pdf) · [editable SVG](drawings/M-02-2m-boom-layout.svg) | 2 m boom stations, hole layout, datums, and drilling checks |
| M-03 | [PDF](drawings/M-03-70cm-boom-layout.pdf) · [editable SVG](drawings/M-03-70cm-boom-layout.svg) | 70 cm boom stations, hole layout, datums, and drilling checks |
| M-04 | [PDF](drawings/M-04-parts-cut-schedule.pdf) · [editable SVG](drawings/M-04-parts-cut-schedule.svg) | Finished parts, cut tolerances, and tape-steel stock allowance |
| M-05 | [PDF](drawings/M-05-passive-element-mounting.pdf) · [editable SVG](drawings/M-05-passive-element-mounting.svg) | Supported 2 m and tape-only 70 cm passive mounting and retention checks |
| M-06 | [PDF](drawings/M-06-split-driven-element-mounting.pdf) · [editable SVG](drawings/M-06-split-driven-element-mounting.svg) | Split driven mounting, hidden-gap witness method, and final retention sequence |
| M-07 | [PDF](drawings/M-07-feed-node-hardware.pdf) · [editable SVG](drawings/M-07-feed-node-hardware.svg) | Feed-node hole placement, hardware stack, electrical assignments, and assembly checks |
| M-08 | [PDF](drawings/M-08-dual-boom-retention.pdf) · [editable SVG](drawings/M-08-dual-boom-retention.svg) | J1/J2 separator pads and ties, boom orientation, and assembled clearance checks |
| M-09 | [PDF](drawings/M-09-close-reflector-clearance.pdf) · [editable SVG](drawings/M-09-close-reflector-clearance.svg) | Close-reflector station separation and physical edge-clearance inspection |
| E-01 | [PDF](drawings/E-01-electrical-feed-schematic.pdf) · [editable SVG](drawings/E-01-electrical-feed-schematic.svg) | Independent 2 m hairpin and 70 cm direct feeds, BNC interfaces, and expected DC checks |
| E-02 | [PDF](drawings/E-02-2m-hairpin-detail.pdf) · [editable SVG](drawings/E-02-2m-hairpin-detail.svg) | 2 m hairpin starting blank, U geometry, orientation, and O7/O8 measurement records |
| E-03 | [PDF](drawings/E-03-coax-and-ferrite-routing.pdf) · [editable SVG](drawings/E-03-coax-and-ferrite-routing.svg) | Independent rearward coax paths, ferrite groups, O7 feed-entry gate, and routing checks |

All four controlled documents are Rev. L. The technical drawing set now includes M-01 through M-09 and E-01 through E-02 Rev. A, plus E-03 Rev. B, issued for review. O7 feed and matching documentation, O8 test records, build photographs, and field data will be added as those phases are completed.

## **Documentation**

The project will document both successful and unsuccessful results.

Design changes, tuning adjustments, fabrication problems, and unexpected measurements will be retained where useful because they provide information about the engineering process rather than only the final product.

Major design revisions will be tracked through GitHub.

## **Tools & Equipment**

Construction and testing may require equipment including:

* Soldering equipment  
* Wire cutters  
* Measuring tools  
* Drill and drill bits  
* Hand tools  
* Multimeter  
* SWR meter and/or antenna analyzer  
* VHF/UHF amateur radio  
* Coaxial adapters  
* Computer or mobile satellite tracking software

Additional equipment will be documented as the project progresses.

## **Safety**

RF, electrical, and mechanical safety procedures should be followed during construction and operation.

Particular attention should be given to:

* Sharp edges on cut tape measure elements  
* Eye protection during cutting and drilling  
* Safe soldering practices  
* RF exposure limits  
* Overhead electrical conductors  
* Lightning and severe weather

**Never deploy or operate an antenna where it could contact overhead power lines. **

Portable antennas should be lowered and moved indoors when lightning is present in the area.

## **Amateur Radio Operation**

Transmission using this antenna must comply with the applicable amateur radio regulations, frequency allocations, operating privileges, and satellite operating requirements of the operator's jurisdiction.

Satellite frequencies and operating modes can change. Current satellite documentation should always be checked before transmitting.

## **Future Development**

Possible future improvements include:

* Antenna element optimization  
* Improved impedance matching  
* Additional gain measurements  
* Radiation pattern characterization  
* Computer modeling  
* Automated SWR data collection  
* Satellite pass logging software  
* Rotator or pointing assistance system  
* More compact transport configuration  
* 3D-printed mechanical components  
* Integration with a portable field communications system

## **Project Goals Beyond the Antenna**

This project is also intended as a practical introduction to several areas of electrical and RF engineering:

* Electromagnetic propagation  
* Antenna resonance  
* Impedance  
* Standing Wave Ratio  
* Transmission lines  
* Directional antenna patterns  
* RF measurement  
* VHF/UHF communications  
* Satellite communications  
* Mechanical/electrical integration  
* Engineering documentation  
* Experimental validation

The goal is not simply to construct an antenna that works, but to understand **why it works, measure how well it works, identify its limitations, and document the complete engineering process.**

---

**Project:** Tape Measure Satellite Yagi  
**Type:** Amateur Radio / RF Engineering  
**Bands:** 2 m / 70 cm  
**Primary Application:** Amateur radio satellite and ISS operation  
**Current Phase:** Pre-fabrication; technical drawings underway
