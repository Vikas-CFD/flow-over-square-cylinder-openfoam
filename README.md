# Flow Over Square Cylinder using OpenFOAM

## Overview
This project investigates incompressible flow over a square cylinder using OpenFOAM.

Simulations were performed for:
- Re = 100
- Re = 200
- Re = 300

The objective was to study wake formation and flow separation behavior for different Reynolds numbers.

---

## Objectives
- Simulate flow over a square cylinder
- Analyze wake formation
- Study drag and lift characteristics
- Perform mesh independence study

---

## Software & Tools
- OpenFOAM v2412
- ParaView
- Linux (WSL)

---

## Project Structure

```text
cases/
   Re100/
   Re200/
   Re300/

mesh/
README.md
```

---

## Methodology
- Geometry generated using blockMesh
- Air considered as working fluid
- Multiple Reynolds number studies conducted

---

## Key Learnings
- OpenFOAM workflow
- Mesh generation using blockMesh
- Boundary condition implementation
- Reynolds number effect on flow behavior

---

## Future Work
- LES simulations
- Unsteady vortex shedding analysis
- Turbulence model comparison

---

## Author
Vikas CFD
M.Tech Thermal & Fluid Engineering
