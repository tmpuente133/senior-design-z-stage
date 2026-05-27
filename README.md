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

<!-- <img src="images/sld.png" width="850"> 

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

# [INSERT DIGITAL CAMERA OVERVIEW IMAGE HERE]

---

## Digital Camera Design Trade Studies

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

---

# [INSERT DIGITAL CAMERA TRADE STUDY IMAGE HERE]

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

# [INSERT ID CLAMP IMAGE HERE]

---

## Structural Validation of Clamp Interface

Because the camera assembly is fully supported through frictional contact with the vessel wall, structural validation of the clamp interface was required.

Finite element analysis was performed to evaluate:

- Stress distribution
- Contact loading
- Off-axis moment loading
- Clamp stiffness
- Potential slip conditions

Results confirmed that the mounting interface provides sufficient stiffness and safety margin under operational loading conditions.

---

# [INSERT FEA IMAGE HERE]

# [INSERT LOAD CASE IMAGE HERE]

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

# [INSERT FINAL DIGITAL CAMERA CAD IMAGE HERE]

# [INSERT FINAL INTEGRATED CAMERA IMAGE HERE]

---

## Digital Camera Fabrication and Assembly

The subsystem progressed through prototyping, fabrication, and full in-vacuum integration.

### Fabrication Activities

- CMM measurement of vessel geometry
- 3D printed prototype validation
- Turning and tapping of ID clamp hardware
- Rail assembly integration
- Final subsystem fit validation

Rapid prototyping significantly reduced manufacturing risk and prevented costly rework of long lead-time hardware.

---

# [INSERT FABRICATION COLLAGE HERE]

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

# [INSERT DIGITAL CAMERA TESTING IMAGE HERE]

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

# [INSERT THERMAL SYSTEM OVERVIEW IMAGE HERE]

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

Trade studies also considered:

- Integration complexity
- Alignment capability
- Vacuum compatibility
- Manufacturability
- Long-term serviceability

---

# [INSERT THERMAL TRADE STUDY IMAGE HERE]

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

# [INSERT FLIR MOUNT CAD IMAGE HERE]

# [INSERT ZNSE VIEWPORT CAD IMAGE HERE]

# [INSERT THERMAL SYSTEM INTEGRATION IMAGE HERE]

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

# [INSERT THERMAL FABRICATION IMAGE HERE]

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

# [INSERT THERMAL VALIDATION IMAGE HERE]

# [INSERT THERMAL OUTPUT IMAGE HERE]

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

# [INSERT DRAWING IMAGE HERE]

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

## Contributions

### Tomas Puente
Primary ownership of:

- Hybrid visualization subsystem architecture
- Digital camera subsystem integration
- Thermal imaging subsystem integration
- ID clamp mounting strategy
- Optical alignment analysis
- Thermal viewport integration
- Structural validation of mounting interfaces
- Manufacturing documentation

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
