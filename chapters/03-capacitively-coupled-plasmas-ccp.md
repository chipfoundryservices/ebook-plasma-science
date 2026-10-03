# Chapter 3: Capacitively Coupled Plasmas (CCP) & Frequency Tuning

## 3.1 CCP Reactor Topology
In a Capacitively Coupled Plasma (CCP) reactor, the wafer sits on a powered electrode separated from an opposing grounded or powered showerhead electrode by a gap of $15\text{–}35\text{ mm}$.
- **Electrical Equivalent:** The plasma acts as a central lossy conductor bounded by two capacitive sheaths ($C_{\text{sheath}} = \epsilon_0 A / s$).

## 3.2 Dual-Frequency CCP Architecture
In single-frequency CCPs, increasing RF power increases both plasma density ($n_e$) and ion bombardment energy ($V_{\text{dc}}$), making it impossible to optimize etch rate and selectivity independently. Modern reactors utilize **Dual-Frequency CCP (DF-CCP)**:
1. **High-Frequency Source ($60\text{–}100\text{ MHz}$):** Governs electron heating and ionization density ($n_e \propto \omega_{\text{HF}}^2$).
2. **Low-Frequency Bias ($2\text{–}13.56\text{ MHz}$):** Controls sheath thickness and accelerates ions toward the wafer ($V_{\text{bias}} \propto 1 / \omega_{\text{LF}}$).

By decoupling ionization from ion kinetic energy, chipmakers etch ultra-narrow contact holes with precise sidewall passivation.
