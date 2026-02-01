# In-Vacuum Z-Stage and Visualization System  
### Tin–Hydrogen Interactions in an EUV Source

---

## Overview
This repository contains the mechanical design, analysis, and implementation of an externally adjustable in-vacuum Z-stage and integrated visualization system for studying tin–hydrogen (Sn–H) interactions inside a vacuum vessel representative of an EUV lithography source.

This project is part of the **SDSU Mechanical Engineering Senior Design Capstone Program** and is sponsored by **ASML (Extreme Ultraviolet Group, San Diego)**.

---

## Project Goals
- Enable **remote vertical adjustment** of test samples under vacuum
- Improve **repeatability and positional accuracy**
- Eliminate confined-space manual adjustments
- Provide **continuous in-vacuum visualization** of samples during testing
- Maintain compatibility with existing vacuum vessel interfaces

---

## System Overview

### Vacuum Vessel Integration
The Z-stage and camera system are mounted internally within the vacuum vessel using existing interfaces to avoid permanent modification.

**Vacuum Vessel and Z-Stage Installation**


---

## Z-Stage Design

### Mechanical Layout
The Z-stage consists of a rigid linear support structure spanning the vessel interior, with a centrally mounted carriage supporting the sample platform and camera system.

**Z-Stage CAD Assembly**


### Load Case Definition
The primary load case includes the combined mass of the camera system, mounting hardware, and samples applied at the carriage.

**Applied Load and Boundary Conditions**


---

## Engineering Analysis

### Structural FEA
Finite Element Analysis was performed to evaluate deflection and stress under worst-case loading.

**Total Displacement**


**Von Mises Stress**


Results indicate acceptable deflection and stresses well below material yield limits.

---

## Visualization System

### Camera Mounting Concept
A digital camera and thermal camera are mounted directly to the Z-stage carriage to enable continuous observation without blocking external viewports.

**Camera Mount CAD**


The design includes provisions for alignment, thermal considerations, and replaceable protective optics.

---

## Manufacturing Documentation

### Assembly and Drawings
Critical components were fully dimensioned and toleranced for fabrication.

**Exploded Assembly View**


**Example Manufacturing Drawing**


---

## Subsystem Ownership and Contributions

Subsystem ownership was distributed to ensure technical depth and accountability.

### Thermal and Digital Camera Subsystem  
**Primary Owner: Tomas Puente**

- System-level concept and integration of the thermal camera
- Mechanical design of camera mounting hardware
- Optical alignment and field-of-view considerations
- Thermal, structural, and contamination constraints
- Integration of camera systems with the Z-stage carriage

### ID Clamp–Based Camera Mounting Method  
**Primary Owner: Tomas Puente**

- Development of a mounting strategy using Mitee-Bite ID clamps
- Interface design leveraging existing vessel geometry
- Secondary machining strategy to accommodate measured cylindricity variation
- Structural validation of the clamp-based mounting approach
- Creation of manufacturing drawings and tolerancing strategy

This approach enabled a rigid, repeatable, and non-invasive camera mounting solution.

---

## Current Project Status
The project has completed the design and analysis phase and is **entering the manufacturing and assembly period**. Custom components are being fabricated and procured, with system assembly and validation testing to follow.

This repository will be **updated throughout the semester** as manufacturing, assembly, and testing progress.

---

## Team
SDSU Mechanical Engineering – Senior Design Capstone  
*(Team members to be added)*

---

## Sponsor
**ASML – Extreme Ultraviolet (EUV) Group**  
San Diego, California
