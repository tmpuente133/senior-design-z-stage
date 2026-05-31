# Hybrid Digital and Thermal Visualization System for In-Vacuum Tin–Hydrogen Interaction Testing
### SDSU Mechanical Engineering Senior Design Capstone — Sponsored by ASML EUV Group

---

## Project Overview

This repository documents the design, analysis, fabrication, integration, and validation of a hybrid visualization subsystem developed for ASML’s Extreme Ultraviolet (EUV) source test vessel.

The project was developed as part of the **San Diego State University Mechanical Engineering Senior Design Program** in collaboration with **ASML’s EUV Group** in San Diego.

The visualization subsystem was designed to improve observation capabilities during vacuum testing of tin–hydrogen (Sn–H) interactions. These experiments involve energetic surface phenomena such as:

- Tin spitting
- Surface modification
- Blister formation
- Localized heating

Historically, operators relied on fixed external cameras and limited viewport visibility, restricting observation quality and requiring chamber venting for inspection.

To address these limitations, the system integrates:

- an internally mounted digital imaging subsystem for high-resolution visual observation, and
- an externally mounted thermal imaging subsystem utilizing a zinc selenide (ZnSe) infrared viewport.

Together, these systems provide continuous optical and thermal monitoring without breaking vacuum or obstructing operator visibility.

---

### System Level Design
<p align="center">
  <img src="https://github.com/tmpuente133/senior-design-z-stage/blob/main/images/sld.png" width="700"><br>
  <em>Figure – System-level diagram showing internal digital imaging, external thermal imaging, and subsystem integration inside the EUV test vessel.</em>
</p>

---

# Digital Visualization Subsystem

## Overview

The digital visualization subsystem was designed to provide real-time, unobstructed imaging of experimental coupons during testing inside ASML’s Porcupine vacuum vessel.

The system needed to satisfy several engineering constraints:

- Vacuum compatibility
- Non-invasive integration
- Structural rigidity
- Repeatable positioning
- Adjustable articulation
- Compatibility with existing vessel geometry
- Minimal obstruction of surrounding hardware

The final design utilizes an internally mounted camera assembly supported by ID expansion clamps and an adjustable 80/20 rail system.

---

### Digital Camera System Overview
<p align="center">
  <img src="https://github.com/tmpuente133/senior-design-z-stage/blob/main/images/digitalcameracadfullintegration.png" width="500"><br>
  <em>Figure – Internal view of the vacuum vessel showing the positioning and integration of the digital camera subsystem.</em>
</p>

---

## Digital Camera Design Trade Studies

<table>
<tr>
<td width="55%" valign="top">

Several camera positioning architectures were evaluated during concept development.

### Concepts Evaluated

- External tripod-mounted camera  
- Internal articulating arm  
- Internal scissor-lift mechanism  
- Internal 80/20 rail system  

Evaluation criteria included:

- Articulation performance  
- Structural rigidity  
- Reliability  
- Space envelope  
- Manufacturability  
- Integration complexity  
- Cost  

The internally mounted **80/20 rail system** was selected due to its balance of:

- Rigidity  
- Positioning capability  
- Modular adjustability  
- Integration compatibility  
- Reliability inside the vacuum environment  

</td>

<td width="45%" valign="top">

<p align="center">
  <img src="https://raw.githubusercontent.com/tmpuente133/senior-design-z-stage/main/images/Screenshot%202026-05-23%20174048.png" width="100%"><br>
  <em>Figure – Four potential camera mounting architectures evaluated during subsystem concept development.</em>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/tmpuente133/senior-design-z-stage/main/images/digicammountingtradestudy.png" width="100%"><br>
  <em>Figure – Weighted decision matrix used to evaluate and select the final digital camera mounting architecture.</em>
</p>

</td>
</tr>
</table>

---

## Camera Mounting Strategy

A non-invasive mounting solution was required to avoid modifying critical vacuum vessel hardware.

