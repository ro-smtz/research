# Semiconductor absorption spectrum

Numerical computation of the semiconductor absorption spectrum using Elliott's formula, including excitonic contributions from bound and continuum states.

**Language:** Python / MATLAB (original in Mathematica)  
**Status:** Planned — reimplementation for reproducibility and visibility

## Physics

The optical absorption of a bulk semiconductor near the band edge is given by Elliott's formula, which accounts for both bound exciton states and the Coulomb-enhanced continuum:

$$\alpha(\omega) \propto \sum_{n=1}^{\infty} \frac{1}{n^3} \delta(\hbar\omega - E_g + E_b/n^2) + \Theta(\hbar\omega - E_g)\frac{2\pi\sqrt{E_b/(\hbar\omega - E_g)}}{1 - e^{-2\pi\sqrt{E_b/(\hbar\omega-E_g)}}}$$

where $E_b$ is the exciton binding energy and $E_g$ the band gap.

## Contents

*(Add scripts here.)*

## Notes

See [`notes/`](./notes/) for the full derivation and parameter choices.
