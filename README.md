# 🧠 Density Functional Theory (DFT) Learning Journey

**Name**: Sk Toufik Haque  
**Goal**: To deeply understand the theoretical and mathematical foundation of Density Functional Theory (DFT) for quantum mechanical simulations and research applications.

---

## 📘 General DFT Topics Covered

### ✅ Quantum Mechanical Many-Electron Problem
- The fundamental challenge in quantum chemistry and materials science.
- Solving the many-body Schrödinger equation is computationally intractable for large systems.

### ✅ Introduction to Density Functional Theory
- Maps the many-electron problem to a functional of the electron density \( \rho(\mathbf{r}) \).
- Reduces computational cost by using single-particle orbitals.

### ✅ Kohn–Sham Spin-Density Functional Theory
- Reformulation of DFT to include spin:
  - Electron density is split into spin-up and spin-down components.
  - Introduces exchange-correlation functionals for spin systems.

---

## 📗 Wave Function Theory

### ✅ Wave Functions and Their Interpretation
- The wave function \( \Psi \) contains all information about a quantum system.
- Probability density: \( |\Psi(\mathbf{r}_1, \mathbf{r}_2, ..., \mathbf{r}_N)|^2 \)

### ✅ Wave Functions for Non-Interacting Electrons
- Slater determinant form for Fermions (antisymmetry).
- Independent-particle approximation.

### ✅ Wave Function Variational Principle
- The true ground-state energy is the minimum of the energy expectation value:
  \[
  E[\Psi] = \frac{\langle \Psi | \hat{H} | \Psi \rangle}{\langle \Psi | \Psi \rangle} \geq E_0
  \]

### ✅ Hellmann–Feynman Theorem
- Allows calculation of forces:
  \[
  \frac{dE}{d\lambda} = \left\langle \Psi \left| \frac{d\hat{H}}{d\lambda} \right| \Psi \right\rangle
  \]

### ✅ Virial Theorem
- Relates kinetic and potential energies:
  \[
  2\langle T \rangle = \langle \mathbf{r} \cdot \nabla V \rangle
  \]

---

## 📕 Density Functionals

### ✅ Definitions and Concepts
- Functionals are functions of a function.
- In DFT, the total energy is a functional of the electron density.

### ✅ Exchange–Correlation Energy
- Encodes all complex many-body effects.
- Known approximately using LDA, GGA, hybrid functionals, etc.

---

## 📙 Book Reading Log

### ✅ "A Primer in Density Functional Theory" (Springer)
**Chapter 1: _Density Functionals for Non-relativistic Coulomb Systems in the New Century_**
- Historical and mathematical foundations of DFT
- Hohenberg–Kohn theorems revisited
- Universality and constraints in exchange–correlation functionals
- Importance of electron-electron cusp condition
- Non-relativistic Coulomb Hamiltonians as a limit case for functional development

---

## 🧮 Key Equations Learned

### ✅ Time-Independent Schrödinger Equation
\[
\hat{H} \Psi = E \Psi
\]

### ✅ Kohn–Sham Equation
\[
\left[ -\frac{1}{2}\nabla^2 + V_{\text{eff}}(\mathbf{r}) \right] \phi_i(\mathbf{r}) = \varepsilon_i \phi_i(\mathbf{r})
\]

### ✅ Electron Density
\[
\rho(\mathbf{r}) = \sum_{i=1}^{N} |\phi_i(\mathbf{r})|^2
\]

### ✅ Total Energy Functional
\[
E[\rho] = T_s[\rho] + \int V_{\text{ext}}(\mathbf{r}) \rho(\mathbf{r}) \, d\mathbf{r}
+ \frac{1}{2} \iint \frac{\rho(\mathbf{r})\rho(\mathbf{r'})}{|\mathbf{r} - \mathbf{r'}|} \, d\mathbf{r} \, d\mathbf{r'} + E_{\text{xc}}[\rho]
\]

---

## 📝 Notes

- This log will be continuously updated with more advanced concepts such as:
  - Self-consistent field (SCF) procedure
  - Functionals: LDA, GGA, hybrid, meta-GGA
  - Basis sets and pseudopotentials
  - Constrained DFT, Time-Dependent DFT (TDDFT)

---

---

**Last Updated**: June 2025  
**Maintained by**: Sk Toufik Haque

