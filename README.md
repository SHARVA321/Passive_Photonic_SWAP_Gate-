# Passive Photonic SWAP Gate via Chirally Coupled Two-Level Emitters

## Abstract/Overview
This project proposes and numerically validates a passive photonic SWAP gate built exclusively from two-level emitters chirally coupled to two multimode waveguides. It demonstrates how chirality and dispersion engineering can yield distinct polariton branches with different group velocities, leading to a saturable nonlinear phase shift without spectral entanglement.

## Key Features/Contributions
* **Passive Gate Design:** Developed a passive $\pi$ gate using only two-level emitters, chirality, and dispersion engineering, eliminating the need for additional nonlinear media.
* **Spectrally Clean Operation:** Confirmed that the output remains unentangled in frequency, ensuring high fidelity.
* **High Fidelity with Emitter Count:** Showcased that inelastic scattering rapidly diminishes with an increasing number of emitters, achieving near-ideal performance by $N \approx 30$.
* **Modular Architecture:** Demonstrated a modular design where the same Controlled-Z (CZ) block can be reused to construct a deterministic SWAP gate by combining three CZs with Hadamard gates.
* **Numerical Validation:** Validated theoretical predictions through full-wave simulations, matching results for single-photon dispersion, group velocity, mode composition, two-photon phase, and joint output spectra for various emitter counts.

## Methodology
The study combines theoretical underpinnings with numerical simulations:
* **Theoretical Framework:** Explored chirality in waveguide Quantum Electrodynamics (QED), detailing the effective spin Hamiltonian and the formation of polariton branches with distinct group velocities.
* **Simulation:** Utilized Lumerical (or similar full-wave simulation software) to numerically validate the proposed design, including single-photon scattering (S-matrix), two-photon scattering, and the resulting nonlinear phase.

## Results
The simulations successfully validated every step of the proposed design, confirming two-band polariton formation, distinct group velocities, the acquisition of a saturable nonlinear phase shift, and the suppression of inelastic scattering. The results align with theoretical predictions, demonstrating the feasibility and scalability of the modular CZ-block architecture for integrated photonic quantum information processing.

## Visualizations
The `plots/` directory contains detailed graphs illustrating key simulation results:
* Single-photon dispersion $\omega(q)$
* Group velocity $v_g(q)$
* Transfer-eigenstate composition $\theta(\omega)$
* Nonlinear two-photon phase $\phi$ vs $\delta$
* Two-photon joint output spectra for $N=2, 16, 30$ emitters

Example:
![Single-photon dispersion](plots/single_photon_dispersion.png)

## Technologies Used
* `Lumerical` (or other full-wave simulation software for photonics)
* `Python` (if used for post-processing or plotting)

## Full Report
For a comprehensive understanding of the project, including detailed theoretical underpinnings, design, and analysis, please refer to the full report:
[Passive Photonic SWAP Gate Report](docs/Passive_Photonic_SWAP_Gate_Report.pdf)

## Contributors
* Sharva Ranganath (PES1UG22EC269)
* Aprameya Kulkarni (PES1UG22EC914)
