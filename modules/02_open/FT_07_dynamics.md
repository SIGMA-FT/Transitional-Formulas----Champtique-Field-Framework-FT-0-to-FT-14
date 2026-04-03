## FT-7 — Generic Field Dynamics
**Status:** A_DISC (Open)
**Expression:** `∂tΦ = D∇²Φ − Γ(Φ,ρ,κ,m) + Σ`

---

### Statement

The field evolves through three simultaneous processes:

**D∇²Φ** — diffusion / field plasticity
**−Γ(Φ,ρ,κ,m)** — return toward the local champtique continuum
**Σ** — external excitation or coupling (incoming champtique differential)

---

### Parameters

**D** — field plasticity coefficient (diffusion)
**Γ** — return function toward local continuum
**Σ** — external excitation: what classical physics names
        pressure, temperature, or collision depending on measurement context —
        always the same cause, varying mode of delivery

---

### Critical Correction on Γ

**Γ is NOT a return toward fixed thermodynamic equilibrium.**

Classical physics imports a fixed equilibrium point —
the system "relaxes" toward a predefined state.
In Pch: the local continuum is itself evolving.
There is no fixed equilibrium — only states of lesser differential.

Γ = return toward the **local champtique continuum**,
which is itself dynamic and history-dependent (FT-8, m).

---

### Open Zone

**What remains to be determined:**
the functional form of Γ.

Is Γ:
- Linear in ΔΦ? → exponential relaxation (simplest)
- Nonlinear? → threshold behavior, hysteresis
- κ-dependent? → slow return in high-κ materials, fast in low-κ

**Experimental path:**
Measure the velocity of return to equilibrium after a perturbation,
on materials of different κ.

**OBS-008 (copper bars + falling magnet)** already provides
raw data for this analysis:
the braking curve as function of gap distance
is the direct observable of D and Γ combined.

**Forthcoming rhéomètre champtique** (3-balance gantry + laser distance 0.005mm)
will provide the precision measurements needed to extract Γ form.

**Experimental candidate (immediate):**
Same copper bar — annealed vs tempered.
Same magnet, same geometry, same gap.
If braking differs → κ of material modified by thermal history → FT-9 link.
If braking identical → κ is geometry-dominated, not history-dependent.
Simple, accessible, discriminating.

---

### Geometric Extension (A_FORMALISER)

FT-7 can be enriched with a geometry term:

```
∂tΦ = D∇²Φ − Γ(Φ,ρ,κ,m) + Σ + G(κ, geometry)
```

Where G captures the field guidance effect of surface geometry:
- Tip → convergent gradient → outgoing Φd emission
- Open cone → inverted convergence → incoming Φd capture
- Polished plane → tangential guidance
- Schwarz minimal surfaces → quasi-stationary solutions (H=0) of FT-7

This term is documented in OBS-002 (cone effect)
and OBS-050 (Schwarz TPMS as quasi-stationary solutions).

---

### Falsification Criterion

FT-7 fails if:
Γ is demonstrated to be a return toward a fixed equilibrium point —
i.e., the same final state is reached regardless of the prior history
of the local continuum.

---

### Links
- CMRPCh-Experimental EXP-003, EXP-008: DOI 10.5281/zenodo.19135745
- OBS-002, OBS-008, OBS-050: internal CMRPCh corpus

*CMRPCh — SIGMA — 2026 — CC BY-SA 4.0*
