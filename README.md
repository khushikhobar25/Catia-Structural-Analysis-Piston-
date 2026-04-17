# Structural Analysis of Piston using CATIA V5
A finite element analysis (FEA) project comparing two piston materials — Aluminum Alloy and Aluminum Graphite — under engine operating conditions, using CATIA V5 structural simulation.

## Project overview
The piston is one of the most critically stressed components in an engine. It endures cyclic gas pressure and extreme temperatures that can cause skirt seizing, head seizing, ring damage, and cylinder damage.

This project designs a 3D piston model in CATIA V5 and performs structural analysis using FEA to determine Von Mises stress distribution and identify safe vs unsafe design conditions.

## Objectives
- Design a complete 3D piston model using CATIA V5 Part Design
- Apply two different materials and compare structural performance
- Determine maximum Von Mises stress under simulated load conditions
- Validate whether the piston design is safe against failure

## 3D model
The piston was modelled in CATIA V5 using:
- Shaft and pad features for the piston crown and skirt
- Circular patterns for bolt holes and ring grooves
- Pocket features for the wrist pin bore
- Mirror operations for symmetric features

## Structural analysis results
| Property | Value |
|---|---|
| Analysis type | Static structural (FEA) |
| Maximum Von Mises stress | 3.25 × 10⁴ N/m² |
| Result | Von Mises stress < permissible stress → Design is safe |
| Constraint | Piston pin holes fully constrained (all DOF) |

## Material comparison
| Property | Aluminum Graphite | Aluminum Alloy |
|---|---|---|
| Weight | Light | Heavier |
| Heat conduction | Excellent | Good |
| Carbon deposits | Very low | Higher |
| Fuel efficiency | Better (less reciprocating mass) | Lower |
| Manufacturability | Easy | Needs special liners |
| Result | Preferred | Standard |

**Conclusion:** Aluminum Graphite piston has lower mass, reduced stress concentration, longer fatigue life, and results in less fuel consumption and lower vehicle emissions compared to Aluminum Alloy.

## Key skills demonstrated
- 3D parametric modelling of complex mechanical components
- Finite Element Analysis (FEA) using CATIA structural simulation
- Von Mises stress interpretation and design validation
- Material property assignment and comparison
- Technical drawing generation with multi-view drafting

## Tools & software
- CATIA V5-R21 (3DEXPERIENCE platform)
- Part Design workbench
- Structural Model Creation (FEA)
- Material Editor
- Generative Shape Design (surfacing)
- Drafting workbench

## About
Completed under the guidance of Mrs. Rachna Singh and Dr. Manoj Soni, Department of Mechanical & Automation Engineering, Indira Gandhi Delhi Technical University for Women (IGDTUW), July 2023.