The digital camera system interfaces with the vessel using **Mitee-Bite ID expansion clamps**, which mount directly to existing cylindrical geometry inside the chamber.

### Advantages of the ID Clamp System

- No permanent chamber modification
- High positional repeatability
- Strong radial clamping force
- Easy installation and removal
- Compact integration footprint
- Direct load transfer into vessel geometry

The mounting strategy allows stable positioning of the camera assembly while maintaining flexibility for future experimental configurations.

---

### ID Clamp Mounting Interface
<p align="center">
  <img src="https://github.com/tmpuente133/senior-design-z-stage/blob/main/images/Screenshot%202026-01-31%20183246.jpg" width="450"><br>
  <em>Figure – ID expansion clamp interface used to rigidly mount the digital camera rail system to existing vessel geometry.</em>
</p>

---

## Final Digital Camera Design

The final digital imaging subsystem consists of:

- Dual ID expansion clamps
- 80/20 extrusion rail assembly
- Adjustable camera carriage
- Commercial off-the-shelf gimbal
- Adjustable articulation geometry

The system provides stable imaging throughout the vessel workspace while remaining easily adjustable for future testing configurations.

---

### Final Digital Camera CAD Assembly
<p align="center">
  <img src="https://github.com/tmpuente133/senior-design-z-stage/blob/main/images/digitalcamcad.jpg" width="600"><br>
  <em>Figure – Final CAD assembly of the internally mounted digital camera subsystem.</em>
</p>

### Integrated Digital Camera System
<p align="center">
  <img src="https://github.com/tmpuente133/senior-design-z-stage/blob/main/images/digitalcamintegration.png" width="600"><br>
  <em>Figure – Fully integrated digital imaging subsystem installed inside the vacuum vessel.</em>
</p>

---

## Digital Camera Fabrication and Assembly

The subsystem progressed through prototyping, fabrication, and full in-vacuum integration.


### Raw stock 
- Will be reduced based off of CMM measurement of vessel geometry

 <p align="center">
  <img src="https://raw.githubusercontent.com/tmpuente133/senior-design-z-stage/main/images/rawstock.png" width="450"><br>
  <em>Figure – Raw Mitee-Bite stock used for fabrication of custom ID expansion clamps prior to final machining and sizing operations.</em>
</p>

---

### 3D printed prototype validation
<p align="center">
  <img src="https://raw.githubusercontent.com/tmpuente133/senior-design-z-stage/main/images/Testfit.png" width="46%">
  <img src="https://raw.githubusercontent.com/tmpuente133/senior-design-z-stage/main/images/testfit2.png" width="42%">
</p>

<p align="center">
  <em>
    Figure – 3D printed prototype validation and physical fit testing performed to verify ID clamp sizing and vessel compatibility prior to machining final hardware.
  </em>
</p>

---
  
### Turning and tapping of ID clamp hardware
<p align="center">
  <img src="https://raw.githubusercontent.com/tmpuente133/senior-design-z-stage/main/images/lathegif.gif" width="30%">
  <img src="https://raw.githubusercontent.com/tmpuente133/senior-design-z-stage/main/images/lathepic.png" width="23%">
</p>

<p align="center">
  <em>
    Figure – Machining operations and motion testing of the custom ID clamp and digital camera subsystem during fabrication and integration.
  </em>
</p>

---
  
### Rail assembly integration

<p align="center">
  <img src="https://github.com/tmpuente133/senior-design-z-stage/blob/main/images/full%20digicam%20assembly.png" width="700"><br>
  <em>Figure – Prototype validation, machining operations, and final assembly activities for the digital camera subsystem.</em>
</p>

Rapid prototyping significantly reduced manufacturing risk and prevented costly rework of long lead-time hardware.

---

## Digital Camera Validation Testing

Validation testing confirmed:

- Full articulation without collision
- Stable imaging throughout system motion
- No clamp slippage under excessive loading
- Sufficient field-of-view coverage
- Compatibility with surrounding vessel hardware

