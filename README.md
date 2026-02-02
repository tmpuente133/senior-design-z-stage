# In-vacuum Z-Stage and test visualization metrology of tin-H interactions in the EUV source - Capstone (ASML X SDSU)
---

## Overview
This repository documents the design, analysis, and implementation of an **in-vacuum visualization subsystem** developed as part of a larger experimental platform for studying tin–hydrogen (Sn–H) interactions inside an Extreme Ultraviolet (EUV) source test vessel.

The broader project includes an externally adjustable in-vacuum Z-stage to position material samples. This repository focuses primarily on the **camera subsystem**, which enables continuous visual and thermal monitoring of samples during testing without obstructing operator viewports or requiring manual intervention under vacuum.

This work is part of the **SDSU Mechanical Engineering Senior Design Capstone Program** and is sponsored by **ASML (Extreme Ultraviolet Group, San Diego)**.

---

## Project Context
Tin–hydrogen interaction experiments are conducted inside a dedicated vacuum vessel to better understand material behavior relevant to EUV lithography sources. During testing, samples are exposed to hydrogen radicals, and physical changes such as spitting, blistering, and surface modification must be monitored in real time.

Prior to this project, visualization was limited by:
- Fixed external cameras mounted to viewports
- Blocked operator visibility
- Inability to continuously monitor samples during experiments
- Limited flexibility in camera positioning and alignment

The visualization subsystem developed in this project addresses these limitations by placing cameras **inside the vacuum vessel** and mechanically integrating them with the experimental platform.

---

## System Overview

### Experimental Setup Inside Vacuum Vessel
The visualization system is mounted internally and positioned to observe samples located on the Z-stage platform. The Z-stage provides positional adjustment, while the camera subsystem provides continuous visual access during testing.

<img src= "images/ZStage_Setup.png" alt="Porcipine Vessel" width="375">

---

## Visualization Subsystem

### Camera System Concept
The visualization subsystem consists of a digital camera and thermal camera mounted to a rigid internal support, allowing continuous monitoring of test samples without blocking external viewports.

Design considerations included:
- Vacuum compatibility and material selection
- Structural rigidity and vibration resistance
- Optical alignment and field-of-view constraints
- Protection from tin vapor and debris
- Compatibility with existing vessel geometry

<img src= "images/Picture4.png" alt="Digital Camera" width="375">

---

### Camera Mounting Strategy
A non-invasive mounting approach was required to avoid modifying existing vacuum hardware. The camera system is mechanically supported using **Mitee-Bite internal diameter (ID) clamps**, allowing rigid attachment to existing cylindrical features inside the vessel.

This approach provides:
- High positional repeatability
- Structural stiffness under load
- No permanent modification to the vessel
- Ease of installation and removal

**Figure 3. Camera mount and ID clamp interface**  

<img src= "images/Screenshot%202026-01-31%20183246.jpg" alt="Porcipine Vessel" width="375">

---

### ID Clamp Interface and Validation
Due to measured cylindricity variation in the mating features, secondary machining strategies and tolerancing considerations were developed to ensure reliable clamp engagement and load distribution.

Structural validation was performed to confirm that the clamp-based interface could support the camera system under operational loading.

**Image 4 – Load Case and Boundary Conditions for Clamp Validation**  

<img src= "images/Picture3.jpg" alt="Porcipine Vessel" width="375">

**Image 5 – Structural Analysis Results**  

<img src= "images/Picture2.png" alt="Porcipine Vessel" width="425">

## Manufacturing Documentation

### Drawings and Assembly
Manufacturing drawings were produced for all custom camera mounting components, including tolerancing strategies compatible with vacuum assembly and alignment requirements.

**Image 6 – Exploded View of Reducer and Zinc-Selenide Viewport Assembly**  

<img src= "images/Screenshot%202026-01-31%20171220.png" alt="Porcipine Vessel" width="375">

**Image 7 – Example Manufacturing Drawing (ID Clamp Interface Part)**  

<img src= "images/Screenshot%202026-01-31%20173111.png" alt="Porcipine Vessel" width="375">

---

## Subsystem Ownership and Contributions

Subsystem ownership was assigned to ensure technical accountability and design depth.

### Visualization and Camera Subsystem  
**Primary Owner: Tomas Puente**

Responsibilities included:
- System-level concept development for in-vacuum visualization
- Integration of digital and thermal cameras
- Mechanical design of camera mounting hardware
- Optical alignment and field-of-view considerations
- Thermal, structural, and contamination constraints
- Integration of the camera subsystem with the Z-stage platform

### ID Clamp–Based Mounting Technique  
**Primary Owner: Tomas Puente**

- Selection of Mitee-Bite ID clamps as a non-invasive mounting solution
- Interface design leveraging existing vessel geometry
- Secondary machining strategy to accommodate cylindricity variation
- Structural validation of the clamp-based mounting approach
- Creation of manufacturing drawings and tolerancing strategy

---

## Current Project Status
The design and analysis phases of the visualization subsystem have been completed. The project is **currently entering the manufacturing and assembly phase**, with custom camera mounting components being fabricated and procured.

This repository will be **updated throughout the semester** as manufacturing, assembly, integration, and testing progress.

