# CAD Arm

> CAD designs and mechanical components for a custom robotic arm system.

This repository contains the **CAD models and mechanical design files** for a custom robotic arm project.

The project is organized around the different physical assemblies of the arm, including the host arm, slave arm, horns, and electronic component models.

The goal of this repository is to keep the mechanical design and supporting CAD components of the robotic arm organized in one place, making it easier to iterate on the design, manufacture components, and continue developing the physical system.

---

## Project Structure

```text
CAD-Arm/
│
├── Host Arm/
│   └── Host arm CAD assemblies and components
│
├── Slave Arm/
│   └── Slave arm CAD assemblies and components
│
├── Horns/
│   └── Servo/motor horn designs
│
├── Electronic Components/
│   └── CAD models for electronic components
│
├── LICENSE
└── .gitattributes
```

---

## Arm Design

The project is split into two primary mechanical assemblies:

### Host Arm

The **Host Arm** represents one side of the robotic arm system and contains its corresponding mechanical CAD components.

### Slave Arm

The **Slave Arm** contains the corresponding mechanical assembly and components for the other side of the system.

Separating the two assemblies makes it easier to modify, manufacture, and iterate on each arm independently.

---

## Mechanical Components

The repository also contains individual supporting components used throughout the arm design.

### Horns

Custom horn designs are included for connecting the actuators to the mechanical structure of the arm.

### Electronic Components

CAD representations of relevant electronic components are included to help with:

- Mechanical clearances
- Component placement
- Mounting
- Assembly planning
- Overall enclosure and structural design

---

## Design Workflow

The general workflow for the project is:

```text
Concept
   │
   ▼
Mechanical Design
   │
   ▼
CAD Modeling
   │
   ├── Host Arm
   │
   ├── Slave Arm
   │
   ├── Horns
   │
   └── Electronics
   │
   ▼
Assembly
   │
   ▼
Prototype / Manufacturing
   │
   ▼
Testing & Iteration
```

The CAD models are intended to evolve alongside the physical prototype.

---

## Repository Purpose

This repository is primarily focused on the **hardware design side** of the robotic arm.

It is useful for:

- Mechanical design reference
- CAD iteration
- Manufacturing preparation
- 3D-printing preparation
- Assembly planning
- Component placement
- Future hardware modifications

The software controlling the arm is separate from this repository.

---

## Development Status

This is an **active design/prototyping repository**.

The CAD models may change as the physical arm is assembled and tested.

Expect:

- Design iterations
- Modified dimensions
- Component replacements
- Structural improvements
- Experimental parts
- Multiple versions of components

This repository represents the development process rather than a finalized production-ready robotic arm.

---

## Future Improvements

Potential future work includes:

- Finalizing mechanical tolerances
- Improving structural strength
- Reducing unnecessary material
- Improving cable routing
- Adding better component mounting
- Refining the arm's mechanical joints
- Creating manufacturing-ready assemblies
- Generating standardized STL/STEP exports
- Adding detailed assembly documentation
- Adding a complete bill of materials
- Documenting mechanical specifications
- Adding photos of the physical prototype

---

## Related Work

The CAD repository is intended to be part of the larger robotic-arm development process, alongside the electronics, firmware, control software, and computer-vision components.

---

## License

This project is licensed under the **MIT License**.

See [`LICENSE`](./LICENSE) for the complete license text.

---

## Author

**Pranab Saini**

GitHub:  
https://github.com/Pranabsssssss

---

<p align="center">
  <strong>CAD Arm</strong><br>
  Robotic Arm Mechanical Design & Prototyping
</p>