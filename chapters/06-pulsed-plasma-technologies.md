# Chapter 6: Pulsed Plasma Technologies & Charge Mitigation

## 6.1 The High-Aspect-Ratio Charging Problem
When etching deep holes in 3D NAND (depth $>5\mu\text{m}$, aspect ratio $>60:1$):
- Highly directional positive ions hit the trench bottom.
- Isotropic thermal electrons deposit on the insulating upper sidewalls.
- The resulting differential charging creates an electrostatic repulsion field that deflects incoming ions, causing etch stopping, striations, and twisting.

## 6.2 Synchronized Source & Bias Pulsing
Advanced etch tools pulse RF generators at frequencies of **$1\text{ to } 50\text{ kHz}$** with duty cycles between $10\%$ and $50\%$:
1. **Pulse ON:** High-density plasma generates ions and radicals; sheath establishes ion acceleration.
2. **Pulse OFF (Afterglow):** Fast electrons cool within $10\mu\text{s}$, collapsing the sheath voltage. Trapped negative ions and thermalized positive ions recombine, neutralizing surface charging and allowing distortion-free etching of 100:1 aspect ratios.
