# **Tape Measure Satellite Yagi**

A portable dual-band **2 m / 70 cm directional Yagi antenna** constructed using tape measure elements for amateur radio satellite, ISS, and field communications.

This project is intended as both a practical amateur radio antenna and an RF engineering project covering antenna design, mechanical fabrication, impedance matching, measurement, testing, and field validation.

## **Project Status**

**Status:** Design / Pre-fabrication

The antenna design and build procedure are currently being developed. Fabrication, RF characterization, and satellite field testing will follow.

## **Overview**

The Tape Measure Satellite Yagi is a lightweight, portable directional antenna designed primarily for handheld amateur radio satellite operation.

The antenna uses flexible steel tape measure elements mounted to a lightweight boom. Tape measure elements are useful for portable antennas because they are inexpensive, easy to cut, resilient, and can bend when struck without permanently damaging the antenna.

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

### **O3 — Detailed Antenna Design**

Define the final electromagnetic geometry of the antenna, including:

* Element lengths  
* Element spacing  
* Driven element geometry  
* Reflector geometry  
* Director geometry  
* Boom layout

### **O4 — Bill of Materials**

Develop the complete component list for construction, including:

* Tape measure material  
* Boom  
* Fasteners  
* Element mounts  
* Coaxial cable  
* RF connectors  
* Feedpoint components  
* Electrical hardware

### **O5 — Mechanical Drawing & Cut Sheet**

Produce fabrication drawings containing:

* Element dimensions  
* Boom dimensions  
* Element locations  
* Hole locations  
* Mechanical mounting details  
* Material cut lengths

### **O6 — Fabrication Procedure**

Document the complete construction process from raw materials through final mechanical assembly.

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

## **Repository Structure**

The repository is planned to use the following structure:

TapeMeasureSatelliteYagi/  
│  
├── README.md  
│  
├── docs/  
│   ├── requirements.md  
│   ├── design.md  
│   ├── billofmaterials.md  
│   ├── fabrication.md  
│   ├── feedsystem.md  
│   ├── testing.md  
│   └── finalreport.md  
│  
├── drawings/  
│   ├── antennalayout/  
│   ├── mechanical/  
│   └── feedsystem/  
│  
├── data/  
│   ├── swr/  
│   ├── terrestrialtests/  
│   └── satellitetests/  
│  
├── images/  
│   ├── fabrication/  
│   ├── completedantenna/  
│   └── fieldtesting/  
│  
└── LICENSE

The repository structure may change as the project develops.

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
* Improved collapsible boom  
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
**Current Phase:** Design and Pre-Fabrication
