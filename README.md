# Flow Over Square Cylinder using OpenFOAM

## Overview
This project investigates incompressible flow over a square cylinder using OpenFOAM.

The simulations were performed for:
- Re = 100
- Re = 200
- Re = 300

The objective was to study wake formation, flow separation, and drag/lift behavior for different Reynolds numbers.

---

## Objectives
- Simulate flow over a square cylinder
- Analyze wake development
- Study flow separation behavior
- Compute drag and lift coefficients
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
- Simulations performed using steady-state solver
- Air considered as working fluid
- Multiple Reynolds number studies conducted

---

## Key Learnings
- Effect of Reynolds number on wake structures
- Importance of mesh quality
- Boundary condition implementation in OpenFOAM
- CFD post-processing using ParaView

---

## Future Work
- LES simulations
- Unsteady vortex shedding analysis
- Turbulence model comparison

---

## Author
Vikas CFD
M.Tech Thermal & Fluid Engineering# flow-over-square-cylinder-openfoam