The final subsystem successfully met all digital visualization performance requirements.

---

### Digital Camera Installation Validation

<p align="center">
  <img src="https://raw.githubusercontent.com/tmpuente133/senior-design-z-stage/main/images/IDclampfitmentverifcation.png" width="36%">
  <img src="https://raw.githubusercontent.com/tmpuente133/senior-design-z-stage/main/images/fitmentverifiation.gif" width="60%">
</p>

<p align="center">
  <em>
    Figure – ID clamp fitment verification and subsystem motion validation performed during integration testing inside the vacuum vessel.
  </em>
</p>

---

# Thermal Imaging Subsystem

## Overview

In addition to optical visualization, thermal monitoring of test coupons was required to better understand tin–hydrogen interaction behavior during energetic surface events.

Because standard vacuum viewports are opaque to long-wave infrared radiation, a dedicated infrared imaging solution was developed.

The thermal subsystem consists of:

- FLIR E75 thermal camera
- Zinc selenide (ZnSe) infrared viewport
- Custom thermal camera mounting assembly
- Integrated reducer flange interface

The system enables non-invasive thermal monitoring without introducing electronics into the vacuum chamber.

---

### Thermal Imaging System Overview
<p align="center">
  <img src="https://github.com/tmpuente133/senior-design-z-stage/blob/main/images/flirintegratedredbox.png" width="500"><br>
  <em>Figure – Thermal imaging subsystem showing FLIR integration and ZnSe viewport positioning relative to the vacuum vessel.</em>
</p>

---

## Thermal Camera Trade Studies

Several infrared viewport materials and mounting strategies were evaluated during subsystem development.

### Viewport Material Study

Materials considered included:

- Germanium
- Zinc Selenide (ZnSe)

ZnSe was selected due to:

- High infrared transmissivity
- Lower cost
- Better availability
- Compatibility with FLIR wavelength range

  
### Thermal Camera Trade Studies
<p align="center">
 <img src="https://raw.githubusercontent.com/tmpuente133/senior-design-z-stage/main/images/thermalcamtradestudy.png" width="25%">
 <img src="https://raw.githubusercontent.com/tmpuente133/senior-design-z-stage/main/images/thermalcamtradestudy1.png" width="65%">
</p>

<p align="center">
  <em>
    Figure – Trade study evaluation comparing infrared viewport materials, integration approaches, and thermal imaging subsystem design concepts.
  </em>
</p>

Seperate trade studies also considered:

- Integration complexity
- Alignment capability
- Vacuum compatibility
- Manufacturability
- Long-term serviceability

---

## Final Thermal Camera Design

The final thermal subsystem includes:

- Custom FLIR mounting bracket
- Adjustable alignment interface
- ZnSe viewport assembly
- Integrated reducer flange

The system was designed to:

- Maintain vacuum integrity
- Minimize vibration and misalignment
- Preserve operator viewport access
- Enable continuous thermal monitoring during testing

---

### FLIR Mounting Assembly
<p align="center">
  <img src="https://github.com/tmpuente133/senior-design-z-stage/blob/main/images/flirmountexploded.png" width="450"><br>
  <em>Figure – Custom thermal camera mounting assembly designed for stable FLIR positioning and alignment.</em>
</p>

### ZnSe Viewport Assembly
<p align="center">
  <img src="https://github.com/tmpuente133/senior-design-z-stage/blob/main/images/explodedviewport.png" width="450"><br>
  <em>Figure – Exploded view of the ZnSe infrared viewport assembly integrated into the reducer flange system.</em>
</p>

---

## Thermal System Fabrication and Assembly

Fabrication and integration activities included:

- Rapid prototype development using additive manufacturing
- Installation of heat-set threaded inserts
- Hardware integration and alignment
- Thermal camera fit validation
- Final subsystem integration

The subsystem was designed for modularity, maintainability, and future experimental flexibility.

---

