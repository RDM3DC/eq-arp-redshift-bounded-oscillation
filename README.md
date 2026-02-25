# ARP Redshift Law with Bounded Oscillatory Steering

**ID:** `eq-arp-redshift-bounded-oscillation`  
**Tier:** derived  
**Score:** 73  
**Units:** OK  
**Theory:** PASS-WITH-ASSUMPTIONS  

## Equation

$$
z(t)=z_h\left(1-e^{-\gamma t}\right)\left(1-\epsilon\cos(\omega t+\phi)\right),\quad 0\le\epsilon<1
$$

## Description

A redshift-relaxation bypass law with bounded oscillatory steering. Keeps ARP exponential approach while adding controlled wobble without sign flips when epsilon is constrained.

## Assumptions

- Single effective horizon scale z_h over the modeled interval.
- Two separated timescales: envelope gamma^{-1} and modulation omega^{-1}.
- Bounded modulation 0<=epsilon<1 ensures nonnegative trajectory.

## Repository Structure

```
images/       # Visualizations, plots, diagrams
derivations/  # Step-by-step derivations and proofs
simulations/  # Computational models and code
data/         # Numerical data, experimental results
notes/        # Research notes and references
```

## Links

- [TopEquations Leaderboard](https://rdm3dc.github.io/TopEquations/leaderboard.html)
- [TopEquations Main Repo](https://github.com/RDM3DC/TopEquations)
- [Certificates](https://rdm3dc.github.io/TopEquations/certificates.html)

---
*Part of the [TopEquations](https://github.com/RDM3DC/TopEquations) project.*
