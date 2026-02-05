# In-vacuum Z-Stage and Test Visualization Metrology of Tin–H Interactions in the EUV Source  
### Senior Design Capstone — ASML × SDSU

---

## Overview
This repository documents the design, analysis, and implementation of a **hybrid visualization subsystem** developed for an Extreme Ultraviolet (EUV) source test vessel used to study tin–hydrogen (Sn–H) interactions.

During testing, material samples are exposed to hydrogen radicals under vacuum, producing physical and thermal effects such as **tin spitting, surface modification, blister formation, and localized heating**. Continuous monitoring of these effects is critical, yet historically limited by fixed external cameras, obstructed operator viewports, and the need to vent the chamber for inspection.

To address these limitations, this project integrates:
- an **internal digital camera** mounted inside the vacuum vessel for high-resolution visual monitoring, and  
- an **external thermal camera** viewing through a **zinc selenide (ZnSe) infrared viewport** for temperature measurement.

Together, these systems provide continuous optical and thermal access to samples without venting the chamber or obstructing operator visibility. The visualization system will also work in parallel with a stage system and as a whole makes up the project which is apart of the **SDSU Mechanical Engineering Senior Design Capstone Program** and is sponsored by **ASML (Extreme Ultraviolet Group, San Diego)**.

### System Level Design
<p align="center">
  <img src="images/sld.png" width="700"><br>
  <em>Figure – System-level diagram showing internal digital imaging, external thermal imaging, and integration with the Z-stage inside the EUV test vessel.</em>
</p>

---

## Visualization Subsystem
The visualization subsystem provides continuous monitoring of samples mounted on an externally adjustable in-vacuum Z-stage. While the Z-stage controls sample position relative to the hydrogen radical source, the camera subsystem enables **real-time visual and thermal observation** throughout testing.

<p align="center">
  <img src="images/ZStage_Setup.png" width="375"><br>
  <em>Figure – Internal view of the Porcupine vacuum vessel showing Z-stage placement and visualization system geometry.</em>
</p>

---

### Camera System Concept
The visualization subsystem consists of:
- an **internal digital camera** for high-resolution visual inspection of surface phenomena, and  
- an **external thermal camera** viewing through an infrared-transparent viewport.

This hybrid approach was selected to balance image quality, vacuum compatibility, and system reliability.

Key design drivers included:
- Vacuum compatibility and low-outgassing materials  
- Structural rigidity and repeatable positioning  
- Optical alignment and field-of-view constraints  
- Protection from tin vapor and debris  
- Compatibility with existing vessel geometry and feedthroughs  

<p align="center">
  <img src="images/Picture4.png" width="375"><br>
  <em>Figure – Internal digital camera assembly used for high-resolution visualization of test samples.</em>
</p>

---

### Camera Mounting Strategy (ID Clamp–Based)
A non-invasive mounting approach was required to avoid modifying or loading critical vacuum hardware. The internal digital camera system is mechanically supported using **Mitee-Bite internal diameter (ID) expansion clamps**, allowing rigid attachment to existing cylindrical features inside the vessel.

This strategy was selected because it:
- Provides **high positional repeatability** without welding or drilling  
- Transfers load directly into the vessel wall rather than CF flanges  
- Allows installation and removal without permanent modification  
- Enables precise alignment within tight spatial constraints  

<p align="center">
  <img src="images/Screenshot%202026-01-31%20183246.jpg" width="375"><br>
  <em>Figure – ID expansion clamp interface used to mount the internal camera rail system to existing vessel geometry.</em>
</p>

---

### ID Clamp Interface: Structural Validation
The ID clamp mounting approach required validation because the camera system is supported entirely through frictional contact with the vessel’s internal cylindrical features. This interface carries both the weight of the camera assembly and off-axis moments introduced by camera standoff.

Finite element analysis was performed to evaluate clamp behavior under conservative load cases, including gravitational loading and induced moments. Boundary conditions were defined to represent contact between the expanded clamp and the vessel wall.

Analysis results confirmed that the clamp-based interface provides sufficient stiffness and safety margin for operational use without risk of slip or localized overstress of the vessel wall.

<p align="center">
  <img src="images/Picture3.jpg" width="375"><br>
  <em>Figure – Load case and boundary conditions used for structural validation of the ID clamp interface.</em>
</p>

<p align="center">
  <img src="images/Picture2.png" width="425"><br>
  <em>Figure – Finite element analysis results showing stress distribution in the ID clamp under worst-case loading.</em>
</p>

---

## Thermal Imaging and Infrared Viewport

### Thermal Viewport: Why It Is Required
In addition to visual inspection, **thermal monitoring** of samples is required to understand tin–hydrogen interaction dynamics during energetic events such as spitting and surface reactions.

Standard vacuum viewports are opaque to long-wave infrared wavelengths. To enable thermal imaging:
- a **zinc selenide (ZnSe) viewport** was selected for its infrared transmissivity,  
- the viewport allows an external **FLIR thermal camera** to image the sample region without introducing electronics into the vacuum, and  
- the external mounting approach reduces contamination risk and simplifies integration.

ZnSe was selected over germanium due to **availability, cost, and equivalent optical performance** for the FLIR E75 wavelength range, as validated during design trade studies.

<p align="center">
  <img src="images/Screenshot%202026-01-31%20171220.png" width="375"><br>
  <em>Figure – Exploded view of the reducer flange and zinc selenide (ZnSe) viewport assembly used for thermal imaging.</em>
</p>

---

## Manufacturing Documentation

### Drawings and Assembly
Manufacturing drawings were produced for all custom camera mounting components, including:
- ID clamp interface features  
- Gimbal and rail mounting adapters  
- Viewport and reducer interfaces  

Drawings reflect vacuum-compatible tolerancing, alignment requirements, and DFMA considerations.

<p align="center">
  <img src="images/Screenshot%202026-01-31%20173111.png" width="375"><br>
  <em>Figure – Example manufacturing drawing for a custom camera mounting interface component.</em>
</p>

---

## Subsystem Ownership and Contributions

Subsystem ownership was assigned to ensure technical accountability and depth of design.

### Visualization and Camera Subsystem  
**Primary Owner: Tomas Puente**

Responsibilities included:
- System-level concept development for hybrid visualization  
- Integration of digital and thermal imaging systems  
- Mechanical design of camera mounting hardware  
- Optical alignment and field-of-view analysis  
- Contamination mitigation and lens protection strategy  
- Integration with the Z-stage experimental platform  

---

### ID Clamp–Based Mounting Technique  
**Primary Owner: Tomas Puente**

- Selection of Mitee-Bite ID clamps as a non-invasive mounting solution  
- Interface design leveraging existing vessel geometry  
- Structural validation of clamp-based mounting under operational loads  
- Creation of manufacturing drawings and tolerancing strategy  

---

### Thermal Viewport and IR Imaging Integration  
**Primary Owner: Tomas Puente**

- Selection and justification of ZnSe viewport material  
- Mechanical integration of reducer, viewport, and thermal camera  
- Trade study between germanium and ZnSe optics  
- Validation of optical access without vacuum intrusion  
- Alignment and standoff considerations for thermal imaging  

---

## Current Project Status
The visualization subsystem has completed **design, analysis, and documentation**. The project is currently entering the **manufacturing and assembly phase**, with custom mounting components being fabricated and procured.

This repository will be **updated throughout the semester** as manufacturing, assembly, integration, and testing progress.