### Thermal System Fabrication
<p align="center">
  <img src="https://github.com/tmpuente133/senior-design-z-stage/blob/main/images/3dflirfab2.png" width="400"><br>
  <em>Figure – Thermal subsystem fabrication activities including prototyping, insert installation, and hardware integration.</em>
</p>

<p align="center">
  <img src="https://github.com/tmpuente133/senior-design-z-stage/blob/main/images/heatsetinsert3.png" width="400"><br>
  <em>Figure – Thermal subsystem fabrication activities including prototyping, insert installation, and hardware integration.</em>
</p>

<p align="center">
  <img src="https://github.com/tmpuente133/senior-design-z-stage/blob/main/images/hardwareinstallflirmount.png" width="300"><br>
  <em>Figure – Thermal subsystem fabrication activities including prototyping, insert installation, and hardware integration.</em>
</p>

---

## Thermal System Validation

Validation testing confirmed:

- Clear thermal imaging of test coupons
- Stable thermal camera positioning
- Proper optical alignment through viewport
- Full coupon visibility within operating field of view
- Distinguishable thermal gradients during operation

The subsystem successfully met all thermal imaging performance requirements.

---

### Thermal Imaging Validation
<p align="center">
  <img src="https://github.com/tmpuente133/senior-design-z-stage/blob/main/images/fovanalyis.png" width="650"><br>
  <em>Figure – Validation testing of the thermal imaging subsystem including alignment verification and field-of-view analysis.</em>
</p>

<p align="center">
  <img src="https://github.com/tmpuente133/senior-design-z-stage/blob/main/images/centeredlens.png" width="500"><br>
  <em>Figure – Validation testing of the thermal imaging subsystem including alignment verification and field-of-view analysis.</em>
</p>

### Thermal Imaging Output
<p align="center">
  <img src="https://github.com/tmpuente133/senior-design-z-stage/blob/main/images/thermal%20gradient.png" width="400"><br>
  <em>Figure – Thermal imaging output captured through the ZnSe viewport during subsystem validation testing.</em>
</p>

---

## Manufacturing Documentation

Manufacturing drawings were produced for all custom subsystem components, including:

- ID clamp interfaces
- Camera mounting hardware
- Thermal camera mounting brackets
- Viewport interfaces
- Alignment hardware

Drawings incorporated:

- Vacuum-compatible tolerancing
- GD&T standards
- DFMA considerations
- Accessibility and assembly requirements

---

### Manufacturing Documentation
<p align="center">
  <img src="https://github.com/tmpuente133/senior-design-z-stage/blob/main/images/Screenshot%202026-01-31%20173111.png" width="500"><br>
  <em>Figure – Example manufacturing drawing showing GD&T implementation and vacuum-compatible tolerancing for subsystem hardware.</em>
</p>

---

## Lessons Learned

Key engineering lessons from the project included:

- Physical fit validation is often more reliable than idealized measurement data alone.
- Early prototyping significantly reduces manufacturing and schedule risk.
- Vacuum-compatible design constraints strongly influence subsystem architecture.
- Modularity improves integration flexibility and future maintainability.
- Integration between independently developed subsystems is often the most challenging aspect of system development.

One major lesson involved validating vessel geometry using low-cost 3D printed prototypes before machining production hardware, preventing substantial cost and lead-time risk.

---

## Future Improvements

Potential future improvements include:

- Automated camera articulation
- Improved cable routing and strain relief
- Permanent thermal camera alignment fixtures
- Expanded thermal characterization capability
- Automated imaging synchronization
- Additional contamination protection for optical components

---

## Project Outcome

The final visualization subsystem was successfully integrated into ASML’s vacuum vessel environment.

Project accomplishments included:

- Successful in-vacuum digital imaging integration
- Real-time thermal monitoring capability
- Improved operator visibility and positioning flexibility
- Continuous observation without venting the chamber
- Stable subsystem performance under operational conditions
- Completion under project budget

The final system established a modular visualization platform for continued experimental development and future subsystem expansion.

---
