# Module 04 — Forthcoming
## Constants Extraction Program and Candidate Formulas

**Status of this module:** research frontier — not ready for publication as formulas

---

## What This Module Contains

This module documents:
1. Prototypical functional forms for key Pch parameters
2. The inter-AI constants extraction program
3. Candidate formulas under development

These are not published as formulas.
They are announced as structured research subjects —
open to the community, protected as prior art.

---

## Proto-Θ — Functional Form for Time Factor

```
Θ(ρ,κ,m) = α · ρ^β · κ^γ
```

**Status:** A_FORMALISER

This power-law form is structurally consistent with:
- GPS correction data (PH-037) — Θ variation between orbital and surface
- Biological longevity data (OBS-005) — Θ variation between dense and diffuse media

Constants α, β, γ are not yet numerically extracted.
This is the primary target of the inter-AI constants program.

---

## Proto-τm — Functional Form for Memory Time

```
τm(κ) = τ₀ · exp(λ · κ)
```

**Status:** A_FORMALISER

This exponential form satisfies both regime boundaries:
- κ → 0 : τm → τ₀ (finite memory duration)
- κ → 1 : τm → ∞ (permanent memory)

Constants τ₀ and λ are not yet numerically extracted.

---

## FT-15 Candidate — Hierarchical κ Absorption

**Proposed role:** absorption hierarchy and κ propagation from surface to volume

**Status:** HYP

Motivated by:
- OBS-006: surface state modifies bulk behavior — how far does κ_surface propagate?
- OBS-050: Schwarz minimal surfaces as κ-attractors in biological tissues

Not formalized. Announced as open research subject.

---

## Inter-AI Constants Extraction Program

**Objective:**
Numerical extraction of Pch constants from documented quantified observables.

**Target constants:**
- α, β, γ (Θ functional form)
- τ₀, λ (τm functional form)

**Method:**
Structured cross-AI analysis of quantified experimental data.
Each AI system applies the same structured protocol to the same dataset.
Results are centralized and synthesized.

**Available data sources:**
- OBS-008: quantified magnet braking measurements (gap vs fall time table)
- PH-037: GPS correction factors (orbital vs surface Θ ratio)
- OBS-005: biological longevity data (dense vs diffuse media)
- Forthcoming: rhéomètre champtique instrumented measurements

**Forthcoming instrument — Rhéomètre champtique:**
```
Gantry     : 3 interchangeable balances by measurement range
Balance A  : balanced materials — bell + agate knife
Balance B  : Φd_high materials (Ag, Cu...) — 0.1g precision
Balance C  : Φd_low materials (Fe, Ni...) — hydraulic jack
Sensor     : laser distance 0.005mm (replaces mirror galvanometer)
Z-axis     : stepper motor + linear encoder 1/100mm
Materials  : PTFE/PEEK in sensitive zones, aluminum for gantry
```

Estimated delivery: 3 weeks from construction start.
Results → CMRPCh-Experimental v2.

---

*CMRPCh — SIGMA — 2026 — CC BY-SA 4.0*
