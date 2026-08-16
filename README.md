# SOLIDWORKS-Projects
Projects that showcase my experience and familiarity of using SOLIDWORKS.

## Biomedical Device - ZipStitch 🏥

### Project Overview

This project involved designing a conceptual **Zip Stitch wound-closure device** using SOLIDWORKS. The project involved modelling individual components, developing their mechanical features, assembling the components and preparing the completed design for 3D printing.

The project provided an opportunity to apply **CAD modelling, mechanical design and assembly techniques** within a biomedical engineering context while considering component interaction, functionality and manufacturability.

> **Note:** This project is a conceptual engineering design developed for educational and portfolio purposes. It is not intended for clinical use.

---

## What is a Zip Stitch?

A Zip Stitch is a **non-invasive wound-closure device** designed to bring the opposing edges of a minor wound together without the use of conventional sutures or staples.

The device uses components positioned on either side of the wound together with a zip-style tightening mechanism. As the zip line is pulled through the retaining mechanism, the opposing sides are progressively drawn closer together to close the wound.

The concept provides an example of how a **simple mechanical mechanism can be applied to a biomedical application**, combining controlled movement with an external wound-closure approach.

<p align="center">
  <img width="350" alt="Zip Stitch wound closure example" src="https://github.com/user-attachments/assets/fce7b981-ccac-458e-9695-c0828ae3a5ea" />
</p>

<p align="center">
  <em>Example application of a zip-style wound closure device.</em>
</p>

---

The completed Zip Stitch design consists of **two primary components** that work together to create the proposed wound-closing mechanism:

- **Part 1 – Stopper:** A retaining component containing the internal mechanism designed to receive and engage with the zip line.
- **Part 2 – Zip Line & Hooks:** A moving component containing repeated hook features designed to travel through and interact with the stopper.

Both components were modelled individually in SOLIDWORKS before being brought together in an **assembly**. The final assembly was configured with appropriate positioning and clearance between the components before being exported as an STL file for 3D printing.

---

## Part 1 – Stopper Design

The first stage of the project involved designing the **stopper**, which acts as the retaining component of the Zip Stitch mechanism. The stopper was designed to receive the zip line and incorporate an internal **lever-clamp mechanism** that interacts with the hook features of Part 2.

The model was developed progressively from the base geometry, followed by the internal guided opening and lever-clamp features. A protective outer structure was also incorporated around the clamping region to provide a smoother external profile and reduce the likelihood of the device catching on clothing or fabric.

Key SOLIDWORKS features used during the design included:

- **Extruded Boss/Base** to create the primary geometry
- **Extruded Cut** to create openings and internal features
- **Lofted Cut** to develop the guided opening for the zip line
- **Lofted Boss/Base** to create the internal lever-clamp geometry
- **Reference Planes, Splines and Arcs** for more complex geometry
- **Circular Pattern** to replicate the internal clamp features
- **Mirror** to create the corresponding stopper
- **Fillet** to smooth external edges and improve the overall geometry

<p align="center"> <img width="500" alt="Screen Shot 2026-08-01 at 11 44 55 pm" src="https://github.com/user-attachments/assets/2ced223b-ea89-4e37-8907-c321c7532dca" />
<p align="center">
  <em>Part 1 – Final SOLIDWORKS model of the stopper components.</em>


<p align="center">
  📁 <a href="KevinYee_13937230_part 1.STL">View Part 1 – Stopper STL</a>
</p>

---

## Part 2 – Zip Line & Hook Design

The second stage involved designing the **zip line and hook mechanism** that passes through and interacts with the stopper.

A cylindrical zip line was created with a series of repeated hook features along its length. These features were designed to allow the zip line to move **forward through the stopper while resisting movement in the opposite direction**, forming the basis of the one-way tightening mechanism.

Rather than modelling each hook individually, a single hook profile was created and replicated along the zip line using a **Linear Pattern**, producing 20 evenly spaced features. A circular pulling handle was also incorporated at the end of the zip line to provide a practical gripping point during operation.

Key SOLIDWORKS features used included:

- **Extruded Boss/Base** to develop the base and supporting geometry
- **Revolved Boss/Base** to create the hook geometry around the cylindrical zip line
- **Reference Planes** for positioning features along the model
- **Linear Pattern** to produce consistent, evenly spaced hook features
- **Extruded Cut** to create the opening within the pulling handle
- **Mirror** to duplicate the completed zip-line component
- **Fillet** to smooth sharp edges and corners

<p align="center"> <img width="500" alt="Screen Shot 2026-08-02 at 12 00 53 am" src="https://github.com/user-attachments/assets/451c165d-155c-45df-ac5c-d51189929ab5" />
<p align="center">
  <em>Part 2 – Final SOLIDWORKS model of the zip line, hook features and pulling handles.</em>
  
<p align="center">
  📁 <a href="KevinYee_13937230_part 2.STL">View Part 2 – Zip Line & Hooks STL</a>
</p>


---

## Part 1 & 2 – Final Assembly

The final stage involved bringing **Part 1 (Stopper)** and **Part 2 (Zip Line & Hooks)** together within a SOLIDWORKS assembly to create the complete Zip Stitch model.

The components were inserted and positioned so that each zip line was correctly aligned with the corresponding opening in the stopper. **Concentric mates** were used to align the cylindrical zip lines with the internal stopper mechanism, while a **distance mate** was applied to maintain the required separation between the components.

Particular attention was given to component positioning and clearance to ensure that the individual bodies did not intersect while maintaining their intended mechanical relationship.

Key assembly techniques included:

- Component insertion and orientation
- **Concentric Mates** for alignment between the zip line and stopper
- **Distance Mate** for controlled component positioning
- Component movement and positioning
- Clearance and interference consideration
- Multi-component assembly

<p align="center">
  <img width="500" alt="Final Zip Stitch SOLIDWORKS design" src="https://github.com/user-attachments/assets/9cc11633-c703-4c86-98b5-caf52b95d94c" />
<p align="center">
  <em>Final SOLIDWORKS assembly showing Part 1 and Part 2 positioned together.</em>
</p>

<p align="center">
  📁 <a href="KevinYee_13937230_part1 and 2.STL">View Part 1 & 2 – Final Assembly STL</a>
</p>

---

## Skills Demonstrated

### SOLIDWORKS & CAD

- 3D Part Modelling
- Parametric Sketching & Dimensioning
- Extruded Boss/Base & Extruded Cut
- Lofted Features
- Revolved Features
- Linear & Circular Patterns
- Mirroring
- Reference Geometry
- Fillets
- Multi-Part Assembly
- Assembly Mates
- STL Preparation & Export

### Engineering

- Mechanical Design
- Component Interaction & Fit
- Assembly Design
- Design for 3D Printing
- Design for Manufacture
- Engineering Problem Solving
- Biomedical Engineering Design Application
